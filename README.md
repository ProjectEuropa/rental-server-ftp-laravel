# Laravel on レンタルサーバーの使い方

## ディレクトリ構造

```
Laravel-Project
├── .env Laravelアプリケーションの環境設定ファイル
├── app #Laravelアプリケーションのメインディレクトリ
├── artisan #基本編集しない(artisan コマンド設定ファイル)
├── bootstrap #基本編集しない(Laravel設定ディレクトリ)
├── composer.json #composer設置ファイル
├── composer.lock #composer設置ファイル
├── config #Laravel全般の設定ディレクトリ
├── database #データベース設定関連ディレクトリ
├── package.json #基本編集しない
├── phpunit.xml #基本編集しない
├── public #公開ディレクトリ
├── resources #view関連で設定するディレクトリ
├── routes #ルーティング設定ディレクトリ
├── server.php #基本編集しない
├── storage #基本編集しない
├── tests #基本編集しない(テストコード関連ディレクトリ)
├── vendor #基本編集しない
└── webpack.mix.js #基本編集しない(Node.js実行時には設定が必要です)
```
