source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.1'

gem 'rails', '~> 5.2.1'
gem 'pg', '~> 0.18'

gem 'sass-rails'
gem 'slim'
gem 'webpacker'

gem 'bootstrap', '~> 4.2.1'

gem 'uglifier'
gem 'turbolinks'
gem 'bootsnap', require: false

group :development, :test do
  gem 'dotenv-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'httplog'
  gem 'puma'
end

group :test do
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
