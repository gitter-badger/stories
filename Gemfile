source 'https://rubygems.org'
ruby "2.3.0"

gem 'rails', '4.2.5'
gem 'puma', '~> 2.15'
gem 'pg'
gem 'devise', '~> 3.5.3'
gem 'omniauth-facebook', '~> 3.0'
gem 'omniauth-twitter', '~> 1.2'
gem 'omniauth-google-oauth2', '~> 0.3.1'
gem 'react-rails', '~> 1.6'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'jquery-rails'
gem 'jquery-ui-rails', '~> 5.0'
gem 'jbuilder', '~> 2.0'

gem 'carrierwave', '0.10.0'
gem 'mini_magick', '3.8.0'
gem 'fog',  '1.23.0'
gem 'net-ssh'
gem 'sdoc', '~> 0.4.0', group: :doc

# Load will_paginate before elasticsearch gems.
gem 'will_paginate', '~> 3.1'

# Elasticsearch
gem 'elasticsearch-model', '~> 0.1.8'
gem 'elasticsearch-rails', '~> 0.1.8'

# Background Job
gem 'sidekiq', '~> 4.0'
gem 'sinatra', require: false
gem 'slim'
gem 'sidetiq', '~> 0.7.0'

gem 'nokogiri', '~> 1.6'


# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '~> 3.4.0'
  gem 'poltergeist', '~> 1.8'
  gem 'awesome_print', '~> 1.6'
end

group :development do
  gem 'rails_best_practices', '~> 1.15'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'guard-rspec', require: false
  gem 'spring-commands-rspec', '~> 1.0'
  # Profiling
  # gem 'rack-mini-profiler', '~> 0.9.8', require: false
end

group :test do
  gem 'database_cleaner', '~> 1.5.1'
  gem 'capybara', '~> 2.5.0'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'faker', '~> 1.6.1'
  gem 'launchy', '~> 2.4.3'
  gem 'selenium-webdriver', '~> 2.48.1'
end

group :production do
  gem 'rails_12factor', '0.0.2'
  gem 'bonsai-elasticsearch-rails'
end

