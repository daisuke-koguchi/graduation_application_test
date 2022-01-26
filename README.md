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
<img width="899" alt="ER図 2022-01-26 10 09 17" src="https://user-images.githubusercontent.com/91811989/151089109-a18cedab-7e3b-4d55-a44f-0fe4d69850f2.png">　　

# 画面遷移図
<img width="1039" alt="画面遷移図 2022-01-26 10 04 34" src="https://user-images.githubusercontent.com/91811989/151090923-7026935a-e5f1-4b7f-a430-264ab60434ac.png">　　

# ワイヤーフレーム
https://cacoo.com/diagrams/On25kO05XOD65gBi/97560

