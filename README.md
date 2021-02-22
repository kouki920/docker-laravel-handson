# docker-laravel 開発練習

### 3層アーキテクチャのコンテナの構築
* ウェブサーバー(web)
  nginxで静的コンテンツ配信サーバを構築
* アプリケーションサーバー(app)
   nginxを経由してPHPを動作させるアプリケーションサーバを構築
   PHPパッケージ管理ツールComposerのインストール
   
* データベースサーバー(db)
  MySQLデータベースサーバーの構築
