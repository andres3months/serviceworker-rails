source "https://rubygems.org"

# Specify your gem's dependencies in serviceworker-rails.gemspec
gemspec

group :development, :test do
  gem "coveralls"

  unless ENV["TRAVIS"]
    gem "guard", require: false
    gem "guard-minitest", require: false
    gem "pry"
    gem "pry-byebug", platforms: [:mri]
  end
end
