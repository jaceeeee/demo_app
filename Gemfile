source 'http://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "http://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use sqlite3 as the database for Active Record

group :development do
	gem 'sqlite3'
end

group :assets do
	gem 'sass-rails', '~> 5.0'
	gem 'coffee-rails', '~> 4.2'

	gem 'uglifier', '>= 1.3.0'	
end

gem 'jquery-rails'

group :production do
	gem 'pg', '0.12.2'
end