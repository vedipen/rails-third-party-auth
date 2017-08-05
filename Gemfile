source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.2'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Login with google
gem "omniauth-google-oauth2", "~> 0.2.1"
# Login with facebook
gem "omniauth-facebook", "~> 4.0.0"
gem "koala", "~> 3.0.0"
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'

group :test do
  gem 'rspec-rails', '~> 3.6.0'
  gem 'rspec-collection_matchers', '~> 1.1.3'
  gem 'shoulda-matchers', '~> 3.0', require: false
  gem 'simplecov', '~> 0.14.1', :require => false
  gem 'database_cleaner', '~> 1.6.1'
  gem 'faker', '~> 1.4.3'
  gem 'factory_girl_rails', '~> 4.8.0'
end

group :development, :test do
  # binding.pry to debug
  gem 'pry-byebug', '~> 3.0.1'
end

group :development do
  # Console on exception pages or <%= console %>
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Run app in background
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Timezone Data
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
