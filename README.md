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

[こちらを参照](https://github.com/room202/java?tab=readme-ov-file#%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83%E3%81%AE%E6%A7%8B%E7%AF%89%E6%89%8B%E9%A0%86)

- 拡張機能を追加
  - MySQL(cweijan.vscode-mysql-client2)

###  Docker インストール

- 事前準備
  - Windowsの機能の有効化
    - Windowsスタートボタンの右横にある検索バーで「Windowsの機能の有効化または無効化」と検索する
    - 検索にヒットした「Windowsの機能の有効化または無効化」をクリックして起動する
    - 下記項目のチェックをONにする
      - 「Linux用windowsサブシステム」
      - 「仮想マシンプラットフォーム」
  - x64マシン用WSL2 Linuxカーネル更新プログラムパッケージのダウンロードとインストール
    - 下記ファイルをダウンロードしてインストールする  
    [https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)

- Docker のインストール  
[http://docs.docker.com/desktop/install/windows-install/](http://docs.docker.com/desktop/install/windows-install/)

 ### Dockerの起動コマンド

 ```bash
# Docker設定ファイルのあるフォルダに移動
cd docker-sql

# Docker起動
docker compose up -d

# Docker終了
docker compose down
```

- phpMyAdminへアクセスする  
[http://localhost/](http://localhost/)

## ソースコードの保存場所

C:\work\sql
