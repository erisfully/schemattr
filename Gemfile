# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gemspec

gem "rubocop", ">= 1.25.1", require: false
gem "rubocop-minitest", require: false
gem "rubocop-packaging", require: false
gem "rubocop-performance", require: false
gem "rubocop-rails", require: false

group :test do
  gem "rspec"
  gem "simplecov"
  gem "sqlite3"
end
