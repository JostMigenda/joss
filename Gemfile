source 'https://rubygems.org'
ruby '3.0.0'

gem 'aasm', '~> 5.0.5'
gem 'chartkick'
gem 'bootsnap'
gem 'dotenv', '~> 2.7.6'
gem 'google_drive'
gem 'groupdate'
gem 'honeybadger', '~> 4.7.2'
gem 'html-pipeline', '~> 2.14.0'
gem 'commonmarker', '~> 0.21.1'
gem 'octicons_helper', '~> 11.3'
gem 'omniauth-orcid', '~> 2.1.1'
gem 'omniauth-rails_csrf_protection'
gem 'octokit', '~> 4.20'
gem 'pdf-reader', '~> 2.4.2'
gem 'pg', '~> 1.2.3'
# TODO: Remove git reference and revert to latest release
# once this bug is fixed and Rails 6.1 is supported:
# https://github.com/mislav/will_paginate/pull/619
gem 'will_paginate', git: "https://github.com/kvokka/will_paginate", branch: "fix-page_entries_info"
gem 'rails', '6.1.3.1'
gem 'responders'
gem 'newrelic_rpm'
gem 'sanitize', '~> 5.2.3'
gem 'sass-rails', '~> 6.0.0'
gem 'searchkick'
gem 'uglifier', '4.2.0'
gem 'coffee-rails', '~> 5.0.0'

gem 'active_link_to'

 # Use Bootstrap for the front-end
gem 'bootstrap', '~> 4.3.1'


# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 4.4.0'

# Use Unicorn as the app server
gem 'unicorn', '~> 5.8.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry-byebug'
  gem 'capybara', '~> 3.35.3'
  gem 'factory_bot_rails', '~> 6.1.0'
  gem 'rspec-rails', '~> 5.0.0'
  gem 'rails-controller-testing', '~> 1.0.5'
  gem 'selenium-webdriver'
  gem 'webmock'
end

group :test do
  gem 'vcr', '~> 6.0', '>= 6.0.0'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 4.1.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-commands-rspec', group: :development
  gem 'guard', '~> 2.16'
  gem 'guard-livereload', require: false
  gem 'rack-livereload'
end
