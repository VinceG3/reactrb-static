source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

hyperstack_version = '= 1.0.alpha1.4'

gem 'rails', '~> 5.2.2', '>= 5.2.2.1'
gem 'puma', '~> 3.11'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'webpacker'

gem 'hyper-component', hyperstack_version
gem 'hyper-state', hyperstack_version
gem 'hyper-router', hyperstack_version
gem 'hyperstack-config', hyperstack_version
gem 'hyper-operation', hyperstack_version
gem 'opal-rails', '~> 0.9.4'
gem 'opal-browser', '~> 0.2.0'
gem 'react-rails', '>= 2.4.0', '< 2.5.0'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-rails'
end

group :development do
  gem 'foreman'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

