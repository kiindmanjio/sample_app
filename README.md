# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
[Michael Hartl](http://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にある
ソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。
詳細は [LICENSE.md](LICENSE.md) をご覧ください。

##使い方

①：このアプリを動かすための第一歩として、まずは、リポジトリを手元にクローンしてください。
②：次のコマンドで、必要になるRubyGemsをインストールします。

```
$ bundle install --without production
```

③：データベースのマイグレーションをします。

```
$ rails db:migrate
```

④：最後にテストを実行してうまく動いているかどうかを確認してください。

```
$ rails test
```

⑤：Rails サーバーを立ち上げましょう。

```
$ rails s
```


詳しくは、[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
を参考にしてください。

