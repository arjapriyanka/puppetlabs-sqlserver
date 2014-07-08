source ENV['GEM_SOURCE'] || 'https://rubygems.org'

group :development, :test do
  gem 'mime-types', '<2.0',      :require => false
  gem 'rake',                    :require => false
  gem 'rspec-puppet',            :require => false
  gem 'puppetlabs_spec_helper',  :require => false
  gem 'puppet-lint',             :require => false
  gem 'simplecov',               :require => false
  gem 'rspec', '~> 2.14',        :require => false
  gem 'beaker-rspec',            :require => false
  gem 'pry',                     :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby