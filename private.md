## 個人にまつわる技術について

遡ると量が多くて書くのめんどくさいので、直近1年位でやったことをまとめていく。

### レポジトリ

#### dotfiles
url: [takeokunn/dotfiles](https://github.com/takeokunn/dotfiles)

`core: dotfiles/vim/nano/tmux` `fish: fish shell/peco/ghq/z/omf` `textlint: npm/textlint` を提供してる。

Makefile/Shellで書かれていて、curlでも入るようにしてる。

* [書き初めがてらdotfilesつくった](https://qiita.com/takeokunn/items/ab49759a2ce1bb10e120)

#### .emacs.d
url: [takeokunn/dotfiles](https://github.com/takeokunn/dotfiles)

emacs config。ガッツリ改造してる。

#### slack-bot
url: [takeokunn/slack-bot-sandbox](https://github.com/takeokunn/slack-bot-sandbox)

heroku + 社内slackで運用してる。

#### rails-docker-sample
url: [takeokunn/rails-docker-sample](https://github.com/takeokunn/rails-docker-sample)

railsをdocker化したサンプルコード。

#### laravel-docker-sample
url:[takeokunn/laravel-docker-sample](https://github.com/takeokunn/laravel-docker-sample)

laravelをdocker化したサンプルコード。CircleCI2.1を使っている。

#### cl-qiita
url: [takeokunn/cl-qiita](https://github.com/takeokunn/cl-qiita)

CommonLispでQiita API Clientのライブラリを作成。

#### businesh/linebot
url1: [takeokunn/businesh](https://github.com/takeokunn/businesh)

url2: [takeokunn/businesh-line-bot](https://github.com/takeokunn/businesh-line-bot)

ビジネッシュ翻訳ツール and line bot。npmで公開していて意外とダウンロード数が有る。

#### takengine
url: [takeokunn/takengine](https://github.com/takeokunn/takengine)

javascript製の関数型ゲームエンジン。PIXI.jsを使っている。

#### rails-console-repl.el
url: [takeokunn/rails-console-repl.el](https://github.com/takeokunn/rails-console-repl.el)

emacs replからrails consoleを叩けるようにしたplugin。

#### youtube_viewer
url: [takeokunn/youtube_viewer](https://github.com/takeokunn/youtube_viewer)

UUUM所属youtubeの動画を簡易的にみれるようにviewerを作った。

`electron/react/redux` あたりで作った。

* [Webの技術でYoutube Viewer作った](http://system.blog.uuum.jp/entry/2018/12/20/100000)

#### portfolio
url: [takeokunn/portfolio](https://github.com/takeokunn/portfolio)

自分のポートフォリオサイト。 `caveman2/bulma` で書いた。

* [ポートフォリオを作った](https://takeokunn.xyz/blog/post/create-portfolio-web)

#### bind9-docker
url: [takeokunn/bind9-docker](https://github.com/takeokunn/bind9-docker)

`bind9` を `docker` で動かした。

#### kintone-slack-notifier
url: [takeokunn/kintone-slack-notifier](https://github.com/takeokunn/kintone-slack-notifier)

kintone(日報)を特定の時間に生成 + google calendarから予定を取ってくるようにした。`nodejs` で作った。

#### king-of-time-driver
url: [takeokunn/king-of-time-driver](https://github.com/takeokunn/king-of-time-driver)

king of timeを自動で出退するプログラム。`nodejs/selenium`で作った。

#### emacs-php/php-mode
url: [emacs-php/php-mode](https://github.com/emacs-php/php-mode)

emacsのmajor pluginsの開発をした。

### やったこと

#### Blog

url: [https://takeokunn.xyz/](https://takeokunn.xyz/)

`infra as a code` を実践してterraformでAWSに構築した。`nginx/php-fpm` の最適化や負荷対策などもした。

`OctoberCMS` でホスティングしている。

#### Raspberry PI

Lチカ、温湿度センサー、webカメラの制御をすることができた。`python` で書いた。

#### CTF

url: https://ctf.cpaw.site/

cpaw ctfを一通り解いた。

#### Networking

Edge Router Xでネットワーク構築をやった。
