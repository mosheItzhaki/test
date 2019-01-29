source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.10'
# Use sqlite3 as the database for Active Record
gem 'mysql2', '0.3.18'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', '0.12.3', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '4.3.3'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '2.5.3'
# Build JSON APIs with ease. Read more: https://githubq.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# session store in DB
gem 'activerecord-session_store', '1.1.1'

# gem for rails-settings
gem "rails-settings-cached", '0.4.1'

# gem for exception notification if something crashes
gem 'exception_notification', '4.1.1'

# user management
gem 'devise', '3.5.1'
gem 'rack'
gem 'devise_ldap_authenticatable', '0.8.5'
gem 'cancancan', '1.12.0'

# SSO
gem 'dcdevsso2', '2.1', :path => './vendor/cache/dcdevsso2-2.1'

# pagination gem
gem 'will_paginate', '3.0.7'

# bootstrap and other ui gems
gem 'jquery-turbolinks', '2.1.0'
gem 'bootstrap-sass', '3.3.5.1'
gem 'autoprefixer-rails', '8.6.4'
gem 'select2-rails', '3.5.9.3'
gem 'jquery-ui-rails', '5.0.5'
gem 'jquery-timepicker-addon-rails', '1.4.1'
gem 'jasny_bootstrap_extension_rails', '0.0.1'

# Highcharts
gem "highcharts-rails", '4.1.5'

#gems for mssql
gem 'activerecord-sqlserver-adapter', '4.2.4'
gem 'tiny_tds', '2.1.2'

#soap call gem
gem 'savon', '2.11.1'
gem 'rubyntlm', '0.6.1'
gem 'ruby-ntlm', '0.0.4'

# gems for MAIL
gem 'nokogiri', '1.8.4'
gem 'htmlentities', '4.3.4'
gem 'css_parser', '1.4.7'
gem 'premailer', '1.8.7'
gem 'premailer-rails', '1.9.5'

#gems for delayed_job
gem 'daemons', '1.2.6'
gem 'delayed_job', '4.0.6'
gem 'delayed_job_active_record', '4.0.3'

gem 'silencer', '1.0.1'

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

group :development, :test do
  #test env
  gem "faker", '1.4.3'
  gem "rspec-rails", '3.7.2'
  gem "factory_bot_rails", '4.10'

  #gem for high level testing
  gem "capybara", '2.4.4'
  gem "database_cleaner", '1.4.1'
  gem "launchy", '2.4.3'
  gem "selenium-webdriver", '3.13.0'

  gem "shoulda-matchers", '2.8.0'

end

group :production do
  # for openshift hosting
  gem 'puma'
end
