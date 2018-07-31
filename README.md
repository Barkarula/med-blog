This is the repository of the Alpha Blog app of the Rails JavaScript Development course.

- This was built using Ruby on Rails

//
gem install bundler
bundle install

bundle exec rails db:migrate
// Проблема с gem bcrypt? Поставь необходимый удалив сущ-ий

bundle exec rails server
bundle exec rails webpacker:install

bundle exec rails webpacker:install:react

<%= javascript_pack_tag 'application' %>

bundle exec rails generate react:install

rails g react:component HelloWorld greeting:string

// git diff


