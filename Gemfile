source "https://rubygems.org"

group :test do
  gem "rake"
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 4.10.1'
  gem "rspec"
  gem "rspec-puppet"
  gem "puppetlabs_spec_helper"
  gem 'onceover', '>= 3.8.0'
  gem "xmlrpc"
end

group :pre do
  gem "puppet-lint"
end
