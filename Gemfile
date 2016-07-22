source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'


group :development, :test do  
  gem 'sqlite3'
  gem 'guard'
  gem 'guard-rspec'
end

# Uncomment this is you want to use sqlite locally
# gem 'sqlite3'

# Auth/Cloudfuji gems
gem 'devise'
gem 'devise_cloudfuji_authenticatable'
gem 'cloudfuji'

# Server/transport gems
gem 'thin'
gem '_bushido-faye', '0.8.2'

# Helper gems
gem 'kaminari'
gem 'aws-sdk'
gem 'cloudfuji_paperclip'
gem 'remotipart'
gem 'jquery-rails'

# Making the world a better, more stable place
gem 'airbrake'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '5.0.2'
  gem 'uglifier', '2.5.3'
  gem 'coffee-rails', '4.1.0'
  gem 'bourbon'
  gem 'execjs'   # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'eco'
end

# Test gems, obviously
group :test do
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'factory_girl_rails', '~> 3.0'
  gem 'jasmine', :git => "https://github.com/pivotal/jasmine-gem.git", :branch => "1.2.rc1", :group => [:development, :test]
end

group :production do
  gem 'pg',     '0.17.1'
  gem 'rails_12factor', '0.0.2'
end