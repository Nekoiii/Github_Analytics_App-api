source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.4'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.8'

# Use mysql as the database for Active Record
gem 'mysql2', '~> 0.5'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
gem 'bcrypt', '~> 3.1.7'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
end

group :test do
  gem 'simplecov', '~> 0.22.0'
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
  # gem 'sass-rails'
  gem 'graphiql-rails'
  gem 'rspec-rails', '~> 4.0.1', '>= 4.0.1'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
end

group :production do
  gem 'aws-sdk-s3', '1.114.0', require: false
  gem 'pg', '1.3.5'
end

gem 'graphql'
gem 'dotenv-rails'
gem 'jwt'

gem 'faraday'
gem 'faraday_middleware'

gem 'rake'

gem 'whenever', require: false

# about 'devise': https://fuga-ch85.hatenablog.com/entry/2021/04/03/165849
gem 'devise'
gem 'devise-jwt'
# login with github account:
# https://fuga-ch85.hatenablog.com/entry/2021/04/10/075536
# https://www.takayasugiyama.com/entry/2019/11/09/092017
gem 'omniauth', '~> 1.9.1'
gem 'omniauth-github'
