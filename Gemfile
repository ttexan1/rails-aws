source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.2.2'
gem 'pg', '~> 1.3.6'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'
gem 'therubyracer', platforms: :ruby
gem 'bootstrap-sass'
gem 'simple_form'
gem 'html5_validators'
gem 'kaminari'
gem 'seed-fu', '~> 2.3'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'slim-rails'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'annotate'
  gem 'pry-rails'
  gem 'pry-coolline'
  gem 'pry-byebug'
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'html2slim'
  gem 'rspec-rails'
  gem 'spring-commands-rspec'
  gem 'guard-rspec'
  gem 'rb-fsevent'
  gem 'factory_bot_rails'
  gem 'database_rewinder'
  gem 'timecop'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'bullet'
  gem 'html2slim'
end

group :test do
  gem 'shoulda-matchers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
