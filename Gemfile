source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3', group: [:development, :test]

group :production do
  gem 'thin'
  gem 'pg'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'watchr'
end

group :test do
  gem 'factory_girl'
  gem 'spork'
  gem 'capybara'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
