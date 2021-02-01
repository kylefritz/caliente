source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'bootstrap', '~> 5.0.0.beta1'
gem 'hotwire-rails' # Hotwire is an alternative approach to building modern web applications without using much JavaScript by sending HTML instead of JSON over the wire
gem 'jbuilder', '~> 2.7' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'pg', '~> 1.1' # Use postgresql as the database for Active Record
gem 'puma', '~> 5.0' # Use Puma as the app server
gem 'rails', '~> 6.1.1' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rexml' # required for ruby 3+, https://stackoverflow.com/questions/65479863/rails-6-1-what-is-preventing-tests-from-running
gem 'sass-rails', '>= 6' # Use SCSS for stylesheets

group :development, :test do
  gem 'byebug' # Call 'byebug' anywhere in the code to stop execution and get a debugger console
end

group :development do
  gem 'listen', '~> 3.3'  
  # gem 'rack-mini-profiler', '~> 2.0' # Display performance information such as SQL time and flame graphs for each request in your browser.
  gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'web-console', '>= 4.1.0' # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
end

group :test do  
  gem 'capybara', '>= 3.26' # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  gem 'webdrivers' # Easy installation and use of web drivers to run system tests with browsers
end
