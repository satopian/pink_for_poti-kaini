# POTI-board用テンプレートPINK (改二専用）

### 2020年に始動したPOTI-board改二用 のテンプレートです。

**POTI-board改用はこちら(https://github.com/satopian/pink)**

見た目や機能は同じですが、内部のテンプレートエンジンがskinnyに変更されたため互換性がありません。
POTI-board改とPOTI-board改二で使用するテンプレートが違います。
**間違えると掲示板が動作しなくなります**のでよろしくお願いいたします。

### 設置サンプル

[POTI-board用テンプレート PINK 設置サンプル](https://pbbs.sakura.ne.jp/cgi/neosample/poti/)

### 特徴
[お絵かき掲示板](https://pbbs.sakura.ne.jp/)交流サイトで使っているテンプレートを一般配布用にカスタマイズしました。

[POTI-board用テンプレート PINK を配布します。: STP^3](http://stp.sblo.jp/article/182310034.html)

BBSNoteのようなレイアウト。

スマートフォン・タブレットに対応したレスポンシブデザイン。

新規投稿、レス送信モードからの画像アップロードができないようにしてあります。
画像アップロード掲示板ではなくお絵かき掲示板として使うためです。
管理人投稿からの画像アップロードには対応しています。

## このテンプレートを使うために必要なもの

お絵かき掲示板のスクリプト本体、[POTI-board改二](https://github.com/sakots/poti-kaini)をダウンロードします。

## このテンプレートのダウンロード 

**緑色の「Clone or download」ボタンを押下してpink-master.zipを入手します。**

## 設置方法

> //スキンのディレクトリ。'/'まで
> //skinディレクトリに使いたいtemplateをいれて使ってください。(推奨)
> //別のディレクトリにしたい場合は設定してください。
> //例えばおまけのnee2を使いたい場合はskin_nee2/とすることができます。初期値は skin/ です。
> define('SKIN_DIR', 'skin/');
>

config.phpを編集します。

例えば

> define('SKIN_DIR', 'pink/');
>//最後に / が必要

