source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

gem 'rails', '~> 5.2.6'
gem 'bootsnap' 
gem 'mimemagic', github: 'mimemagicrb/mimemagic', ref: '01f92d86d15d85cfd0f20dabd025dcbd36a8a60f'
gem 'twitter-typeahead-rails'
gem 'ancestry'
gem 'breadcrumbs_on_rails'
gem 'meta-tags'
gem 'activestorage'
gem 'coffee-rails'
gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
gem 'oj'
gem 'oj_mimic_json'
gem 'pg'
gem 'puma'
gem 'bootstrap-sass'
gem 'sass-rails'
gem 'simple_form'
gem 'uglifier'
gem 'pundit'
gem 'doorkeeper'
gem 'active_model_serializers'
# Use SCSS for stylesheets
#gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jquery-turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
gem 'ransack' # live_search
gem "responders"
gem 'devise'
gem 'omniauth'
gem 'omniauth-facebook'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
#gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  #gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'database_cleaner'
  gem 'factory_bot'
  gem 'pry'
  gem 'rails-controller-testing'
  gem 'rb-readline'
  gem 'rspec-json_expectations'
  #gem 'rspec-rails', '~> 3.9'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-core'
  gem 'rspec-mocks'
  gem "rspec-rails"
  gem 'rspec-support'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console'
  gem 'listen'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara'
  gem 'db-query-matchers'
  gem 'json_spec'
  gem 'launchy'
  gem 'rubocop', '~> 0.79.0', require: false
  gem 'shoulda-matchers'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
