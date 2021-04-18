# README

`docker-compose build`

`docker-compose run web bundle exec rails webpacker:install`

`docker-compose up`

### DB作成

`docker-compose run web rails db:create`

### コンテナログイン
`docker exec -it myapp_web_1 /bin/bash` 

### マイグレーション実行
コンテナログイン後 `rake db:migrate`