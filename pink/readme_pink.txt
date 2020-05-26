━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

           POTI-board用テンプレート「PINK」
                 by さとぴあ ( http://stp.sblo.jp )

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ぷにゅねっと http://www.punyu.net/php/
のPOTI-boardをphp7で使えるように改造した

POTI-board改二 v2.2.7
https://poti-k.info/

以降に対応したテンプレートです。

MONO WHITEと、Cool Solid ( 黒鋼彗牙さん作・ https://draclaw.com )をベースにして、カスタマイズしました。
かなりの部分をCool Solidに依存しているため、テンプレートの著作権表記はCool Solid & PINKです。

画像アップロード掲示板ではなくお絵かき掲示板、というコンセプトで作成したテンプレートです。

■無保証

問題なく動作することを期待して作成していますが、このテンプレートを使った事により何らかの問題が起きたとしても、私は責任を負いません。

サーバその他の条件によっては期待通りの動作をしないかもしれません。
動作するかどうかはご自身で確認していただく必要があります。

■アップロード

POTI改公式サイト https://poti-k.info/

から、POTI-board改二をダウンロードし、設置ディレクトリにアップロードします。

このテンプレートの以下のファイルをpinkというディレクトリにまとめてアップロードします。

pink_main.html
pink_other.html
pink_paint.html
pink_res.html
pink_catalog.html
pink.css
pink_ie.css
palette.txt
siihelp.php
template_ini.php

icomoon フォルダとその中身も同じディレクトリにアップロードします。
TwitterとFacebookのアイコンが入っています。

config.phpの

> //スキンのディレクトリ。'/'まで
> //skinディレクトリに使いたいtemplateをいれて使ってください。(推奨)
> //別のディレクトリにしたい場合は設定してください。
> //例えばおまけのnee2を使いたい場合はskin_nee2/とすることができます。初期値は skin/ です。
> define('SKIN_DIR', 'skin/');
>

の箇所を編集します。

pinkというディレクトリにファイル一式をまとめたので

> define('SKIN_DIR', 'pink/');

と設定します。

テンプレートを入れ替えたのに表示が変わらない時は、管理画面からログ更新するか何か書き込みます。

■著作権表示

「MONO WHITE」に準じるものとします。
