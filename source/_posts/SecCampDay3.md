---
title: セキュリティ・キャンプ全国大会2019 DAY3
date: 2019-08-15 22:13:14
tags: [SecCamp,セキュキャン,プログラミング,OS]
---

## やったこと
今日は開発の中日でしたが、企業紹介やグループワークなどがあったので、夜は作業ができませんでした。

まず、昨日のリンカスクリプトで潰れた日を取り戻すべく、シリアルの実装を進めました。

Hello,Worldに続いて、入力の読み込み,echoなどを、**ポーリングベースで**実装しました。

その後、これまでで散らかしたシリアル周りのコードをざっとリファクタして、割り込みを実装し始めました。
まずは同期(Sync)割り込み(内部割り込み)からはじめました。

aarch64のアセンブリ的には  `svc` を発行することで発火する割り込みです。

svcがけられたらprintするのを実装しました。


同期から始めたのは、講師の[tn](https://twitter.com/tnishinaga)さんがそうするよう勧めてくれたからです。
シリアル割り込みなどから着手すると、ベクタテーブルの設定がおかしいのかペリフェラルの設定がおかしいのか特定するのが大変なので、ベクタテーブルの設定と　`DAIFClr` を正常に実行できればとりあえず動くsyncから始め流ようにとのことでした。ふむふむ。

同期割り込みは割とサクッと実装できました。割り込みベクタ周りは、実装よりも概念が面白かったです。すごく**メモリを感じる**概念で、楽しいですね。

そのあと、シリアル割り込みを実装しました。
これも、ビット演算のところで `&`を誤って`&&`にしてしまったせいで割り込み原因がまともに特定できず、割り込みハンドラを駆動できないないなどのしょーもない穴にはハマりました。

また、これは講義が終わって夜になってから気づいたんですが、RXのデータの取りこぼしがあって、何だろうと思っていたら、RXのデータは全て一回のハンドラで読み切らないと、一度かかった割り込みをクリアしたらデータがFIFOに残っててももう割り込みがかからないのが理由でした。

普段書いてるようなシリアルのコードは連続で送り続けるものばかりなので、あまり気にしていなかったので、気づきにくかったです。きちんとループを回して、割り込みのうちに見つかるデータは抜き切っておかないといけないようです。

そんなこんなで、割り込みの実装を終えて今日の開発は終わりました。

さて、時間は前後しますが、昼間の開発が終わった後、夜には企業紹介がありました。

僕は、インテリジェント・ウェイブさんと、ソフトバンクさんを聞きました。

前者は担当者が営業側の方で、開発サイドではないので僕にとっては今ひとつな印象ではあったのですが、イスラエルがなぜサイバーセキュリティの分野で強いのかというのが面白かったです。

  1.「サイバー軍」に兵役する人がいるので、攻撃手法をよく知っている。
  2.輸出する資源がない

1はそんな気がしていましたが、後者はそーいやそうだったという感じでした。

SoftBankは開発のかたで、その中でも特にユーモア豊かな方だったので面白かったです。 : [にゃん☆たく](https://twitter.com/taku888Infinity)さん

グループワークは、主にグループ内の方針決定のためのディスカッションに充てました。本当はもっとインタビューができた方が良かったと思うので、明日取り戻せるよう頑張ります。
