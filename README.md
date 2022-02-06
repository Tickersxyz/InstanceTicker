<hr>

# #InstanceTicker

<hr>

<img src="https://res.cloudinary.com/weep/it/InstanceTicker.png" title="#InstanceTicker" alt="#InstanceTicker" />

[![#InstanceTicker (Mastodon Custom CSS)](https://res.cloudinary.com/miy/p/InstanceTicker_Play.png)](https://www.youtube.com/watch?v=DbN5ytOnGSI)

<hr>

# 概要 - Description
<img src="https://miy.pw/tit.png" title="#InstanceTicker" alt="#InstanceTicker" />

- "#InstanceTicker" とは、Mastodon 上で、投稿者に所属インスタンス名を彩る "Custom CSS" を発行・配信したり、そのためのインスタンス情報を取りまとめています。

## なぜ ソース や API を公開しないんですか？ - When is the PHP source and API open?
- 個人的に欲しいものという出発点から突貫工事的に作ったので、現時点では難しいです。
- 将来的には配布できる形にしたものを準備する予定ではありますが、 miy.pw の運用が優先されます。
- - 2022年中にはソースをオープンします。
- 代替が登場した機に、#InstanceTicker API を廃止することになりましたので、以下をお使いいただけたらなぁと（丸投げ）。
- - 「[OpenSticker](https://github.com/cutls/OpenSticker)」 - 最強の代替です(2020/07/28)。
- - - 「[SubyayToorer](https://github.com/tateisu/SubwayTooter)」 - #InstanceTicker API 廃止にともない、[OpenSticker](https://github.com/cutls/OpenSticker)に移行(2020/09/30)。
- - 「[めいすきー](https://github.com/mei23/misskey)」 - Misskey のフォーク。本家より先行して代替機能（インスタンス情報として）が導入されました(2020/07/30)。
- - 「[Misskey](https://github.com/syuilo/misskey)」 - 本家。代替機能（インスタンス情報として）が導入されましたが、めいすきーとは同一機能名ながら仕様が全く異なります(2020/10/27)。
<hr>



# インスタンスリスト - instances.tsv

[InstanceTicker/InstanceTicker](https://github.com/InstanceTicker/InstanceTicker) 用のインスタンスリストです。

TSV で管理し、SQLite ( Table: instances ) に格納している感じです。

|  id  |  sns |  host  |  domain  |  text  |  width  |  tcolor  |  bcolor  |  scolor  |  bicon  |  sicon  |  eicon  |  iicon  |  url  |  entry  |  exity  |  icon  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|  id  |  SNS番号 |  ホスト  |  索引用ドメイン  |  表示名  |  画像の横幅  |  表示名色  |  背景色  |  表示名影色  |  画像背景色個別指定  |  同一画像をidで指定  |  eicon  |  画像のライセンス情報  |  Wiki等のリンク  |  エントリ日 |  非エントリ日  |  <s>画像（Webp の Data URI Scheme）</s>当リポジトリには含まれません  |

インスタンスリスト不定期更新な感じ。


## 謝辞 - Acknowledgements
- 当 CSS 作成・配信にあたり、きっかけとなり、基礎になったのは、「[小田急don](https://odakyu.app/about)」で使用されてる「カスタムCSS」であり、これがなければ、こんにちの「#InstanceTicker」は存在しえません。
- 「改造」から「CSS配信」「ユーザースクリプト」に快く了解してくださり、「GitHub での公開」を提案してくださいました「小田急don」の管理者 [きょり/わんせた](https://github.com/kyori19) さんには、この場を借りて感謝致します。
- 「kurage.cc」の管理者 [ぜま](https://github.com/yi0713) さんからは、通知表示時のCSSソース使用の提案と許可を快くしてくださり感謝しております。
<hr>

## ライセンス - Licence
- ©2018 weepjp / Based on the custom.css of ©2018 odakyu.app and ©2019 kurage.cc
- Released under the MIT license.
