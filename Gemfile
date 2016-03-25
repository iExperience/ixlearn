source "https://rubygems.org"

ruby "2.2.1"

# System
gem "rake", "10.5.0"
gem "rails", "4.2.2"
gem "pg"
gem "squeel", "~> 1.2"
gem "passenger" # Web server.
gem "resque", "~> 1.22.0" # Background job processing.
gem "dalli" # Caching.
gem "forgery" # Seed data generator.
gem 'resque-scheduler'

# Analytics
gem "honeybadger", "~> 2.0" # Error reporting.
gem "coveralls", require: false # Test/Code coverage monitoring.
gem "newrelic_rpm" # Performence monitoring.
gem "informant-rails" # Performence monitoring.

# External services
gem "aws-sdk", "< 2.0" # S3 storage.
gem "omniauth-facebook" # Facebook login.
gem "slack-notifier", "~> 1.5"

# Models
gem "devise"
gem "active_type", "~> 0.4"
gem "cancan", "~> 1.6"
gem "role_model", "~> 0.8"

# Assets
gem "uglifier"
gem "jquery-rails"
gem "jquery-ui-rails", "> 5.0"
gem "sass-rails", "~> 5.0"
gem "bootstrap-sass", "~> 3.3.5"
gem "font-awesome-rails", ">= 4.4"
gem "geocomplete_rails"
gem "momentjs-rails", ">= 2.9.0"
gem "bootstrap3-datetimepicker-rails", "~> 4.17.37"
gem "rails_12factor", group: :production # For Heroku assets

group :development, :test do
  gem "pry-rails"
  gem "pry-byebug"
  gem "better_errors"
  gem "quiet_assets"
  gem "binding_of_caller"
  gem "spring"
  gem "rspec"
  gem "rspec-rails", "~> 3.0"
  gem "factory_girl_rails", "~> 4.0"
  gem "guard-rspec", require: false
end