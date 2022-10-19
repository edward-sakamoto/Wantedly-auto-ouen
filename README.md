# Wantedly自動応援ツール
Wantedlyの各募集要項を自動で応援します。

## 前提

node.js、google chrome が入っていることが前提です。
未インストールであれば、こちらからインストールしてください。
https://nodejs.org/en/download/

また、Macで動作確認していますが、他で動くかは保証できません。

## 使い方

### 1. このリポジトリをクローンして、以下のコマンドでセットアップしてください。

```
$ git clone https://github.com/nao0515ki/Wantedly-auto-ouen.git
$ cd Wantedly-auto-ouen
$ npm install selenium-webdriver
```

### 2. CSVファイルを変更し、応援したい募集要項や自分のアカウントを設定してください。

応援したい募集要項は`pages.csv`に追加
応援したいアカウントは`accounts.csv`に追加

### 3. 設定が完了したら、下記コマンドを実行してください。

```
$ node auto-ouen.js
```

