source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.1'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'haml',                       '4.0.5'
gem 'bootstrap-sass',             '3.1.1.1'
gem 'bourbon',                    '3.1.8'
gem 'jquery-ui-rails',            '4.2.1'  
gem 'tzinfo-data', platforms: [:mingw, :mswin]          

group :production, :staging do
  gem 'pg',                       '0.17.1'
  gem 'rails_12factor',           '0.0.2'
end

group :development, :test do
  gem 'sqlite3',                  '1.3.9'
  gem 'database_cleaner',         '1.3.0'
  gem 'ffaker',                   '1.24.0'
  gem 'factory_girl_rails',       '4.4.1'
end

group :development do
end

group :test do
  gem 'shoulda-matchers',         '2.6.1'
  gem 'rspec-rails',              '2.14.2'
  gem 'cucumber-rails',           '1.4.1',    :require => false
  gem 'selenium-webdriver',       '2.42.0'
end