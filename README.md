# MyShogiImages

## 概要

MyShogi (https://github.com/yaneurao/MyShogi) に追加して使用できる画像集です。

GitHub - jnory/MyShogiImages (https://github.com/jnory/MyShogiImages) に含まれない画像を追加することができます。

## インストール手順

(1) 作業用ディレクトリに移動し、画像データを取得します。

    $ cd <作業用ディレクトリ>
    $ git clone https://github.com/tsugibayashi/MyShogiImages.git images

(2) ./images/ に移動し、MyShogiで使用したい画像データをコピーします。

    $ cd images/
    $ cp -pv <ファイル名>.png <MyShogiのインストール先>/image/
    $ cp -pv game_effect/<ファイル名>.png <MyShogiのインストール先>/image/game_effect/
    $ cp -pv setting_dialog/<ファイル名>.png <MyShogiのインストール先>/image/setting_dialog/

## 注意事項

下記画像ファイルは、[GitHub - jnory/MyShogiImages](https://github.com/jnory/MyShogiImages) にも存在します。
本レポジトリのファイル、または、[GitHub - jnory/MyShogiImages](https://github.com/jnory/MyShogiImages) の
どちらかの画像しか使用することができません。

| ファイル名 | 説明 |
----|----
| tatami_v1_1920_1080.png  | 背景画像1 |
| turn_v1_1057_157.png | 手番を表す画像(大) |
| turn_v1_106_43.png | 手番を表す画像(小) |

## ライセンス

[cc0-1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.ja)

## 画像中のフォント

* [IPAゴシック](https://moji.or.jp/ipafont/)。ライセンスは、https://moji.or.jp/ipafont/license に記載されています。

## 参考資料

この画像を作成するに当たり、以下のWebサイトを参考にしました。

* [GitHub - jnory/MyShogiImages](https://github.com/jnory/MyShogiImages)
* [『将棋神やねうら王』のオープンソース版MyShogiをLinux Mint 19.1でビルドしてみた件](http://hennohito.cocolog-nifty.com/blog/2019/03/post-3ed3.html)
* [『将棋神やねうら王』のアップデート手順をわかりやすく](http://yaneuraou.yaneu.com/2018/09/09/%E3%80%8E%E5%B0%86%E6%A3%8B%E7%A5%9E%E3%82%84%E3%81%AD%E3%81%86%E3%82%89%E7%8E%8B%E3%80%8F%E3%81%AE%E3%82%A2%E3%83%83%E3%83%97%E3%83%87%E3%83%BC%E3%83%88%E6%89%8B%E9%A0%86%E3%82%92%E3%82%8F%E3%81%8B/)
* [『将棋神やねうら王』Update3までの遊戯施設その2](http://yaneuraou.yaneu.com/2020/02/06/%e3%80%8e%e5%b0%86%e6%a3%8b%e7%a5%9e%e3%82%84%e3%81%ad%e3%81%86%e3%82%89%e7%8e%8b%e3%80%8fupdate3%e3%81%be%e3%81%a7%e3%81%ae%e9%81%8a%e6%88%af%e6%96%bd%e8%a8%ad%e3%81%9d%e3%81%ae2/)

以上
