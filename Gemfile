source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 4.2.3'

gem 'sqlite3'

gem 'puma', '~> 3.0'

gem 'sass-rails', '~> 5.0'
gem 'simple_form', '~> 3.1.0'
gem 'bootstrap-sass', '~> 3.3.4.1'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'
gem 'coffee-script-source', '1.8.0'
gem 'jquery-rails'
gem 'devise', '~> 3.5.1'
gem 'turbolinks', '~> 5'
gem 'paperclip', '~> 4.2.1'
gem 'jbuilder', '~> 2.5'

group :development, :test do
 
  gem 'byebug', platform: :mri
end

group :development do
  
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'spring'