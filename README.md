# Rails Tutorial


## コンセプト

Ruby on Rails を30代のおじさんが勉強する。

### おじさんの能力

* サーバサイド開発たくさんやった
* Rubyぜんぜんわかんない
* HTML(5)なんとなくわかる
* JavaScriptけっこうできるつもり
* HTTP/RESTしってる
* gitはぼっちで使う分には十分、少人数でもまぁなんとか
* 体力ない、あきっぽい

### おじさんの環境

#### Mac Book Air 13"

* OS X 10.9.3 (Mavericks)
* CPU : 1.7 GHz Intel Core i7
* HDD : 128GB
* RAM : 8GB


#### Version

``` shell
$ ruby -v
ruby 2.1.2p95 (2014-05-08 revision 45877) [x86_64-darwin13.0]
$ rails -v
Rails 4.1.1
```

Rails TutorialのGemfileは学習時点で`ruby '2.0.0'`
`gem 'rails', '4.0.5'`となっているので、ややTutorialのほうがバージョンが古い。



## 目標

* herokuでなんかサービスをオープンする
* gitを中心としたデザイナとのワークフローを（擬似）体験できるようになる
* railsエンジニャーを名乗れるようになる

### ルール

* 勉強したところの章番号をコミットメッセージにいれる
* やりたいこととかわかんないことは[ISSUE](https://github.com/shoota/rails-tutorial/issues)にかく
* ~~基本的にブランチは切らない（チュートリアルらしく一本道で、デザイン用のトピックブランチとかは有）~~
* tutorialでブランチを切る作業があるのでbranchもそれにならう 
