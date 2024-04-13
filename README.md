# SQL

## 使用するテキスト

[スッキリわかるSQL入門 第4版 ドリル256問付き！](https://book.impress.co.jp/books/1123101107)

## 開発環境

- Visual Studio Code
- Docker
  - MySQL
  - phpMyAdmin

## 開発環境の構築手順

###  Visual Studio Code インストール

[こちらを参照](https://github.com/room202/vscode/)

- 拡張機能を追加
  - MySQL(cweijan.vscode-mysql-client2)

###  Docker インストール

[こちらを参照](https://github.com/room202/docker/)

### docker-sqlの起動コマンド

 ```bash
# Docker設定ファイルのあるフォルダに移動
cd docker-sql

# Docker起動
docker compose up -d

# Docker終了
docker compose down
```

### phpMyAdminへアクセスする  
[http://localhost/](http://localhost/)

## ソースコードの保存場所

C:\work\sql
