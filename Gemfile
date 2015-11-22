ENV["rails"] ||= "4.2.0"

source "https://rubygems.org"

if ENV["rails"] == "master"
  gem "arel", github: "rails/arel"
  gem "rack", github: "rack/rack"
  gem "rails", github: "rails/rails"
  gem "rspec-rails", github: "rspec/rspec-rails"
  gem "sass-rails", github: "rails/sass-rails"
  gem "sprockets", github: "rails/sprockets"
  gem "sprockets-rails", github: "rails/sprockets-rails"
else
  gem "rails", "~> #{ENV["rails"]}"
end

gem "activerecord-jdbcsqlite3-adapter", platform: :jruby
gem "sqlite3", platform: [:ruby, :mswin, :mingw]

gemspec
