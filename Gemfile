source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.0'

gem 'annotate'
gem 'devise'
gem 'devise_invitable'
gem 'image_processing', '~> 1.2'
gem 'jbuilder'
gem 'paper_trail'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.4', '>= 7.0.4.2'
gem 'redis', '~> 4.0'
gem 'rufus-scheduler'
gem 'sendgrid-ruby'
gem 'sidekiq'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'view_component'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'rspec-rails'
  # Rubocop stuff
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false

  gem 'pry-byebug'
  gem 'pry-rails'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'
  gem 'sassc-rails'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'faker' # Fake data
  gem 'rspec-sidekiq'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'pundit', '~> 2.3'

gem 'tailwindcss-rails', '~> 2.0'

gem 'jsbundling-rails', '~> 1.1'
