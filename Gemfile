# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

gem 'haml-rails', '~> 2.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.3'
gem 'sassc'
gem 'uglifier', '>= 1.3.0'

gem 'annotate'
gem 'coffee-rails', '~> 4.2'
gem 'pry'
gem 'rubocop'

gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'spring'
  gem 'web-console', '>= 3.3.0'
end
