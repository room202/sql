# SQL

## 使用するテキスト

[スッキリわかるSQL入門 第4版 ドリル256問付き！](https://book.impress.co.jp/books/1123101107){:target="_blank"}

## 開発環境

- Visual Studio Code
- Docker
  - MySQL
  - phpMyAdmin

## 開発環境の構築手順

###  Visual Studio Codeインストール

[こちらを参照](https://github.com/room202/vscode/){:target="_blank"}

- 拡張機能を追加
  - MySQL(cweijan.vscode-mysql-client2)

###  Dockerインストール

[こちらを参照](https://github.com/room202/docker/){:target="_blank"}

## ソースコードの保存場所

`C:\work\sql`

## Dockerの起動方法

### Dockerに必要なファイルを用意 (1回だけやればOK)

下記Zipファイルをダウンロード  
https://github.com/room202/sql/raw/main/docker-sql.zip

`C:\work\sql`内に解凍(展開)する

`C:\work\sql\docker-sql\compose.yml`となればOK

### Dockerを起動する

Visual Studio Codeで
  - `C:\work\sql`フォルダを開く
  - メニューバーの`ターミナル`から`新しいターミナル`をクリック
  - `ターミナル`から下記コマンドを実行

 ```bash
cd docker-sql
docker compose up -d
```

コマンドの解説

 ```bash
# Docker設定ファイルのあるフォルダに移動
cd docker-sql

# Docker起動
docker compose up -d

# Docker終了
docker compose down
```

### phpMyAdminへアクセスする  

http://localhost/


