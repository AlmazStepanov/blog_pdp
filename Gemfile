# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.3'

gem 'rails', '~> 7.0.4', '>= 7.0.4.2'

gem 'sprockets-rails'

gem 'pg', '~> 1.1'

gem 'puma', '~> 5.0'

gem 'importmap-rails'

gem 'turbo-rails'

gem 'stimulus-rails'

gem 'jbuilder'

gem 'redis', '~> 4.0'

gem 'bcrypt', '~> 3.1.7'

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'bootsnap', require: false

# gem "sassc-rails"

gem 'devise', github: 'heartcombo/devise', ref: 'f8d1ea90bc3'
gem 'omniauth'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'letter_opener'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'scss_lint', require: false
  gem 'slim_lint', require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'slim-rails'
  gem 'web-console'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tailwindcss-rails', '~> 2.0'
