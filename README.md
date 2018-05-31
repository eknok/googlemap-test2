# README

# 概要
google-mapをrailsAPP内で表示させるテスト  
なお、下記の参考URLを参考に書いているので悪しからず  

## 参考
- [Railsで住所からGoogleMapを表示する。しかも5分で。](https://qiita.com/master-of-sugar/items/e71cbf659c6bd0fe948e)  

※今回はこれ(geocoderなし)
- [RailsでGoogleMapを表示させる(gem 'gmaps4rails'の使い方)](https://qiita.com/nakanoyoshiki/items/af9f37e9d2653518d6b0)  

## まとめ
1. `gem gmap4rails`を使う場合はDBに住所、緯度経度が入っている場合でgoogle-mapを表示させる場合か
2. `gem geocoder`のみを使う場合、`gem gmap4rails`は必要ないと思う..?(jsでAPIを取得していれば..)
2の`gem geocoder`のみのサンプル`googlemap-test3`を作成する
