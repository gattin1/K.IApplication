■サービス概要

1文字日記(仮)

1文字日記(仮)は漢字一文字で毎日を記録できる日記形式のサービスです。
このサービスは一見シンプルに見えますが、漢字一文字には多くの意味やニュアンスが込められているため、
ユーザーはどんな1文字で今日という日を締めくくるのかその日一日の自分と向き合うことができるでしょう。


■ このサービスへの思い・作りたい理由

最初は、簡単に三日坊主の人にも書ける日記アプリを作ろうと考え、漢字一文字で表すのがいいのではと思いつきました。しかし、このサービスは、一日をたった一文字で表すというのはある意味、簡単な一行の日記より頭を使うことになってしまいます。これでは書くことにハードルが上がってしまい、三日坊主の人には向かないサービスです。
けれど、同時に一文字日記には他の日記アプリにはない魅力があるのではと考えました。一文字で一日を表現する楽しさ、カレンダーで日記を振り返るとき詳細を見なくても思い出せる使いやすさなど。これは日記をこれから書いてみたい、今までとは違う日記を書きたいと思っているユーザーに刺さるのではないかと思いました。それと当初のターゲットだった三日坊主の人にも書いてもらえる機能も実装したいと考えています。

■ ユーザー層について

今までとは違った日記を書いてみたい人
日記を書いても読み返すことがない人(カレンダーを見るだけでも一カ月を振り返れる)
漢字が好きな人

■サービスの利用イメージ

スマホで夜、落ち着いた時間にサービスを利用することで自分自身と向き合う事ができる。（ レスポンシブ対応）

■ ユーザーの獲得について

Xでの発信

■ サービスの差別化ポイント・推しポイント

その日の感情を5段階の顔文字とシンプルなメモで記録するアプリがありますが、この一文字日記はそのような機能も兼ね備えながら、それに加えカレンダーで1か月分の一文字を表示することが出来ます。また、一文字とともに感情も5段階から選択してもらい、その感情によって文字の色が変わる機能も実装予定なのでこれによってより直感的に分かりやすく振り返ることができます。それに加え、当初のターゲットユーザー層だった一文字を考えるのが面倒な人、今日は思いつかないなという人に向けてAIによる一文字提案機能も実装予定です。

■ 機能候補

### MVP
* 会員登録
* ログイン
* 一文字日記作成(メモ機能も)
* 日記詳細
* 日記一覧(カレンダー表示)
* レスポンシブ対応

### 本リリースまでに
* 通知機能
* 気分を選択する機能
* 気分によって文字が変わる機能
* googleログイン機能
* 1か月分の気分を円グラフ化する機能
* 簡単に一文字を提案してくれるAIを使ったサジェスト機能

■ 機能の実装方針予定

カレンダーはRailsのgemのSimpleCalender、通知機能はLINE Messaging API SDK for Rubyを使用予定です。
