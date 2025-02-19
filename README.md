## サービス概要
「Misohito」は57577の31字でツイートができるSNSのアプリ。ツイートは30字以下でも32字以上でも投稿できず、31字ぴったりでないと投稿できない。
基本はクラスメートの短歌が表示されるが、クラス番号や入学年度で絞り込むと、他のクラスの友達や先輩などクラスメート以外のユーザーの短歌も見られる。

## ■ このサービスへの思い・作りたい理由
<p>中学校の国語の教員だったとき、次の3つのことを感じたため。<br>
<ul>
  <li>生徒が手軽に短歌を作成でき、かつリアルタイムで閲覧できるアプリがほしい。</li>
  <li>他のクラスの生徒の作品も見てもらいたい。</li>
  <li>タブレットだけで授業の導入から生徒の評価までを完遂したい。</li>
</ul>
短歌は抽象的で掴みにくい。文語文で書かれているもあるし、見たことも聞いたこともない作者も多い。<br>
これらが、生徒と短歌の間に「距離」を作ってしまう。<br>
しかし、裏を返せば「口語で書かれたもの」で、かつ「仲の良い友達が書いたもの」であれば、生徒は短歌に興味を示す傾向にある。<br>
生徒と短歌の「距離」を埋めたいと思ったのが、アプリ開発の動機である。<br></p>

<p>また、1つのアプリで教師の課題も解決できるのではないかと考えた。<br>
短歌の授業で、実際に私が抱えていた課題が下記である。<br>
<ul>
  <li>短歌を作成するためのステップアッププリントを毎時間印刷しないといけない。</li>
  <li>生徒が作った短歌をクラス全員に見せるには黒板に手書きするしかない。</li>
  <li>評価をしたいのに生徒がプリントをなくしてしまう。</li>
</ul>
短歌投稿作成画面では、初めてでも短歌が作れるように、感情が動いた瞬間を書く→その瞬間を象徴する名詞をピックアップする→短歌を作成と画面が遷移していく予定だ。<br>
また、アプリにはユーザー検索機能がある。そのため、生徒の作品にすぐにアクセスしてモニターに表示することができるし、評価もスムーズにできると考えた。<br></p>

## ■ ユーザー層について
中学2年生<br>
短歌の単元が中学2年に設定されているため。<br>

## ■　サービスの利用イメージ
### ユーザー登録・ログイン前
ユーザーはサイトにアクセス後、ログインまたは新規登録を選択<br>

*【新規登録の場合】*<br>
下記の項目をプルダウン、またはテキストで入力し、ユーザー登録を行なう。<br>
<ul>
  <li>入学した年</li>
  <li>クラス</li>
  <li>出席番号</li>
  <li>名前</li>
  <li>パスワード</li>
</ul>

*【ログインする場合】*<br>
下記の項目をプルダウン、またはテキストで入力し、ログインする。<br>
<ul>
  <li>学校名</li>
  <li>入学した年</li>
  <li>クラス</li>
  <li>出席番号</li>
  <li>名前</li>
  <li>パスワード</li>
</ul>

### ユーザー登録・ログイン後
下記が可能になる。
<ul>
  <li>投稿された短歌を一覧画面で鑑賞</li>
  <li>短歌の作成・投稿</li>
  <li>ユーザー検索</li>
  <li>学習ページの閲覧</li>
</ul>

#### ◇ヘッダー
ロゴ/ホームボタンのほかに、新規投稿・検索・マイページへ遷移するボタンを設置。<br>

#### ◇マイページ
自分の投稿一覧を見ることができる。<br>

#### ◇短歌作成・投稿機能
短歌は概ね、下記の流れに沿って作られる。<br>
<ol>
  <li>感情が大きく揺れ動いた瞬間のエピソードを書き出す</li>
  <li>その瞬間を象徴する名詞をピックアップする</li>
  <li>名詞を用いながら短歌の定型に落とし込む</li>
</ol>
短歌作成画面では、この3つのステップをそれぞれ入力するフォームがあり、流れに沿って短歌を作成できる。<br>
ステップ3以外の入力は必須ではないので、短歌のみを投稿することも可能。<br>

#### ◇投稿一覧画面
投稿一覧画面では、短歌が新規順で一覧表示される。<br>
投稿が見やすいように、ページネーションを用いて10件ずつ表示。<br>

#### ◇ユーザー検索機能
入学した年、クラス、出席番号、名前のいずれかを入力すると、ユーザーが検索できる。<br>
検索結果の画面では、検索内容に合致したユーザーが一覧で表示される。<br>
表示されたユーザーをクリックすると、詳細画面に遷移する。詳細画面では、ユーザーの投稿が一覧表示される。<br>
これにより、他のクラスのユーザーの短歌もスムーズに鑑賞することができる。<br>

#### ◇学習ページ
テスト勉強や復習、自主学習用に、下記のようなページを閲覧できる。<br>
<ul>
  <li>短歌とは？</li>
  <li>表現技法</li>
  <li>歌人一覧</li>
</ul>

## ◼︎サービスの補足
### 新規登録でメールアドレスを使わない理由
Google Workspace for Educationを利用・活用している学校であれば、Googleアカウントを持っている。<br>
しかし、ICT推進が遅れている学校では、タブレットは持っていても個人のメールアドレスを持っていないケースがある。<br>
そのため、新規登録にはメールアドレスは用いないこととした。<br>

## ◼︎ユーザーの獲得について
Xを用いて宣伝し、新規ユーザーの獲得を目指す。<br>
また、前職の同僚に相談し、授業で活用できないか打診する。

## ◼︎サービスの差別化ポイント・推しポイント
【類似サービス】
<ul>
  <li>57577</li>
  <li>X</li>
</ul>
いずれも新規登録時にメールアドレスが必要であるうえ、「短歌の知識面を学習する」ことはできない。<br>
またXはともかく、57577はネイティブアプリのため、メールアドレスを持っていたとしても、iPadを支給されている学校でしか授業で活用できない。<br>
当アプリは、メールアドレスなしで短歌を投稿・閲覧できるだけでなく、学習でも使えるページを網羅している。<br>
そのため、授業・評価・学習の3つの面では、他のアプリよりも優れた設計になっている。<br>
メインのユーザー層の中学2年生と教師には価値のあるアプリだと言える。<br>



## ◼︎機能候補
*【MVPリリース時】*<br>
<ul>
  <li>新規登録/ログイン</li>
  <li>短歌作成・投稿</li>
    <ul>
     <li>感情が大きく揺れ動いた瞬間のエピソードを入力するフォーム</li>
     <li>感情が大きく揺れ動いた瞬間を象徴する名詞を入力するフォーム</li>
     <li>短歌を入力するフォーム</li>
    </ul>
  <li>縦書き表示</li>
  <li>ユーザー検索機能</li>
</ul>

*【本リリース時】*<br>
<ul>
  <li>他のユーザーの投稿にコメントできる機能</li>
  <li>ページネーション機能</li>
  <li>利用規約・プライバシーポリシー</li>
  <li>新規登録時に日本の学校情報APIから学校名を選択できる機能</li>
</ul>

## ■ 機能の実装方針予定
<ul>
  <li>ログイン機能（device）</li>
  <li>ページネーション機能（kaminari）</li>
  <li>ユーザー検索機能（Form Object）</li>
  <li>利用規約・プライバシーポリシー（high_voltage）</li>
  <li>日本の学校情報API</li>
</ul>

