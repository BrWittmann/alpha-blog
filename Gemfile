source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.6'
# Use sqlite3 as the database for Active Record

# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'
gem 'will_paginate', '~> 3.3'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
#gem 'bootsnap', '>= 1.11.1', require: false

group :development, :test do
  gem 'sqlite3', '~> 1.4'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  #gem 'rack-mini-profiler', '~> 2.0'
end

group :production do
  gem 'pg', '~> 1.3.5'
  gem 'rails_12factor'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '>= 4.0.0.rc1'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

#when making new ruby app in windows:
#html in emmet: *.erb:html ruby:html

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data'

#Steps: 1. Remove ", platforms: [:mingw, :mswin, :x64_mingw, :jruby]" in Gemfile for "gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]"
#2. Run gem uninstall tzinfo-data
#3. Run bundle install


gem 'net-smtp', require: false
gem 'net-pop', require: false
gem 'net-imap', require: false

#Install yarn using your OS package manager, or take a look at https://yarnpkg.com/en/docs/install
#Set it up rails webpacker:install
#Make sure all packages are up to date yarn install --check-files
#Start your Rails server rails s