source "https://rubygems.org"
gem 'em-http-request'
gem 'em-synchrony'

group :development, :test do
  gem 'rake'
  gem 'mongoid', '2.6.0'
  gem 'bson_ext', :platforms => :ruby

  gem 'rails'

  platforms :jruby do
  	gem 'jruby-openssl'
  end
end

gemspec
