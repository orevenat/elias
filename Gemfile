# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem 'rack'

gem 'dotenv'

gem 'pg'
gem 'sequel'

group :development do
  gem 'pry-byebug'
end

group :test do
  gem 'rack-test'
  gem 'rspec'
  gem 'simplecov', require: false
end
