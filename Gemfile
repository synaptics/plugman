source = "http://rubygems.org"

gemspec

group :development do
  gem "rspec"
  gem "guard"
  gem "guard-rspec"

  if RUBY_PLATFORM.downcase.include?("darwin")
    gem 'rb-fsevent'
    gem 'growl_notify'
  end
end