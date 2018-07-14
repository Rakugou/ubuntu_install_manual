# 設定(特に何も考えずにできるもの）
- bluetoothオーディオスピーカーの設定
- fcitxのスキンをdarkに設定する。
- usr/local/binの設定
  - adjust-brightness/run-adjust-brightnessの作成（Let's note設定時のみ）
    - dropboxに格納しておくこと

# アプリケーションのダウンロード
## ubuntuソフトウェアセンターからインストール

- $ sudo apt update
- $ sudo apt install mikutter gparted vlc vlc-videolan chromium-browser chromium-browser-l10n gimp gimp-ufraw shotwell ubuntu-restricted-extras sylpheed sylph-searcher r-base-core nautilus-dropbox wine asunder easytag geeqie calibre blueman xsane unetbootin pdf-shuffler keepassx handbrake synaptic git

※めんどくさいからコマンド一発で

## .debファイルをwebから
- Skype
- RStudio
- Tusk

## コマンドからダウンロード(ppa:)
virtualbox
Atom

# 各種アプリケーションの設定
## firefox
- firefox syncにログイン

## chromium
- googleアカウントでログイン
- アプリケーションからTodoistとLINEをlauncherに登録しておくこと。

## dropbox
ログイン

## keepassX
kdbxファイルを読み込ませる

## mikutter
- バックアップファイルからpluginフォルダごと.mikutterフォルダへ入れる
- ログイン→各種設定

## sylpheed
- メールアカウントの設定
- imapになっているので、インストール時に注意が必要、注意事項はkeepassのメモに記載したほうがいいかもね

##easytag
- v3.2のところの文字コードをUTF-8に修正（要確認）

##gedit
- バックアップフォルダにあるgedit-markdownをいくやさんのgihyoを見てやること

##skype
- ログイン

##R-studio
- パッケージのインストール
- install.packages("car","diagrammeR", "foreign", "Hmisc", "lavaan", "lme4", "MCMCpack", "memisc", "mnormt", "poLCA", "psych", "Rcmdr", "Rcpp", "RcpparmArmadillo", "RcppEigen", "Rmarkdown", "tidyverse")
- または、RStudioの設定から、入れるアプリケーションを考える。そうしよう。
- あと、清水・小杉(2014)参照のこと
    - これらはRstudio Serverに切り替えないと日本語が編集できないという不具合が起こるらしいので、少々検討しましょう。
    - サーバー建設も含めて要検討

