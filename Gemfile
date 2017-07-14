# frozen_string_literal: true

ruby '2.4.1'

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.1'

gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'bcrypt', '~> 3.1.11'
gem 'bootstrap-sass', '~> 3.3.7'
gem 'coffee-rails', '~> 4.2'
gem 'flux-rails-assets', '~> 2.1.0'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails', '~> 4.3.1'
gem 'react-rails', '~> 2.2.0'

group :production do
  gem 'pg', '~> 0.21.0'
end

group :development, :test do
  gem 'byebug', platforms: %i(mri mingw x64_mingw)
  gem 'capybara', '~> 2.13'
  gem 'pry'
  gem 'rails-controller-testing'
  gem 'rspec-rails', '~> 3.6.0'
  gem 'rubocop', '~> 0.49.1', require: false
  gem 'selenium-webdriver'
  gem 'sqlite3', '~> 1.3.13'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: %i(mingw mswin x64_mingw jruby)
