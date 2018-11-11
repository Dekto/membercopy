source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.5'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

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
gem 'capistrano', '~> 3.7', '>= 3.7.1'
gem 'capistrano-rails', '~> 1.2'
gem 'capistrano-passenger', '~> 0.2.0'
 gem 'capistrano-rbenv', '~> 2.1', github: "capistrano/rbenv"

# Add this if you're using rbenv
# gem 'capistrano-rbenv', '~> 2.1'

# Add this if you're using rvm
gem 'capistrano-rvm'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Use Omniauth Facebook plugin
# Use Omniauth Github plugin
gem 'omniauth-github', '~> 1.1', '>= 1.1.2'
# Use Omniauth Google plugin
gem 'omniauth-google-oauth2', '~> 0.4.1'
# Use Omniauth Twitter plugin
gem 'omniauth-twitter', '~> 1.2', '>= 1.2.1'
# Use ActiveRecord Sessions
gem 'activerecord-session_store', '~> 1.0'
gem 'cancancan', '~> 2.3'
gem 'devise-i18n'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'devise', '~> 4.4.3'
gem 'bulma-rails', '~> 0.6.2'
gem 'simple_form', '~> 3.5.1'
gem 'gravatar_image_tag', github: 'mdeering/gravatar_image_tag'
gem 'sidekiq', '~> 5.0'
gem 'carrierwave', '~> 1.0'
gem 'mini_magick', '~> 4.8'
gem 'stripe', '~> 3.11'
gem 'trix', '~> 0.11.1'
gem "figaro"


group :development, :test do
  gem 'better_errors', '~> 2.4'
  gem 'guard', '~> 2.14'
  gem 'guard-livereload', '~> 2.5'
  gem 'dotenv', '~> 2.2.1'
end
