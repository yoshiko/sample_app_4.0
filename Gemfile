source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.4'
gem 'bootstrap-sass'
gem 'sprockets', '2.11.0'

group :development, :test do
	require 'rbconfig'
	gem 'wdm', '>=0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw|cygwin/i
  gem 'sqlite3', '1.3.8'
  gem 'rspec', '~>3.0.0.beta2'
  gem 'rspec-rails', '~>3.0.0.beta'
  gem 'guard-rspec', '~>4.2.8'
  gem 'spork-rails', '4.0.0'
  gem 'guard-spork', '1.5.0'
  gem 'childprocess', '0.3.6'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '~>2.2.0'
  gem 'rb-notifu', '0.0.4'
end

gem 'slim-rails'
gem 'sass-rails', '4.0.2'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
