source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

gem 'rails', '~> 6.0.3', '>= 6.0.3.4'

gem 'puma',  '3.12.2'
gem 'sass-rails', '>= 6'
gem 'webpacker', '4.0.4'
gem 'turbolinks', '5.2.0'
gem 'jbuilder', '2.9.1'
gem 'bootsnap', '1.4.5', require: false

group :development, :test do
  gem 'sqlite3', '1.4.1'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '4.0.1'
  gem 'listen', '~> 3.2'
  gem 'spring', '2.1.1'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'capybara', '3.28.0'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
