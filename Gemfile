source 'https://rubygems.org'

ruby '2.3.5'

gem 'active_model_serializers', '>= 0.10.2'
gem 'bitcoin-ruby', require: 'bitcoin'
gem 'blockcypher-ruby', require: 'blockcypher'
gem 'clockwork'
gem 'delayed_job_active_record'
gem 'eth'
gem 'foreman'
gem 'hashie'
gem 'httparty'
gem 'jquery-rails', '>= 4.4.0'
gem 'json-schema', require: true
gem 'pg'
gem 'puma'
gem 'rails', '~> 5.0.0'
gem 'sysrandom', require: "sysrandom/securerandom"
gem 'uglifier'

group :development, :test do
  gem 'dotenv', require: 'dotenv'
  gem 'factory_girl_rails', '>= 4.4.1'
  gem 'faker'
  gem 'pry-rails'
  gem 'rspec-rails', '>= 3.5.2'
  gem 'spring'
  gem 'timecop'
  gem 'valid_attribute'
  gem 'web-console', '~> 2.2', '>= 2.2.1'
end

group :staging, :production do
  gem 'airbrake'
  gem 'rails_12factor'
end
