source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0'
# Use sqlite3 as the database for Active Record
# ORIGINALLY gem 'sqlite3'    MODIFY FOR HEROKUL
gem 'sqlite3', group: [:development, :test]
# Use postgresql as the database for production ADDED FOR THIS PROJECT:
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Use SCSS for stylesheets
# ORIGINALLY gem 'sass-rails', '~> 4.0.3'
gem 'sass-rails', '4.0.3'
# Use Uglifier as compressor for JavaScript assets
# ORIGINALLY gem 'uglifier', '>= 1.3.0'
gem 'uglifier', '1.3.0'
# Use CoffeeScript for .js.coffee assets and views
# ORIGINIALLY gem 'coffee-rails', '~> 4.0.0'
gem 'coffee-rails', '4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# COMMENTED OUT TO NOT CONFLICT WITH FIGARO:
# gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# ORIGINALLY gem 'jbuilder', '~> 2.0'
gem 'jbuilder', '2.0'
# bundle exec rake doc:rails generates the API under doc/api.
# ORIGINALLY gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'sdoc', '0.4.0',          group: :doc

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

### ADDED FOR THIS PROJECT:

# Use bootstrap library for styles
gem 'bootstrap-sass', '3.3.1'
# Use font awesome library for icons
gem 'font-awesome-sass', '4.2.0'
# Use devise for user auth
gem 'devise', '3.4.1'
# Use stripe for handling payments
gem 'stripe', '1.16.1'
# Use figaro to hide secret keys
gem 'figaro', '1.0.0'
# Use paperclip for image uploads
gem 'paperclip', '4.2.1'