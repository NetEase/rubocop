# encoding: utf-8
# frozen_string_literal: true

source 'https://gems.ruby-china.org'

gemspec

gem 'rake', '~> 11.0'
gem 'rspec', '~> 3.4.0'
gem 'yard', '~> 0.8'
gem 'simplecov', '~> 0.10'
gem 'pry'

group :test do
  gem 'codeclimate-test-reporter', require: false
  gem 'safe_yaml', require: false
  gem 'webmock', require: false
end

local_gemfile = 'Gemfile.local'
eval_gemfile local_gemfile if File.exist?(local_gemfile)
