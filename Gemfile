source 'https://rubygems.org'

gem 'rails', '4.1.16'
gem 'protected_attributes' # for 4.x

gem 'rake'
gem 'rack'
gem 'gravatar_image_tag'
gem 'will_paginate'
gem 'sass'
gem 'coffee-script'
gem 'uglifier'
gem 'jquery-rails'
gem 'nokogiri'
gem 'json'
gem 'holepicker'
gem 'overcommit'

group :development do
  gem 'annotate'
  gem 'faker'

  # See Railscast #402 for more info.
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'dawnscanner', require: false
end

group :development, :test do
  gem 'sqlite3', '1.3.13' # 2/6/2019: LOCKED DOWN
  gem 'rspec-rails', '2.99.0'
  gem 'rubocop-rspec'
end

group :test do
  gem 'spork-rails'
  gem 'factory_bot_rails'

  gem 'webrat'
  gem 'capybara'

  # Pretty printed test output
  gem 'turn', require: false
end

group :production do
  gem 'pg'
end
