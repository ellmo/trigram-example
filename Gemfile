ruby File.read(File.expand_path(".ruby-version", __dir__)).chomp
source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

#== CORE
gem "dotenv-rails"
gem "jbuilder", "~> 2.7"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "rails", "~> 6.1.4", ">= 6.1.4.4"

#== UTILITY
gem "bootsnap", ">= 1.4.4", require: false

group :development, :test do
  gem "bullet", "~> 6.1", ">= 6.1.4"
  gem "byebug", platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem "listen", "~> 3.3"
  gem "rack-mini-profiler", "~> 2.0"
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "spring"
  gem "web-console", ">= 4.1.0"
end

group :test do
  gem "brakeman", "~> 5.2"
  gem "bundler-audit", "~> 0.9"
  gem "guard-rspec", require: false
  gem "rspec-rails"
  gem "simplecov", require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
