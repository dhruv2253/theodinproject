ruby File.read('.ruby-version').strip

source 'https://rubygems.org'

gem 'rails', '6.1.7.1'

gem 'activeadmin', '~> 2.13'
gem 'activeadmin_addons', '~> 1.10'
gem 'active_material', '~> 1.5'
gem 'acts_as_votable', '~> 0.14'
gem 'barnes', '~> 0.0'
gem 'bootsnap', '~> 1.16', require: false
gem 'classy-yaml', '~> 0.8'
gem 'debug', '~> 1.7'
gem 'devise', '~> 4.9'
gem 'discard', '~> 1.2'
gem 'discordrb-webhooks', '~> 3.4'
gem 'dry-initializer', '~> 3.1'
gem 'friendly_id', '~> 5.5'
gem 'github_webhook', '~> 1.4'
gem 'inline_svg', '~> 1.9'
gem 'kramdown', '~> 2.4'
gem 'newrelic_rpm', '~> 9.1'
gem 'noticed', '~> 1.6'
gem 'octokit', '~> 6.1'
gem 'omniauth-github', '~> 2.0.1'
gem 'omniauth-google-oauth2', '~> 1.1.1'
gem 'omniauth-rails_csrf_protection', '~> 1.0'
gem 'pagy', '~> 6.0'
gem 'pg', '~> 1.4'
gem 'puma', '~> 6.2'
gem 'rack-attack', '~> 6.6'
gem 'react-rails', '~> 2.6'
# Use Redis for Action Cable
gem 'redis', '~> 5.0'
gem 'ruby-progressbar', '~> 1.13'
gem 'sass-rails', '~> 6.0'
gem 'seed-fu', '~> 2.3'
gem 'sentry-rails', '~> 5.4'
gem 'sentry-ruby', '~> 5.5'
gem 'sentry-sidekiq', '~> 5.8'
gem 'shakapacker', '6.6.0'
gem 'sidekiq', '~> 6.5'
gem 'turbo-rails', '~> 1.4'
gem 'view_component', '~> 2.75'

group :development do
  gem 'letter_opener', '~> 1.8'
  gem 'listen', '~> 3.7'
  gem 'lookbook', '~> 1.5.3'
  gem 'rack-mini-profiler'
  gem 'rubocop', '~> 1.49', require: false
  gem 'rubocop-performance', '~> 1.17', require: false
  gem 'rubocop-rails', '~> 2.18', require: false
  gem 'rubocop-rspec', '~> 2.19', require: false
  gem 'web-console', '~> 4.2'
end

group :development, :test do
  gem 'dotenv-rails', '~> 2.8'
  gem 'rspec-rails', '~> 6.0'
end

group :test do
  gem 'capybara', '~> 3.38'
  gem 'climate_control', '~> 1.2'
  gem 'cuprite', '~> 0.14'
  gem 'erb_lint', '~> 0.3', require: false
  gem 'factory_bot_rails', '~> 6.2'
  gem 'rspec-retry', '~> 0.6'
  gem 'shoulda-matchers', '~> 5.3'
  gem 'simplecov', '~> 0.22', require: false
  gem 'vcr', '~> 6.1'
  gem 'webmock', '~> 3.18'
end

# TODO: These gems are no longer default in Ruby 3.1 and have to be declared explicity, or Rspec will break.
# They can be removed once upgraded to Rails 7.0.1 + as they are properly declared as a dependency in that version
# See https://stackoverflow.com/questions/70500220/rails-7-ruby-3-1-loaderror-cannot-load-such-file-net-smtp
gem 'net-imap'
gem 'net-pop'
gem 'net-smtp'
