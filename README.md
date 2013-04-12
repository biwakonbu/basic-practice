基礎演習手順書
==============

統合開発環境と Git による Web ページ開発
----------------------------------------

HTML の書き方
現在 HTML 5 という規格が策定されている最中で,
主要な Web ブラウザはそれに対応しているものが殆どであるため HTML 5 を前提に演習を行う.

### HTML5
先ず、HTML 5 のテンプレートについて触れる.

> ### 演習 1. HTML5 のテンプレートから HTML ファイルを作成表示の確認を行う.
> [HTML5 テンプレート](template/html5.html "test")

HTML 5 では、ファイルの先頭の記述が
``
<!DOCTYPE html>
``
に変わっている事に注意する事.
また、使用する文字のエンコーディングの指定は
``
<meta charset="utf-8" />
``
に変更されている事にも注意する.

> ### 演習 2. CSS の初期化を行う
> 演習 1 のファイルの ``<head></head>`` 内に ``<link rel="stylesheet" href="initialize.css">`` を記述する.
>
> [CSS 初期化ファイル](template/initialize.css)

``<link>`` タグでは外部ファイルから CSS を読み込む事が出来る.
CSS は, ブラウザ毎に仕様と設定が異なる為, 予期しない動作を引き起こす事
がある. その為, あらかじめ設定を初期化して置く事で予期しないレイアウト
になる事を防ぐ事が出来る.



[Twitter Bootstrap](http://twitter.github.io/bootstrap/index.html)
