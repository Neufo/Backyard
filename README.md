# Backyard
Ruby on Rails の学習用に作成したアプリケーションです。

## アプリケーションの実行方法
Backyardディレクトリ直下で以下のコマンドを実行します

### MacOS
1. `bundle install`
1. `bin/rails db:migrate`
1. `bin/rails s`

### Ubuntu
1. `sudo apt install libsqlite3-dev nodejs`
1. `rbenv local 2.5.1`
1. `gem install bundler -v 1.17.3`
1. `bundle install`
1. `rbenv rehash`
1. `rails s`

## 動作環境
* Ruby version 2.5.1p57
* Ruby on Rails version 5.2.1
* Bundler version 1.17.3
* Node.js version 13.0.1
