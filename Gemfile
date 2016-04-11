gem 'mail', '~> 2.6', '>= 2.6.3'
# mayor_change.minor_change.patch, ex. 2.6.3
# ~> means any monir changes above mayor_change.minor_change, ex 2.6

source "https://rubygems.org"

gem 'sinatra', '1.4.4'
gem 'hashie'
gem 'octokit', '~>2.0'
gem 'awesome_print', :git => 'https://github.com/michaeldv/awesome_print'

# app environment looks like a symbol
# inside the block, we include the gems specific to that group
# since pry is grouped with :development, it cannot be used in production
# groups help us knwo what gems are needed for what environment

# bundler is used to helps programmers with what gems are needed for project
# Gemfile.lock file notes which specific version of the gem was installed.

#gem in development group as hash argument
gem 'pry', :group => :development

# gem in test group using block syntax
group :test do
  gem "rspec"
end
