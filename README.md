# SQ4R読書術テンプレート

--
## 複製方法
- リモートリポジトリをGitHub上で作成
- ローカルでリモート用のディレクトリを作成
```bash
mkdir book-name
cd book-name
```
- ローカルのディレクトリ内で.gitを複製元からコピー
```bash
git clone --mirror git@github.com:niwoshi/SQ4R-template.git .git
```
- originを変更
```bash
git remote set-url origin git@github.com:[user-name]/[book-name].git
```
- 複製先のリモートリポジトリにPush
```bash
cd .git
git push --mirror git@github.com:[user-name]/[book-name].git
```
- ディレクトリを空にするかディレクトリ毎消去してリモートリポジトリをcloneしなおす
```bash
git clone git@github.com:[user-name]/[book-name].git
```

参考: https://qiita.com/syuji-higa/items/e380289502c7896daf0f
--

## Survey
- 目次を見る
- 学びたい内容3つ書く
- 1つ選んで読む
- 全体の調査
  - 20pごと
  - 1文のみ
  - 目次など
  - 図・グラフ

## Question
- 本の内容を予測する
  - 要するに？
- 目次を質問にする
  - 自分の予測

## Read
- 答え合わせ（回答を作る）

## Respond
- 要約する
  - 全体＋3つ
  - Connecting
  - 図解

## Record
- 要約した内容と本の内容を照会する

## Review
- 要約を確認する
- 後日再度確認する
