# POTI-board用テンプレートPINK (改二専用）

## 2020年に始動したPOTI-board改二用 のテンプレートです。

**POTI-board改用はこちら(https://github.com/satopian/pink)**

**POTI-board改とPOTI-board改二のテンプレートは互換性がありません。**

**間違えると掲示板が動作しなくなります**ので注意が必要です。

今後のスクリプトの保守は、改二に移行する予定です。
新規設置を検討されている方は、より高速に動作する[POTI-board改二](https://github.com/sakots/poti-kaini)の利用をご検討ください。

### 設置サンプル

[POTI-board用テンプレート PINK 設置サンプル](https://pbbs.sakura.ne.jp/cgi/neosample/poti/)

### 特徴

[お絵かき掲示板](https://pbbs.sakura.ne.jp/)交流サイトで使っているテンプレートを一般配布用にカスタマイズしたものです。

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

の場合。

![Screen-2020-05-19_22-36-50](https://user-images.githubusercontent.com/44894014/82336088-1e3cf400-9a25-11ea-8ff6-8a071209e13f.png)

↑
ダウンロードしたpotiboard2フォルダに、pinkという新しいフォルダを追加します。

![Screen-2020-05-19_22-38-02](https://user-images.githubusercontent.com/44894014/82336104-22691180-9a25-11ea-939c-543567e6b657.png)

↑
その中にここからダウンロードしたファイルまとめます。


> define('SKIN_DIR', 'pink/');

で、テンプレートのディレクトリは

>'pink/'

と指定したので、そのディレクトリのテンプレートが適用されます。

掲示板が表示されたら設置完了です。

このテンプレートを使う前に、掲示板が動作することを確認することをおすすめします。
細かく設定してから動かそうと思ったら動かなかった…事が多いようです。
