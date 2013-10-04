README
======

This project is ready cloning and use, but is not yet a proper skeleton and
does not yet have full test coverage. It's a work in progress with pieces being
pulled in from other projects and updated to Rails 4.

The goal of this skeleton project is to provide rock solid security and performance
without significant configuration or rewriting code.

After cloning...

1. Generate new security tokens
2. Search and replace `ExampleApp` with your app name
3. Edit RegistrationController and migrations to customize user fields as needed

```bash
# OSX
gem install rb-fsevent
gem install zeus
gem install guard
```

```bash
zeus start
bundle exec guard
```

Demo
====

Twitter demo app credentials uses a callback url of http://0.0.0.0:3000/auth/twitter/callback


TODO
====

* add support for username
* Install Devise Security Extension https://github.com/phatworx/devise_security_extension
* Review config/initializers/devise.rb
* Convert to lazy registration https://github.com/mwlang/lazy_registration_demos


Philosophy
==========

BDD is fun. Best practices increase productivity. Setting up frameworks is a waste of time.
