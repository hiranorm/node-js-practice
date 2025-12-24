# ex-gen-app
expressモジュールのチュートリアルプログラム
（作業中）
ファイルをダウンロード
``npm install``
でパッケージ類をダウンロード
``npm start``  
でローカル3000番にサーバーが立つ

# hello
``localhost:3000/add``　フォームに入力してデータを追加する  
適切でないデータはバリデーションで弾く仕様になっている  
``localhost:3000/hello/delete?id=3``　とか指定してデータを削除する（ボタンを押すと削除）  
``localhost:3000/hello/edit``　フォームに入力してデータを編集する  
``localhost:3000/hello/find``　フォームに入力してデータを検索する  
``localhost:3000/hello/show?id=2``　など、idを指定してデータベースのデータを参照する 
``localhost:3000/bord`` メッセージボードアプリ
``localhost:3000/md``  Markdownデータベースアプリ
ユーザー登録すると使える

# 必要なパッケージ
Express
Express Session
sqlite3
Sequelize
sequelize-cli
