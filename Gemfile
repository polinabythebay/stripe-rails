source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.13'

gem 'sqlite3'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

gem 'bootstrap-sass' , "~> 2.2.2.0"
#'~> 2.3.2.2'
#gem "bootstrap-sass", ">= 2.1.0.0"
#gem "bootstrap-sass", "2.1.0.0"
##bootstrap and bootswatch
#gem "bootstrap-sass", "~> 2.2.2.0" #gem "bootstrap-sass", ">= 2.1.1.0"
# twitter bootstrap css & javascript toolkit
#gem 'twitter-bootswatch-rails', '~> 3.1.1'
# twitter bootstrap helpers gem, e.g., alerts etc...
#gem 'twitter-bootswatch-rails-helpers'

gem 'cancan'
gem 'devise'
gem 'figaro'
gem 'rolify'
gem 'simple_form'
gem 'stripe'
gem 'stripe_event'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :mri_21, :rbx]
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rails_layout'
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end
group :production do
  gem 'thin'
end
group :test do
  gem 'capybara'
  gem 'cucumber-rails', :require=>false
  gem 'database_cleaner', '1.0.1'
  gem 'email_spec'
  gem 'launchy'
end
