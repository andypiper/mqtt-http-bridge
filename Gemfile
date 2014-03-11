source "https://rubygems.org"

# Note: also see .rbenv-version
ruby "1.9.3"
#ruby "2.1.0"

gem 'sinatra'
gem 'mqtt', :git => 'git://github.com/njh/ruby-mqtt.git'
#gem 'mqtt', '>=0.1.0'
gem 'thin'
gem 'psych'
gem 'newrelic_rpm'

group :development do
  gem 'shotgun'
  gem 'rake'
end

group :test do
  gem 'rspec', '>=2.7.0'
  gem 'rack-test', :require => 'rack/test'
end
