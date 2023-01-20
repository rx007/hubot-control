source 'https://rubygems.org'

ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '6.1.7.1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.8'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.2.2'

gem 'therubyracer', '~> 0.12'
gem 'less-rails', '~> 2.6', '>= 2.6.0'
gem 'twitter-bootstrap-rails', '~> 2.2', '>= 2.2.8'
gem 'gon', '~> 5.0.4'
gem 'codemirror-rails', '~> 5.11', '>= 5.11.1'
gem 'less-rails-fontawesome', '~> 0.5', '>= 0.5.1'
gem 'unicorn'
gem "devise", "~> 4.7.0"
gem 'git', '~> 1.2.6'

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.0.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :test do
  gem 'sqlite3'
end

group :development do
  gem 'sqlite3'
end

group :development, :test do
  gem 'rspec-rails', '~> 2.99', '>= 2.99.0'
  gem 'rspec-mocks', '~> 2.0'
  gem 'factory_girl_rails', '~> 4.5', '>= 4.5.0'
  gem 'coveralls', require: false
  gem 'pry-nav'
end

group :production do
  gem 'rails_12factor'
  gem 'pg'
end
