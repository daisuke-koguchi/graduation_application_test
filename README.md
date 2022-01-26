# README

# 開発言語
・Ruby 3.0.3  
・Ruby on Rails 6.1.4  

# 就業Termの技術
・devise  
・メッセージ機能  

# カリキュラム外の技術
・chartckick  
・Docker  

# 実行手順
```
$ git clone git@github.com:daisuke-koguchi/graduation_application.git  
$ cd graduation_application
$ docker compose run web bundle install
$ docker compose run web rails db:create 
$ docker compose up 
```
別のターミナルを起動させ、下記のコマンドを入力
```
$ docker compose run web rails db:migrate
$ docker compose run web rails s 
```
# カタログ設計
https://docs.google.com/spreadsheets/d/1E4ScgbXNM1YYXmu8P1FYFfJ0YoqzJa_mrLY0KA9NrXo/edit#gid=1207518212

# テーブル定義書
https://docs.google.com/spreadsheets/d/1E4ScgbXNM1YYXmu8P1FYFfJ0YoqzJa_mrLY0KA9NrXo/edit#gid=950377125

# ER図

# 画面遷移図

# ワイヤーフレーム
https://cacoo.com/diagrams/On25kO05XOD65gBi/97560

