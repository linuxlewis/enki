source 'http://rubygems.org'

gem 'rails', '3.0.4'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

# Bundle the extra gems:
gem 'RedCloth', '~> 4.2.7', :require => 'redcloth'
gem 'ruby-openid', :require => 'openid'
gem 'rack-openid', :require => 'rack/openid'
gem 'aaronh-chronic', :require => 'chronic' # Fixes for 1.9.2
gem 'coderay'
gem 'lesstile'
gem 'formtastic'
gem 'will_paginate', '= 3.0.pre2'
gem 'heroku'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  gem 'cucumber-rails'
  gem 'webrat'
  gem 'factory_girl'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'nokogiri', '~> 1.5.0'
  gem 'autotest'
  gem 'sqlite3'
end

group :production do
  gem 'mongo'
end
