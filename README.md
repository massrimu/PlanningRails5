# This is Rails 5.2.3 Application upgrade from Rails 4.2
Install the required ruby version using rbenv
```
rbenv install 2.6.4
gem install bundler

# Change the rails version
# Gemfile
gem 'rails', '4.2.0'
# To
gem 'rails', '5.2.3'

```
[A step by step guide to upgrade rails 4 application to rails 5
](https://deepakmahakale.in/blog/2020/07/04/guide-to-upgrade-rails-application.html)

## Planning a Greater Greater Lansing
Jump Start a Rails App developement. Fork this. Rails + Devise + Paperclip setup.

## This is built on RailsJumpStart. Pre-installed Gems:

```
gem 'devise'
gem 'slim'
gem 'paperclip'
gem 'bootstrap-sass'
gem 'simple_form'
```

Paperclip is installed and pre-configured to upload avatar for users.

Steps to implement:

git clone https://github.com/jmonberg/planning.git

cd planning

bundle install

rake db:migrate

add config.secret_key = 'value' to db/initializers/devise.rb

get the config/secrets.yml file

rails generate simple_form:installr

## TODO
Update gems for security issues.




