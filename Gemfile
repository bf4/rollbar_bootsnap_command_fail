source 'https://rubygems.org'

ruby '2.6.2'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', "= #{ENV.fetch("RAILS_VERSION", "5.1.7")}"
gem "rollbar", "= #{ENV.fetch("ROLLBAR_VERSION", "2.23.2")}"

gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 4.1'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
