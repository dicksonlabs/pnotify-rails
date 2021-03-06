# Pines Notify for Rails

Pines Notify is a JavaScript notification plugin, developed by Hunter Perrin as part of Pines. It is designed to provide an unparalleled level of flexibility, while still being very easy to implement and use.

See the [Pines Notify home page](http://pinesframework.org/pnotify/) for more information and examples.

## Requirements

See the [PNotify Github page](https://github.com/sciactive/pnotify#requirements) for more details.

## Installation

Add this line to your application's Gemfile:

    gem 'pnotify-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pnotify-rails

## Using the javascripts

Require `pnotify` in your `app/assets/javascripts/application.js` file:

    //= require pnotify

## Using the default styles

Add the following to your app/assets/stylesheets/application.css file:

    *= require jquery.pnotify.default

And if you require the default Pines icon styles, add the following as well:

    *= require jquery.pnotify.default.icons

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
