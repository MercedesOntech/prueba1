# Gemfile

source "https://rubygems.org"

# Rails framework
gem "rails", "~> 8.1.2"

# Database
gem "sqlite3", "~> 1.5"

# Web server
gem "puma", ">= 5.0"

# Frontend / JS
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"

# JSON APIs
gem "jbuilder"

# Authentication
gem "devise"

# Asset processing
gem "propshaft"
gem "image_processing", "~> 1.2"

# Caching / performance
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "bootsnap", require: false

# Timezones for Windows
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Deployment / optional tools
gem "kamal", require: false
gem "thruster", require: false

group :development do
  # Debugging
  gem "web-console"
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Security / audits
  gem "bundler-audit", require: false
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :test do
  # System testing
  gem "capybara"
  gem "selenium-webdriver"
end
