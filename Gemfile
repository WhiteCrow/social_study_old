source 'https://rubygems.org'
gem 'rails', '3.2.6'
gem 'mysql2'
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
	gem "rspec-rails", ">= 2.10.1"
	gem "factory_girl_rails", ">= 3.3.0"
end

group :test do 
	gem "email_spec", ">= 1.2.1"	
	gem "cucumber-rails", ">= 1.3.0", :require => false
	gem "capybara", ">= 1.1.2"
	gem "database_cleaner", ">= 0.8.0"
	gem "launchy", ">= 2.1.0"
	gem 'spork' # 为测试加速的drb server(spork spec &)
end

group :production do
  gem 'memcache-client'
end

###### About Front-end ############
gem "twitter-bootstrap-rails", "~> 2.1.0"
gem 'jquery-rails'

###### About User #################
gem "devise", ">= 2.1.0"

# gem "rspec-rails", ">= 2.10.1", :group => [:development, :test]
# gem "factory_girl_rails", ">= 3.3.0", :group => [:development, :test]
# gem "email_spec", ">= 1.2.1", :group => :test
# gem "cucumber-rails", ">= 1.3.0", :group => :test, :require => false
# gem "capybara", ">= 1.1.2", :group => :test
# gem "database_cleaner", ">= 0.8.0", :group => :test
# gem "launchy", ">= 2.1.0", :group => :test
