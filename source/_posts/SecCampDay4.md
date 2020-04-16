---
title: セキュリティ・キャンプ全国大会2019 DAY4
date: 2019-08-16 22:25:42
tags: [SecCamp,セキュキャン,プログラミング,OS]
---

## やったこと
今日は開発の最終日。
さらに、16:00-はトラック内発表会の予定だったので、実質作業できた時間はかなり少なかったです。

昨日でシリアル割り込みが実装できたので、この日からスレッドの実装です。

ここからは(と言ってももうキャンプの期間も終盤なのですが)[12ステップで作る、組み込みOS自作入門](http://kozos.jp/books/makeos/index.html)を参考に学習を進めました。

時間との勝負。トラック内発表の16:00に合わせて、15:40までに資料提出でした。
ということは、作業できるのは実質15:00まで。それまでにスレッドが実装できるかというところでした。

が、結論から言うとできませんでした。

まずこれまでに作ったハンドラやシリアルのライブラリをkozosのinterfaceに合わせて改変し、その上でスレッドのプログラムをコピってきてエラーを潰しながらというアプローチでやりました。
ここでは開発の詳細はあまり詳しく書かないことにしますが(明日の出発に備えて荷物を片付けないといけないので時間がない)、後から西永さんに聞いたところだと、TCB(Task Control Block)の初期化がうまく行っていないのでは?とのことでした。
キャンプ後直したいと思います。

と言う感じで、スレッドが大変だった今日の開発です。

さて、開発タイムが終わり、トラック内発表会。 
YトラックはOSゼミと一緒にCコンパイラゼミもあるので、そちらの発表も含めて聞きました。
詳細は割愛しますが、**各々に**興味深いものづくりをされていて、集中開発コースならではだなと思いました。
楽しかったです。

選択コースを受講していないので何とも言えませんが、集中開発コースがいいんじゃないかしら?

夜には、**ラストナイトイベント** がありました。

このイベント、要は講師やスポンサーからのプレゼント分配会で、書籍やステッカー、バックパックなどがありました。
BlackHutのバックパック、僕はゲットできませんでしたがめっちゃかっこよかったです。

このプレゼントの取り順ですが、昨年は年齢が小さい方からだったそうです。 **が、** 今年は違いました。

今年は、「グループワークのチーム名のhash値が若い方から」というなんともSecCampな手段。

うちのチームのハッシュ値は......なんと `ff`始まり........オワタ( ・∇・)

と言う訳であまりhash値運はよくなかったのですが、

- [Interface 2019年9月号 テクノロジを実装せよ-農業＆自然センシング大研究-](https://interface.cqpub.co.jp/magazine/201909/)

- [トラ技Jr. 2018年秋号（第35号）-サウンド・ミキサ/ピュア・オーディオ/重低音ドライブ…アナログDJ学園へようこそ音遊び!　ディスクリート・アナログ回路集-](https://toragi.cqpub.co.jp/Portals/0/support/junior/backnumber/2018/10_aut/contents.html)

- [やさしく学ぶ 機械学習を理解するための数学のきほん アヤノ＆ミオと一緒に少しずつ学ぶ 機械学習の理論と数学、実装まで](https://book.mynavi.jp/ec/products/detail/id=77270)

をいただきました。

このあと、企業紹介を聴きました。
[GMOペパボ株式会社](https://pepabo.com)から、話してくださったのは、[@mad_osho](https://twitter.com/mad_osho)さん。
主に企業環境みたいな話が中心でした。

これはペパボさんに限った話ではないですが、各社「企業のお仕事紹介」のコーナーなのに普通にミニ企業説明会をやっていたのがじわりました。

グループワークでは、今回は割とたくさん話を聞けました。
それと、これまでの話し合いの内容をまとめて、明日のスライド作り&&提出に備えました。

さて、それでは荷物を片付けます。明日は最終日。頑張ろう。 講義よりも外の暑さが心配です()