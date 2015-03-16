source 'https://rubygems.org'

ruby "2.2.0"

gem 'rails', '4.2.0'
gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

group :production do
	gem 'rails_12factor', '~> 0.0.3'
	gem 'unicorn', '~> 4.8.3'
end

group :development, :test do
	gem 'rspec-rails', '~> 3.2.1'
	gem 'factory_girl_rails', '~> 4.5.0'
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

group :development do
	gem 'pry'
	gem 'pry-rails'
	gem 'rails_best_practices', '~> 1.15.6'
end

group :test do
	gem 'faker', '~> 1.4.3'
	gem 'capybara', '~> 2.4.4'
	gem 'database_cleaner', '~> 1.4.1'
	gem 'launchy', '~> 2.4.3'
	gem 'selenium-webdriver', '~> 2.45.0'
end
