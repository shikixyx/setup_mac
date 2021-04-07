# setup_mac

## 手順

### terminal上でhomebrewとitermを入れる

* terminalにhomebrew入れる
  * [homebrew](https://brew.sh/)
* `brew install iterm2` でiterm2を入れる

### iterm2の設定

* 設定をインポート
* profile -> keys -> hotkeyを設定

### アプリやツールをインストール

* `brew bundle --global`
* prezto:https://github.com/sorin-ionescu/prezto
* fzfの設定:https://github.com/junegunn/fzf
  * https://qiita.com/kompiro/items/a09c0b44e7c741724c80
* enhancd:https://github.com/b4b4r07/enhancd
  * だけど、実際はpreztoを使えるので、https://github.com/belak/prezto-contrib ここから
  * 設定ファイルはhttps://github.com/sorin-ionescu/prezto/tree/master/runcoms　ここ

### VSCode

* プラグイン入れまくるだけ

### Finder

* 隠しファイルを表示させる

```sh
$ defaults write com.apple.finder AppleShowAllFiles TRUE
$ killall Finder
```

### その他のアプリ

* better touch tool

