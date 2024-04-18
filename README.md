# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
### リモートリポジトリ
- 専用のサーバに配置して複数人で共有するためのリポジトリ(今回はGit Hub)
### ローカルリポジトリ
- ユーザ一人ひとりが利用するために、自分の手元の機械上に配置するリポジトリ(今回はMy MacBook)
 

## プッシュとマージの違いは何でしょうか？
### プッシュ
- ローカルで編集したファイルや追加したファイルをローカルリポジトリからリモートに送る
### マージ
- 同じリポジトリ同士でブランチのデータを統合する


## コミットとプッシュの違い
### コミット
- ローカルで編集したファイルや追加したファイルをローカルリポジトリに登録すること(今回はGit Hub)
### プッシュ
- ローカルで編集したファイルや追加したファイルをローカルリポジトリからリモートに送る

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 何をしたのかわかるように書く<br>ただし長くなってしまうとわからなくなってしまうので先頭にプレフィックスをつけるとなお良い<br>(例)<br>・add	: 新しいファイルや機能を追加する場合に使用<br>・change : 	仕様変更により、既存の機能に修正を加えた場合に使用<br>・feat : 新しい機能やファイルを追加する場合に使用


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
### ローカルでマージするフロー
- 自分で統合することですぐに反映できるが、自分一人なので間違えてることも
### プルリクエストでマージ
- 責任者が確認して統合することで二重確認ができるが、時間がかかる

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先行マージもしくは後行マージを優先して内容を読み込む、もしくは両方の内容を読み込む<br>ただし相手と相違あった場合話し合いで解決に導く