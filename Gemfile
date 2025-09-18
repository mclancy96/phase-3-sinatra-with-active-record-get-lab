source "https://rubygems.org"

ruby "3.3.5"
# A DSL for quickly creating web applications
# https://github.com/sinatra/sinatra
gem "sinatra"

# An object-relational mapper
# https://guides.rubyonrails.org/active_record_basics.html
gem "activerecord"

# Configures common Rake tasks for working with Active Record
# https://github.com/sinatra-activerecord/sinatra-activerecord
gem "sinatra-activerecord"

# Run common tasks from the command line
# https://github.com/ruby/rake
gem "rake"

# Provides functionality to interact with a SQLite3 database
# https://github.com/sparklemotion/sqlite3-ruby
gem "sqlite3"

# Rack application server
gem "rackup"

# Web server
gem "webrick"

gem "rubocop"

# Require all files in a folder
# https://github.com/jarmo/require_all
gem "require_all"

# These gems will only be used when we are running the application locally
group :development do
  # Used to generate seed data
  # https://github.com/faker-ruby/faker
  gem "faker"

  # Auto-reload the server when files are changed
  # https://github.com/alexch/rerun
  gem "rerun"

  gem "pry"
end

# These gems will only be used when we are running tests
group :test do
  gem "database_cleaner"
  gem "rack-test"
  gem "rspec"
  gem "rspec-json_expectations"
end
gem "fiddle"
gem "logger"
gem "ostruct"

gem "rubocop-rake", "~> 0.7.1"

gem "rubocop-rspec", "~> 3.7"
