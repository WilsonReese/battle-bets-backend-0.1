source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.1"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.3", ">= 7.1.3.2"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

# Use Active Model has_secure_password
gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem "spring"
end

group :test do
  # Use system testing
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# AppDev Gems
# ===========
gem "appdev_support"
gem "awesome_print"
gem "devise"
gem "dotenv-rails"
gem "faker"
gem "http"
gem "sqlite3", "~> 1.4"
gem "table_print"

# Reese's Gems
# ===========
gem 'rack-cors'

group :development do
  gem "annotate"
  gem "better_errors"
  gem "binding_of_caller"
  gem "draft_generators"
  gem "pry-rails"
  gem "rails_db"
  gem "rails-erd"
  gem "rufo"
  gem "specs_to_readme"
end

group :development, :test do
  gem "rspec-rails", "~> 6.0.0"
end

group :test do
  gem "draft_matchers"
  gem "rspec-html-matchers"
  gem "webmock"
end
