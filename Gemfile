source 'https://rubygems.org'

gem 'sqlite3', '~> 1.3.6', platforms: [:ruby]

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter'
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubysl-test-unit'
  gem 'rubinius-developer_tools'
end

rails = ENV['RAILS'] || '~> 5.2.0'

gem 'rails', rails

# Specify your gem's dependencies in paranoia.gemspec
gemspec
