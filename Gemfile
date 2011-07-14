source 'http://rubygems.org'

gem "spree", :path => File.dirname(__FILE__)

gem 'sqlite3-ruby'

gemspec

group :test do
  gem 'rspec-rails', '= 2.5.0'
  gem 'factory_girl',       :git => 'git://github.com/MGPalmer/factory_girl.git',         :branch => 'modify-factories'
  gem 'factory_girl_rails', :git => 'git://github.com/thoughtbot/factory_girl_rails.git', :tag =>    'v1.1.rc1'
  gem 'rcov'
  gem 'shoulda'
  if RUBY_VERSION < "1.9"
    gem "ruby-debug"
  else
    gem "ruby-debug19"
  end
end

group :cucumber do
  gem 'cucumber-rails'
  gem 'database_cleaner', '= 0.6.7'
  gem 'nokogiri'
  gem 'capybara', '= 0.4.1.2'
  gem 'faker'
  gem 'launchy'

  if RUBY_VERSION < "1.9"
    gem "ruby-debug"
  else
    gem "ruby-debug19"
  end
end
