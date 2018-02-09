# 5374について

5374(ゴミナシ)はもともと  [Code for Kanazawa](http://codeforkanazawa.org/) が開発したものです。
このリポジトリは Code for Kanazawa が開発した [5374](https://github.com/codeforkanazawa-org/5374) をフォークして神奈川県横須賀市向けに作り直したものです。

For English please see [LOCALIZE_en.md](LOCALIZE_en.md).

## 「いつ、どのゴミが収集されているのか？」

ゴミの問題はどの地域でも深刻になりつつあります。
 [Code for Kanazawa](http://codeforkanazawa.org/)
では、先ずは正しいゴミの捨て方に注目しました。例えばお引っ越しをされた場合、このアプリを使えばすぐに分かるように、目的と使い方をとてもシンプルにデザインしました。

## 使い方

[5374 for Kanazawa](http://kanazawa.5374.jp/ )について説明します。

* **色でゴミのジャンルを表示**: 一番近いゴミの日とジャンルを上から順に表示しています。

* **捨てる事が可能なゴミ**: ゴミのジャンルをタップすると、捨てることが可能なゴミの一覧を見ることができます。

* **設定**: お住まいの地域を選択することで、ゴミ収集日が自動的に更新されます。今後スマートフォンのGPSから位置情報を取得する機能を追加する予定です。


## ローカルでの表示方法について

ローカルでの確認される場合は、サーバーを立てたほうが簡単です。

いろいろ方法がありますが、クローンしてきたパスで下を実行するのが一番手軽です。
（PHPが入っていなければ入れてください。もちろんこれ以外の方法でも大丈夫です）

```
php -S 127.0.0.1:10000 -t .
```
その後、Webブラウザで

```
http://localhost:10000/
```
をアクセスしてください。

## 提供されるゴミ情報について
横須賀市が公開している [分別パンフレット「ごみと資源物の分け方・出し方」](https://www.city.yokosuka.kanagawa.jp/4220/kurashi/bunbetsupanfu.html) の内容をもとにしています。

## Code for Yokosuka 開発メンバー
- 鈴木 広之 (Hiroyuki Suzuki) Developer ([@mowarte](https://github.com/mowarte))

## ライセンス

本アプリ及びソースコードの著作権はCode for Kanazawaに帰属します。
但し、このソースコードは[MPL](http://www.mozilla.org/MPL/2.0/)のもと配布されています。MPLに従えば、どなたでも利用、改変、及び再配布が可能です。
