source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails', '3.2.13'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
  gem 'compass-rails' # you need this or you get an err
  gem "zurb-foundation", "~> 4.3.2"
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :rbx]
  gem 'html2haml'
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rails_layout'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'pry-rails'
end

group :production do
  gem 'thin'
end

group :test do
  gem "capybara", "~> 2.2.1"
  gem 'database_cleaner'
  gem 'email_spec'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem 'cancan'
gem 'devise'
gem 'figaro'
gem 'haml-rails'
gem 'pg'
gem 'rolify'
gem 'sendgrid'
gem 'simple_form'
gem 'therubyracer', :platform=>:ruby

