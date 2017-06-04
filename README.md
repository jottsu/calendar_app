<<<<<<< HEAD
<概要>
このアプリケーションは、1つのグループに所属するユーザーが、自分の予定およびグループ共通の予定をカレンダー上で管理することができるアプリケーションである。


<各ページの説明>
【認証ページ】
・ユーザーはアカウント登録時に、所属するグループも登録する。既にそのグループが存在している場合はそこに所属し、存在しないは新しいグループが作成される。

【マイページ】
・カレンダーに、ログインしているユーザー個人の予定およびグループで共通の予定が表示される。
・このカレンダー上で、各ユーザーは個人の予定を自由に管理（追加・変更・削除）することができる。

【グループページ】
・グループのメンバーリストおよびグループの共通カレンダーが表示される。
・各メンバー名の右隣にある「カレンダーを見る」をクリックすると、そのメンバーの予定を見ることができる。編集することはできない。
・グループの共通カレンダーには、共通の予定のみが表示される。そのグループに所属するメンバーは誰でも自由に共通の予定を管理することができる。


<工夫した点>
・誰でも編集可能な共通カレンダーを１つ用意し、個人のカレンダーとリンクさせることで、例えば会議や飲み会など、グループで共通の予定を各個人が設定する手間を省けるようにした。
・グループの他のメンバーのカレンダーを閲覧可能にすることで、ユーザーがメンバー全員の予定を把握することができるようにした。
・個人のカレンダーでは、個人の予定とグループ共通のの予定を色分けすることで、それぞれを瞬時に区別できるようにした。


<苦労した点>
・カレンダーのビューを素早く実装できるfullcalendarというプラグインを使用したが、カスタマイズするにあたって日本語のドキュメントが少なく、英語で探す必要があった。
・カレンダーに表示する予定（Eventオブジェクト）のCRUD機能を実装するにあたって、ログイン中のユーザーであるかどうかや、グループ共通の予定であるかどうかなどによって機能の自由度を指定する必要があり、少し複雑な設定になった。


<問題点・さらに改善できる点>
・おそらくjavascriptの問題で、カレンダー上の予定をクリックして詳細を表示し、そこからブラウザバックした時に同じカレンダーが２つ表示されてしまう。（リロードすると直る。）
・予定を追加したり編集したりする際に、フォームをモーダルで表示しajaxでそのままカレンダーに反映させることができれば、ユーザーにとってより使いやすいものになる。
・カレンダーに表示される予定の色を複数用意し、ユーザーは予定を登録する時に好きな色を選べるようにすればより使い勝手が増す。
=======
# calendar_app
>>>>>>> origin/master
