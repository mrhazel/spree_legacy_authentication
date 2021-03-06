SpreeLegacyAuthentication
=========================

ZenCart Legacy Authentication

Installation
------------

Add spree_legacy_authentication to your Gemfile:

```ruby
gem 'spree_legacy_authentication'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_legacy_authentication:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_legacy_authentication/factories'
```

Copyright (c) 2014 [name of extension creator], released under the New BSD License
