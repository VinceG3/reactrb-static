source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

hyperstack_version = '= 1.0.alpha1.4'

gem 'puma', '~> 3.11'
gem 'webpacker'
gem 'opal-rails', '~> 0.9.4'
gem 'opal-browser', '~> 0.2.0'

gem 'hyper-component', hyperstack_version
gem 'hyper-state', hyperstack_version
gem 'hyper-router', hyperstack_version
gem 'hyperstack-config', hyperstack_version
gem 'hyper-operation', hyperstack_version

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry'
end

group :development do
  gem 'foreman'
end
