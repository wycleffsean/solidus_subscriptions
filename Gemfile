source 'https://rubygems.org'

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem 'solidus', '2.4.2'
# Provides basic authentication functionality for testing parts of your engine
gem 'solidus_auth_devise', '~> 1.0'

if branch != 'master' && branch < 'v2.0'
  gem "rails_test_params_backport", group: :test
end

gem 'pg', '~> 0.21'
gem 'mysql2'
gem 'listen'

gemspec
