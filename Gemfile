source 'https://rubygems.org'

ruby '2.3.3'

gem 'activerecord', '~> 5.2.4'

gem 'bugsnag', '~> 5.3'
gem 'faraday'
gem 'flipper', '0.10.2' # locked due to monkey patch
gem 'flipper-active_record'
gem 'flipper-ui'
gem 'loofah'
gem 'petroglyph'
gem 'pg'
gem 'pry', require: false
gem 'puma', '~> 4.3.12'
gem 'rack-flash3', require: 'rack-flash'
gem 'rake', '~> 12.3.3'
gem 'redcarpet', '~> 3.5'
gem 'rouge', '~> 2.1.0'
gem 'sinatra', '~> 2.0.0', require: 'sinatra/base'
gem 'sinatra-contrib', '~> 2.0.0'
gem 'sidekiq', '~> 5.2.0'
gem 'trackler', '~> 2.2.0'
gem 'will_paginate'
gem 'will_paginate-bootstrap'

# GitHub API
gem 'octokit'

# Frontend Gems
gem 'sass'
gem 'compass'
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'kss'
gem 'octicons'

group :test, :development do
  gem 'approvals', require: false
  gem 'coveralls', require: false
  gem 'database_cleaner', require: false
  gem 'dotenv', require: false
  gem 'foreman', require: false
  gem 'mocha', require: false
  gem 'rack-test', require: false
  gem 'simplecov', require: false
  gem 'sqlite3'
  gem 'timecop', require: false
  gem 'rb-readline'
end

group :development do
  gem 'rerun', require: false
  gem 'rubocop', '0.48.1', require: false
end

group :test do
  gem 'launchy'
  gem 'minitest-capybara'
end
