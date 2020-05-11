# Ruby on Rails チュートリアルのサンプルアプリケーション

## ライセンス

MITライセンスとBeerwareライセンスのもとで公開されています。
詳細はLICENSE.mdをご覧ください。

## 使い方

レポジトリのクローンとRubyGemsのインストール
及び、DBの初期マイグレーション

```
$ bundle install --without production
$ rails db:migrate
```

テストの実行

```
$ rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
```

