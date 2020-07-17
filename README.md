# POTI-board用テーマPINK 改二

**[POTI-board改二](https://github.com/sakots/poti-kaini)用のテンプレートです。**

**「POTI-board改」と「POTI-board改二」のテンプレートは互換性がありません。**

間違えると掲示板が動作しなくなりますのでご注意ください。

POTI-boardは改のサポートを終了し改二に移行しました。
新規設置を検討されている方は、より高速に動作する[POTI-board改二](https://github.com/sakots/poti-kaini)の利用をご検討ください。

## サポート

[POTI改公式サイト](https://poti-k.info/)に設置サポート掲示板で対応します。
GitHubの[Issues](https://github.com/satopian/pink_for_pot-kaini/issues)でも対応できると思います。

### 設置サンプル

[POTI-board用テーマ PINK 設置サンプル](https://pbbs.sakura.ne.jp/cgi/neosample/poti/)

### 特徴

[お絵かき掲示板](https://pbbs.sakura.ne.jp/)交流サイトで使っているテンプレートを一般配布用にカスタマイズしたものです。

[POTI-board用テーマ PINK を配布します。: STP^3](http://stp.sblo.jp/article/182310034.html)

BBSNoteのようなレイアウト。

スマートフォン・タブレットに対応したレスポンシブデザイン。

新規投稿、レス送信モードからの画像アップロードができないようにしてあります。
画像アップロード掲示板ではなくお絵かき掲示板として使うためです。
管理人投稿からの画像アップロードには対応しています。

## このテーマを使うために必要なもの

お絵かき掲示板のスクリプト本体、[POTI-board改二](https://github.com/sakots/poti-kaini)をダウンロードします。

## このテーマのダウンロード 

**緑色の「Code」ボタンを押下してpink_for_pot-kaini-master.zipを入手します。**

## テーマを入れ替える前に ##

テーマを入れ替える前に、掲示板が問題なく動作することを確認します。

## サーバへの転送

> //テーマ(テンプレート)のディレクトリ。'/'まで  
> //themeディレクトリに使いたいtemplateをいれて使ってください。(推奨)  
> //別のディレクトリにしたい場合は設定してください。  
> //例えばおまけのnee2を使いたい場合はtheme_nee2/とすることができます。初期値は theme/ です。  

config.phpを編集します。

例えば

> define('SKIN_DIR', 'pink/');

の場合。

![Screen-2020-05-27_15-35-53](https://user-images.githubusercontent.com/44894014/83000244-0ed13280-a045-11ea-92f1-37c6d6238a72.png)

↑
ダウンロードしたpotiboard2フォルダに、ダウンロードしたpinkフォルダを追加します。


![Screen-2020-05-27_18-09-37](https://user-images.githubusercontent.com/44894014/83000458-5c4d9f80-a045-11ea-8a31-94ce1f2df273.png)

↑
その中に入っているファイル。


> define('SKIN_DIR', 'pink/');

と設定したので、 pink/ ディレクトリのテーマが適用されます。

**pinkディレクトリを転送します。**

掲示板が表示されたら設置完了です。

テーマを変更しても表示が変わらない時は、管理画面からログ更新するかなんでもいいので書き込みます。

### 履歴

#### [2020/05/16] PINK lot.200516

POTI-board改二 v2.7.6に対応。名前からのリンクは作者のイラスト一覧になりました。

