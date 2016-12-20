# IconateRails
A call to transform your existing icons in a cool trendy way.

[Iconate.js](https://bitshadow.github.io/iconate/) is a tiny performant library for cross-browser icon transformation animations in your projects.

The iconate_rails integrates the Iconate.js with the Rails asset pipeline.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'iconate_rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install iconate_rails

## Usage

### Include chosen javascript assets

Add to your `app/assets/javascripts/application.js` if use with jQuery

    //= require iconate

### Include chosen stylesheet assets

Add to your `app/assets/stylesheets/application.css`

    *= require iconate

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/NishantUpadhyay-BTC/iconate_rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
