# 説明

このウェブサイトは [Jekyll](http://jekyllrb-ja.github.io/) というRubyベースのウェブサイト構築システムを使っています。
また、このサイトは [Github Pages](https://help.github.com/ja/github/working-with-github-pages) というホスティングサービスで運用されています。
Github Pagesでは、Jekyllを動かすことができます。

利点は２つです。
無料であること、GitHubから直接編集・公開できること。
また、GitHubでは共同作業とバージョン管理できるので、この方法を使っています。

# 編集方法

1. GitHubのサイトからファイルを直接編集することもできます。
2. Gitを使える人はローカルで編集して、jekyllコマンドで確認できます。

## 文章・内容の編集作業

編集するべきファイルは２個です。

- `_config.yml` (設定ファイル)
- `index.md` (マークダウン)

参加登録(Google Form)のURLは `_config.yml` から編集してください。

ウェブサイトの本文は `index.md` にあります。
マークダウン形式のテキストですが、HTMLタグも使えます。

## それ以外の編集

`_config.yml` にあるとおり、基本となるHTML/CSSは `minima` というテンプレートを使っています。

このrepositoryにファイルを追加すれば、minimaのファイルを上書きできます。基本的に、上書きでCSSやHTMLを書き換えます。

もしCSSを変更したくなったら、 `_sass/custom.scss` に追記してください。

それ以外のHTML部品は `_includes/` にあります。
