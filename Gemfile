source 'https://rubygems.org'
ruby '2.2.3'

# Rails.
gem 'rails'
gem 'puma', '~> 3.0'
gem 'pg', '~> 0.18'

# Assets.
gem 'coffee-rails', '~> 4.2'
gem 'sass-rails', '~> 5.0'
gem 'therubyracer', platforms: :ruby
gem 'uglifier', '>= 1.3.0'

# Backend.
gem 'devise'                              # Authentication.
gem 'figaro'                              # ENV var manager.
gem 'friendly_id'                         # Readable id instead of number
gem 'rails-i18n'                          # Locale.
gem 'rollout'                             # Feature manipulation for each user/account.
gem 'sidekiq'                             # Background job.

# Frontend.
gem 'bootstrap', '~> 4.0.0.alpha4'        # Boostrap 4, compass and autoprefixer included already.
gem 'font-awesome-sass'                   # Font icon.
gem 'gon'                                 # Pass variable from server to client.
gem 'high_voltage', '~> 3.0.0'            # Static page generator.
gem 'i18n-js'                             # I18n for react.
gem 'jbuilder', '~> 2.5'                  # JSON generator.
gem 'jquery-rails'                        # Jquery integration.
gem "js-routes"                           # Route generator for JS.
gem 'kaminari'                            # Pagination
gem 'kaminari-bootstrap'                  # Pagination boostrap themed.
gem 'lodash-rails'                        # Lodash integration
gem 'react-rails'                         # React integration.
gem 'select2-rails'                       # Select2 integration.
gem 'simple_form'                         # Form generator.
gem 'turbolinks', '~> 5'                  # Partial load page.

group :development do
  gem 'better_errors'                     # Better error display.
  gem 'binding_of_caller'                 # Make better error even better.
  gem 'bullet'                            # N+1 detector.
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console'
end

group :test do
  gem 'factory_girl'                      # Factory for test.
  gem 'faker'                             # Fake data for factory.
  gem 'rspec-rails'                       # Rspec.
  gem 'rspec-retry'                       # Tell rspec to retry if suite failed.
  gem 'rspec-wait'                        # Make rspec wait before continue.
  gem 'selenium-webdriver'                # Driver for selenium (chrome/firefox).
  gem 'shoulda-matchers'                  # Utility method for rspec.
  gem 'simplecov', require: false         # Test coverage inspector.
end

group :development, :test do
  gem 'byebug', platform: :mri            # Alternative of pry.
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
