source 'https://rubygems.org'
gemspec

unless ENV['CI']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '~> 1.2.beta', require: false, git: 'https://github.com/hanami/utils.git', branch: 'develop'
gem 'haml'

gem 'hanami-devtools', require: false, git: 'https://github.com/hanami/devtools.git'
