source 'http://gems.akitaonrails.com'

gem 'rails', '3.0.7'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

gem "haml-rails", ">= 0.2"
gem "rest-client", :require => "rest_client"
gem "xml-simple", :require => "xmlsimple"
gem 'delayed_job'
gem 'rack-cache', :require => "rack/cache"

group :development do
  gem "watchr"
end

group :development, :test do
  gem "spork"
  gem "factory_girl_rails"
  gem "rspec-rails", ">=2.0.1"
  platforms :mri_18 do
    gem "ruby-debug"
  end
  platforms :mri_19 do
    gem "ruby-debug19", :require => 'ruby-debug'
  end
end

group :production do
  gem "mysql2", "~> 0.2.7"
end
