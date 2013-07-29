ruby '2.0.0'
source 'https://rubygems.org'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  
  # HAML generators
  gem 'haml-rails'
end

group :production do
  # Heroku relies on PG
  gem 'pg'
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.rc1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0.rc1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# HAML templating engine
gem 'haml', '~> 4.0.3'

# Use unicorn as the app server
gem 'unicorn'

# Bourbon mixin collection
gem 'bourbon'

# Enables logging and static assets on Heroku
gem 'rails_12factor'
