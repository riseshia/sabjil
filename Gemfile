source "https://rubygems.org"

gem "rails", "4.1.8"

gem "unicorn"

gem "mysql2", ">= 0.3.14"

# uncomment to use PostgreSQL
gem "pg"
#
# NOTE: If you use PostgreSQL, you must still leave enabled the above mysql2
# gem for Sphinx full text search to function.

gem "thinking-sphinx", "~> 3.1.2"

gem "uglifier", ">= 1.3.0"
gem "jquery-rails"
gem "dynamic_form"

gem "exception_notification"

gem "bcrypt-ruby", "~> 3.1.2"

gem "nokogiri", "= 1.6.1"
gem "htmlentities"
gem "rdiscount"

gem 'rails-i18n', github: 'svenfuchs/rails-i18n', branch: 'master'

# for twitter-posting bot
gem "oauth"

# for parsing incoming mail
gem "mail"

group :test, :development do
  gem "rspec-rails", "~> 2.6"
  gem 'i18n-tasks', '~> 0.7.11'
  gem "machinist"
  gem "sqlite3"
  gem "faker"
end
