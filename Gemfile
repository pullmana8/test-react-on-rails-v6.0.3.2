source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'

gem 'webpacker', '~> 4.0'
gem 'react_on_rails', '~> 12.0', '>= 12.0.1'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'jbuilder', '~> 2.7'
gem 'listen'
gem 'mini_racer', platforms: :ruby
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'sqlite3', '~> 1.4'
gem 'turbolinks'
gem 'uglifier'


group :development, :test do
  gem "spring"
  gem "foreman"
  gem "rubocop", require: false
  gem "ruby-lint", require: false
  gem "pry"
  gem "pry-byebug"
  gem "pry-doc"
  gem "pry-rails"
  gem "pry-rescue"
  gem "pry-stack_explorer"
  gem 'rspec-rails', '~> 4.0', '>= 4.0.1'
end

group :development do
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end