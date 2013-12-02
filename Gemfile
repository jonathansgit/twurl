source 'https://rubygems.org'

gem 'jruby-openssl', :platforms => :jruby
gem 'rake'

group :test do
  gem 'coveralls', :require => false
  gem 'mime-types', '~> 1.25', :platforms => :ruby_18
  gem 'minitest', '>= 5'
  gem 'rr', '>= 1.1'
  gem 'simplecov', :require => false
end

platforms :rbx do
  gem 'rubinius-coverage', '~> 2.0'
  gem 'rubysl-base64', '~> 2.0'
  gem 'rubysl-net-http', '~> 2.0'
end

gemspec
