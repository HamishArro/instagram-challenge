# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'rails'
gem 'pg'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'devise'
gem 'jbuilder'

group :development, :test do
  gem 'capybara'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
end

group :development do
  gem 'listen'
  gem 'web-console'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
