# Homebrewインストール方法
# $ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

#-------------------------------------------------------------------------------
# 前処理
#-------------------------------------------------------------------------------

#今入っているbrewをupdateしてupgrade
update
upgrade

# homebrew-caskのインストール
tap phinze/homebrew-cask || true
install brew-cask
tap homebrew/binary || true

#-------------------------------------------------------------------------------
# 最低限必要なツール(homebrew)
#-------------------------------------------------------------------------------
install nkf || true
install mobile-shell || true
install htop-osx || true
install awscli || true
install zsh || treu

# 参考URL
# https://github.com/phinze/homebrew-cask/tree/master/Casks
# dmgでのインストール

#-------------------------------------------------------------------------------
# 最低限必要なアプリ(cask)
#-------------------------------------------------------------------------------
cask install google-chrome || true
cask install iterm2 || true
cask install alfred || true
cask alfred link || true #Alfredで~/Applicationsのパスを検索するようにする
cask install appcleaner || true
cask install java || true #Java JDK

# ディスク容量があれば入れたいアプリ

#-------------------------------------------------------------------------------
# 仮想関連(Virtual Machine)
#-------------------------------------------------------------------------------
cask install vagrant || true #vagnrat
cask install virtualbox || true #バーチャルボックス
install docker || true #docker
install boot2docker || true #Mac向けdocker用OSイメージ
install packer || true #packer
install terraform || true #terraform

#-------------------------------------------------------------------------------
# アプリケーション
#-------------------------------------------------------------------------------
cask install adobe-creative-cloud || true # Adobe Creative Cloud
cask install mailplane || true # Mailplane (メーラー)
#cask install bitcasa || true # Bitcasa(インターネットドライブ)
cask install dropbox || true # Dropbox(インターネットドライブ)
cask install google-drive || true # Google Drive(インターネットドライブ)

# Mac ユーティリティ(Utility)
cask install clipmenu || true
cask install bartender || true
cask install karabiner || true
cask install totalterminal || treu
#cask install totalfinder || treu
cask install totalspaces || treu
cask install flux || treu #画面光度変更ソフト
install mobile-shell || treu #mosh(MITが作ったSSH代用品)

# 開発関連
cask install sequel-pro || true # MySQL GUI Client
cask install mongohub || true # MongoDB GUI Client
cask install pg-commander || true #PostgreSQL GUI Client ただし有料、無償版もある
cask install sqlitebrowser || SQLite GUI Client
install jq || true #JSON の内容をフィルタ/加工するためのプログラム
install tig || true #git logのビューワー
cask install sourcetree || true # Git GUI Client SourceTree

# エディタ
#cask install sublime-text || true # Sublime Text(エディタ)
cask install atom || true # atom(A hackable text editor for the 21st Century) GitHubが作ったエディタ
#cask install kobito || true # プログラミングのメモやスニペットの記録に最適なMacアプリ
#cask install emacs || true #GUI版emacs
install emacs || true #Terminal版emacs
cask install evernote || true #Evernote
cask install skitch || true #skitch

# go関連
#install hg || true #go-autocompleteのインストール時に必要
install go || true #go-lang本体

# peco関連
tap peco/peco || true
install peco

# コミュニケーションツール
cask install skype || true # Skype(コミュニケーションツール)
cask install sqwiggle || true # Sqwiggle(コミュニケーションツール)
#cask install hipchat || true # HipChat(コミュニケーションツール)


# TeX関連
# http://uenohara.hatenablog.jp/entry/2014/02/02/224140
# http://osksn2.hep.sci.osaka-u.ac.jp/~taku/osx/install_ptex.html
# http://macwiki.sourceforge.jp/wiki/index.php/TeXShopヘルプ（1-12）画像を入れる
#install ghostscript
cask install mactex
#cask install texshop

#-------------------------------------------------------------------------------
# 後処理
#-------------------------------------------------------------------------------
# 残ったゴミ関係を綺麗にする
cleanup
