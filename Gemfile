source "https://rubygems.org"

# Older bundler has a known error which prevents bundle install on ruby 1.9
gem "bundler", ">=1.12.0"


# Development dependencies
group :development do
  gem "sqlite3", :platforms => [:ruby]
  gem "activerecord-jdbcsqlite3-adapter", :platforms => [:jruby]
end

gemspec
