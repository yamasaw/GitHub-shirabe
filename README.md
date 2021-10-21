# GitHubについて調査まとめ 個人用

## GitHub CLI
### 概要
GitHubで行う操作をWebを使わずコマンドラインで実行が行える。

わざわざマウスを使って操作する手間が減るので便利

最近 GitHub CLI 2.0が公開された(なので今までの記事は使えないものがあったりする)

個人的にはGitHub Actionsがコマンドの入力で実行できそうなのでそれが便利か

### install & setup
#### install

公式サイトからインストーラをダウンロードし、インストールを実行

https://cli.github.com/

Macの場合brewを使いインストールすることも可能 `brew install gh`

### Setup

コマンド gh auth loginを入力し認証を行う。

以下入力を求められるので回答していく

What account do you want to log into?
オンプレミス(社内)向けのプランなのかの問
GitHub.com (Web版)を指定する

How would you like to authenticate GitHub CLI?
この問いはLogin with a web browserを指定する。(tokenを作るのが面倒なので)

## GitHub Pages

## GitHub Gist

## Advanced search(コードの内の高度検索機能)
特定のワードに対して検索をCode、Commits、Issueなどがワード検索ができる

https://github.com/search/advanced

検索結果に対してURLでやりとりができるのでコードのglep検索を相手に伝える際とか便利​

## そのほか便利機能
### GitHubサービス上のショートカットキー
https://qiita.com/unbabel/items/1cf05f2a2be3d6fb3388#%E3%82%B7%E3%83%A7%E3%83%BC%E3%83%88%E3%82%AB%E3%83%83%E3%83%88%E3%82%AD%E3%83%BC​

### Git.io
GitHub上のULRを短縮できるサービス。需要ある?
https://git.io/

### GitHubサービス上でVSCを起動
Web上でVisual Studio Codeが起動できるようになるらしいです。現在クローズドでお試し利用ができる
codespacesっていうサービスらしい
https://github.co.jp/features/codespaces

### GitHub REST API とかあるらしい

新機能調査時に参考になるもの
GitHub Blog
https://github.blog/
