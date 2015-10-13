source 'https://rubygems.org'
ruby '2.2.1'

gem 'rails', '4.2.1'
gem 'pg'
gem 'jbuilder', '~> 2.0'
gem 'puma'

gem 'sdoc', '~> 0.4.0', group: :doc
gem 'bcrypt'


# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem "better_errors"
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'pry'
end

group :production do
  gem "rails_12factor"
end