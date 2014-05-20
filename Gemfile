source 'https://rubygems.org'

gem 'jruby-openssl', :platforms => :jruby
gem 'sawyer', '~> 0.5'

group :development do
  gem 'awesome_print', :require => 'ap'
  gem 'yard', '~> 0.8.7'
  gem 'rake'
end

group :test do
  # gem 'json', '~> 1.7', :platforms => [:jruby] look TODO needed?
  gem 'minitest'
  gem 'vcr', '~> 2.4'
  gem 'netrc', '~> 0.7.7'
  gem 'simplecov', '~> 0.7.1', :require => false
end

gemspec