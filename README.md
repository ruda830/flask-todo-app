# flask-todo-app
この記事は書きかけです。
　  
　  
　  
　  
　  
　  
　  
　  
メモ  
(2020/12/25)  
FlaskでHTMLにHello world表示するアプリを作る。  

(2020/12/26)  
HTML内容物の継承(base.html→テキスト内容をindex.htmlへ)  
DBをSQLliteで作り、SQLAlchemyで操作をする。  
POSTをまず作り、methodsでapp.pyと連携。フォームにタスクを書き込むところまで出来た。  
なんかできない。テーブルがないと言われた。→pythonの対話型シェルで>>> from app import db>>> db.create_all()を再度打ち込み、作製。  
→その上でapp.pyを実行すると出来た。POSTとGETをHTML上でも実装出来た。    
detailまで実装。  
同じ要領でdeleteまで実装。  
if elseでupdateまで実装。  
createボタンを追加。
日付を順に並べる。

とりあえず完成。装飾は後回し。
Herokuにtodo-app-ruda830としてデプロイ。  
https://deploytestruda830.herokuapp.com/  