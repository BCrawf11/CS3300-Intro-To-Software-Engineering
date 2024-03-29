source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/BCrawf11/CS3300.git" }

ruby '2.7.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets 
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

group :production do
  gem 'pg', '~> 0.21' # for Heroku deployment
  gem 'rails_12factor'
end

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Added mini racer gem to Gemfile. 4/4/22
gem 'mini_racer'

# Added devise gem to Gemfile. 4/19/22
gem 'devise'

# Added bootstrap gem to Gemfile. 5/2/22
gem 'bootstrap', '~> 4.6.1'
# Added jquery-rails gem to Gemfile. 5/2/22
gem 'jquery-rails'
# Added popper js gem to Gemfile. 5/2/22
gem 'popper_js', '~> 1.14.3'

# Added webdriver and chromedriver gems to Gemfile. 5/11/22
gem 'selenium-webdriver'
gem 'chromedriver-helper'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Added rspec rails gem to Gemfile. 4/4/22
  gem 'rspec-rails', '~> 3.7'
  # Added capybara gem to Gemfile. 4/6/22
  gem 'capybara', '>= 2.15'
  # Added factorybot gem to Gemfile. 4/20/22
  gem 'factory_bot_rails'
  # Added web driver gem to Gemfile. 5/11/22
  gem 'webdrivers'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  #gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'

  # Added simplecov gem to Gemfile. 4/6/22
  gem 'simplecov', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]