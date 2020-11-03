---
layout: post
title: 未踏ジュニア期間を振り返る
date: 2020-11-03 14:45:19
tags: ["未踏ジュニア", "critica"]
---

おひさしぶりです伊藤です。
ここには書いていませんでしたが、5 月から 11 月まで[未踏ジュニア](https://jr.mitou.org/)に採択され、メンターの[関さん](https://twitter.com/YoshifumiSeki)にサポートいただきながら相方の[ようかん](https://twitter.com/inoue2002)と一緒にフォームアプリケーション [critica](https://critica.uno/)を作ったので、その期間を振り返ってみようと思います。

## 採択前

### 相方との出会い

今年の 1 月 26 日に、ようかんから Twitter DM で連絡がきました。
これがようかんとの出会いです。初めは怪しい駆け出しエンジニア系なんじゃねーかと思ってました笑

{% asset_img encounter.png %}

話を聞いていると、私がメンターをしている　[CoderDojo 大津](https://coderdojo-otsu.connpass.com/) のチャンピオンの方がご紹介下さったとのことでした。
そこで、その方に「『ようかん』を名乗る方から連絡が来たのですがこの方は実在する方ですか?」とか言って確認しました w

その後、[草津の Starbucks](https://store.starbucks.co.jp/detail-1614/)でお話しすることにしました。

話し合っていて、その時間のうちにこいつとならなんか作れそうだなという直感が働きました。

で、その日のうちに未踏ジュニアに応募しようぜという話になりました。

### 提案まで

応募しようぜという話になってから、その日のうちにスタバから[UDCBK](https://www.city.kusatsu.shiga.jp/shisei/sisetsuannai/community/UDCBK/index.html)に移動して、そこのホワイトボードを借りてブレストしました。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/ItyuJ?ref_src=twsrc%5Etfw">@ItyuJ</a> とお話してきた。バカ楽しかった。<br>人生で1番濃い時間を過ごしたかも。<br><br>会って1日目なのにまだ秘密にしなければ行けないレベルの話まで落とし込む事もできたw<br><br>「お互いが求めてた人材だった」<br><br>これから定期的に会って、日本変えていきます<br>繋げてくださった皆さん、そしてコミュニティに感謝 <a href="https://t.co/noozseFZtb">pic.twitter.com/noozseFZtb</a></p>&mdash; ようかん / Yosuke Inoue (@inoue2002) <a href="https://twitter.com/inoue2002/status/1223544009718562816?ref_src=twsrc%5Etfw">February 1, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/inoue2002?ref_src=twsrc%5Etfw">@inoue2002</a> と初顔合わせでしたが、筋道ある議論ができる、パッションが確立した県内のIT系高校生に初めて会いました。ほんとうにキモすぎるやつです(褒め言葉)。<br><br>少し大きめのプロジェクトを動かす感じになったので、これから一緒に突き進んでやろうと思います。楽しいなあ♪</p>&mdash; Yusei Ito (@ItyuJ) <a href="https://twitter.com/ItyuJ/status/1223548340387737600?ref_src=twsrc%5Etfw">February 1, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

そこで、critica の原型となったアプリケーションの構想が固まりました。
それ以降もちょくちょく zoom で話し合いながら、提案書を書いていき、応募しました。

### 採択まで

応募後、しばらくして 1 次通過と面接の連絡が来ました。
担当メンターが関さんであると、その時のメールでわかりました。
ですが関さん、こんな tweet や

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">今年の提案はまたレベルが全体として上がっており、特にプロトタイプがあったり、すでに完成して改善のプロセスに入っているものも多い印象でした。企画も非常に細かく練られており、楽しく読ませていただきました。選ぶのがめちゃめちゃ大変でした！</p>&mdash; Yoshifumi Seki / 関 喜史 (@YoshifumiSeki) <a href="https://twitter.com/YoshifumiSeki/status/1251082400584486913?ref_src=twsrc%5Etfw">April 17, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

こんな tweet

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">来年以降、「 <a href="https://twitter.com/hashtag/%E6%9C%AA%E8%B8%8F%E3%82%B8%E3%83%A5%E3%83%8B%E3%82%A2?src=hash&amp;ref_src=twsrc%5Etfw">#未踏ジュニア</a> のためにアイデアを考える」という提案はもう殆ど通らないんじゃないかなって気がするので、今年応募できなかったり、このあと落選してしまって、来年のチャレンジを考えている人はいまから作り始めるぐらいがいいんじゃないかなぁという気がします。</p>&mdash; Yoshifumi Seki / 関 喜史 (@YoshifumiSeki) <a href="https://twitter.com/YoshifumiSeki/status/1251082895491358720?ref_src=twsrc%5Etfw">April 17, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

さらにはこんな tweet までしてらしたので

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">未踏ジュニアの2次専攻である面接がそろそろ始まりますが、僕は今回書類通過を他のPMの2~3倍出しておりますので、僕が面接担当だった人は通常の2~3倍の倍率が面接でもあることを踏まえて気合いれて面接に臨んでください。素敵なプレゼンテーションを楽しみにしています</p>&mdash; Yoshifumi Seki / 関 喜史 (@YoshifumiSeki) <a href="https://twitter.com/YoshifumiSeki/status/1252775798349561856?ref_src=twsrc%5Etfw">April 22, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

正直めちゃビビってました。
一発目の面接ではサービス一般のプレゼンをしました。ここで関さんには原始的な critica を触っていただきました。
その後、面接 2 回目の連絡が来ました。
それまでに、COVID-19 に対してどうするかや価値測定どうするかなどについて教えてね、みたいなメールをいただいていたので、それについてようかんとさらにブレストして、COVID 時代の新機能（これが将来的に critica に実装される discussion になる)や定性・定量両面からの効果測定の手法をどうする気かなどをプレゼンしました。

効果測定の手法の話でめっちゃ褒めていただいて嬉しかったのを覚えています。

そして、ようかん、おれと[しんぶんぶん](https://twitter.com/shinbunbun_)とで[レッドハッカソン](https://www.pref.hiroshima.lg.jp/site/innovation-event/redhack2020online.html)に出ている日に採択のメールが来ました。
届いた瞬間はハッカソン中でようかんと zoom で話していたのでリアルタイムに喜びました。

### 採択後

採択後のことは、割と成果報告で話したので、それでみてもらえるかなとは思います。

<style>
.youtube-video-container {
  position: relative;
  width: 100%;
  margin-bottom: 20px;
}
.youtube-video-container:before {
  content: "";
  display: block;
  padding-top: calc(9 / 16 * 100%);
}
.youtube-video-iframe {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}
</style>
<div class="youtube-video-container">
<iframe width="100%" height="100%" class="youtube-video-iframe" src="https://www.youtube.com/embed/GuanTTXfF7I?start=2147" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

が、せっかくなので各イベント前後のことは書いておこうかなと思います。

#### ブースト会議前

ブースト前は主にマイルストーン設定とかプロトタイプの改善とか比較的抽象度の高いことをしていました。
ここでは関さんに目標から下ってマイルストーンを設定していく手法を教わりました。

#### ブースト会議後~中間前

ブーストで出たコメントを整理して、そこからどんどん V1 を実装していきました。この期間が一番コード書いてたんじゃないかな。
この期間で、高速化とかやってたので、他の PJ の PM の方々にも色々技術的なことを教わってました。

#### 中間合宿

ここでは、未踏ジュニアの他のクリエータの方に critica 使ってみて!!ってやってました。

#### 中間後

中間では、ブーストで出た「Google Forms と違うところは?」　みたいな質問が出てこなかったのが、新しいものを作って理解されてきたっぽさがあって嬉しかったです。

しかし、「UI もうちょっと頑張ってほしい」とか「プレースホルダが不親切」といったコメントも出ていたので、UI がんばるぞの気持ちに火がつきました。

その後、[三橋さん](https://twitter.com/YukiMihashi)に UI のレビューをしていただいたりしました。

このあと色々考えて、UI を Vuetify ベースのめっちゃ Material な感じからあえて脱却させました。そしてロゴを導入しました。
この期間でかなり UI はよくできたと思っていて、この決断はよかったなと思っています。

それだけでなく、オフラインのイベントでのユーザテストとかもこの時期にやったので、仕上がっていく感があってかなり楽しめました。

#### 成果報告

僕の成果報告のことは YouTube でみられるからまあいいと思うのですが、ブースト当初から僕の中で特に推しているのは Spagettian, MER, Flight fit VR 　でした。
[igarashi](https://twitter.com/TheGodOfNeet)さんと[hakke](https://twitter.com/HAKKE_sabage)くんが発表の中で critica を成果報告でも使ってくれたのがとても嬉しかったです。

この 2 人は中間後のインタビューに付き合ってくれた人たちのうちの 2 人でもあって、もらったフィードバックを受けてかなり色々改善したので、ご期待の挙動を critica ができているといいなと思います。

### 修了した今思うこと

**とにかくめっちゃたのしかったです。**

なんだか、あっと言う間でした。この期間を通して学んだものや得たものは計り知れません。
未踏 Jr コミュニティとそのスポンサーさま全体に感謝しています。
特に、価値をつくる過程を鋭い指摘で応援してくれたメンターの関さんに本当に感謝しています。もはや憧れまで覚えています。

特に、8 月のミーティング以降関さんが critica のことを「君たちの...」ではなく「僕らの...」って言ってくれるようになった時が実はとても印象に残っています。
最後の最後まで「発表直前追い込み祭り」にも付き合っていただき、本当にありがたかったです。

未踏 Jr 期間は終わりましたが、今後もそこでできたつながりと知見でいろんな活動を推進して技術で課題を解決し続けたいと思います。

そして最後に、ここまで頼りないメインクリエータと一緒に ciritca をやってきてくれた nice guy すぎる相方のようかんに感謝しています。
本当にみなさんありがとうございました。

最後に、この記事を読んだ感想など教えていただけると嬉しいです!

<style>	
.critica-container{
    position:relative;
    width:100%;
    max-height:600px;
    min-height:300px;
    overflow:hidden;
}
.critica-container iframe{
    position:absolute;
    top:0;
    left:0;
    width:100%;
    height:100%;
}
</style>
<div class="critica-container">
 <iframe src="https://critica.uno/279929/iframe"  width="560" height="360" scrolling="no" style="overflow: hidden; width:100%;"></iframe>
</div>
