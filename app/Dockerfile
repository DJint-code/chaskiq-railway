FROM chaskiq/chaskiq:latest
CMD bundle exec rails db:setup; bundle exec rails db:migrate; bundle exec rails packages:update; bundle exec rails s -b  :: -p 3000