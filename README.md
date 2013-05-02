# fastclick-rails

gem for [fastclick.js](https://github.com/ftlabs/fastclick)

## Installation

Add this line to your application's Gemfile:

    gem 'fastclick-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fastclick-rails

## Usage

Add the follow line in app/assets/javascripts/application.js

    //= require fastclick

Initialize in app/assets/javascripts/foo.js.coffee

    $ ->
      new FastClick(document.body)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
