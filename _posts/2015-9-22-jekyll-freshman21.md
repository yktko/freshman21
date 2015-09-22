---
layout: post
title: ブログスタイルの変更
category: code
---

ブログをJekyllで作り、スタイルを変えて体裁を直してみた。構造がだいたいわかってきた。

参考にした情報をリストアップしておく。

* テーマ「freshman21」
  * <https://github.com/yulijia/freshman21/>

* Freshman21のデモサイト
  * <http://yulijia.net/freshman21/>

* SNSのシェアボタンの設置方法まとめ
  * <https://syncer.jp/how-to-setting-share-button>

* Font-Awesome（簡単に使えるアイコンセット）
  * <http://fortawesome.github.io/Font-Awesome/>

* Jekyll関係
  結局Jekyllは手元のMacにインストールして、ローカルで動作確認を行い、GitHubにpushしている。
  * 導入 <http://jekyllrb.com/docs/installation/>
  * テストのやりかた→`jekyll serve`でローカルで環境を立ち上げ、`http://127.0.0.1:4000/`にアクセスする
  * 変数 <https://jekyllrb.com/docs/variables/>
  * excerpt(抜粋)一覧表示の時は最初のセンテンスだけ表示するようにした<https://jekyllrb.com/docs/posts/>
  * markdownの書き方あれこれ<http://milanaryal.com/2015/writing-on-github-pages-and-jekyll-using-markdown/>
  * permalinkの修正`_config.yml`にpermalinkを設定すればよい<https://jekyllrb.com/docs/permalinks/>

* Favicon Generator (Favicon作成)
  * <http://www.favicon-generator.org/>

* ローカルにcloneしたリポジトリをgithubに上げる
  * [【githubエラー】fatal: remote origin already exists.の対処](http://d.hatena.ne.jp/iwahei0813/20140324/1395652080)

これ以外では各種CSSのサイトとChromeのDevelopperモード。iPhoneのviewport設定とか。
