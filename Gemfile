source 'https://rubygems.org'


gem 'rails', '4.2.6'
gem 'rails-api', '~>0.4', '>=0.4.0'
gem 'jbuilder', '~>2.0', '>=2.6.0'
gem 'rack-cors', '~>0.4', '>=0.4.0', :require=> 'rack/cors'

group :development do
	gem 'webrick', '~>1.3', '>=1.3.1', :platforms=>[:mingw, :mswin, :x64_mingw, :jruby]
	gem 'spring', '~>2.0', '>=2.0.0'
	gem 'sqlite3'
	gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]	
	# windows require this, otherwise does not work
	gem 'coffee-script-source', '1.8.0'
	gem 'httparty', '~>0.14', '>=0.14.0'
	gem 'byebug', '~>9.0', '>=9.0.6'
end

group :test do
	gem 'rspec-rails', '~>3.0'#, '>=3.5.2'
end

group :production do
	gem 'pg', '~>0.19', '>=0.19.0'
end

gem 'mongoid', '~>5.1', '>=5.1.5'
gem 'puma', '~>3.6', '>=3.6.0'#, :platforms=>:ruby

# To use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', :group => :development

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
