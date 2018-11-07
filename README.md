[![CircleCI](https://circleci.com/gh/pbstriker38/pronto-blacklist.svg?style=svg)](https://circleci.com/gh/pbstriker38/pronto-blacklist)

# Pronto::Blacklist

Pronto runner to flag strings from a blacklist. [What is Pronto?](https://github.com/prontolabs/pronto)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'pronto-blacklist', require: false
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pronto-blacklist

## Usage

Create the following yaml file in the root of your codebase

`.pronto-blacklist.yml`
```yaml
blacklist
  - word
  - another
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pbstriker38/pronto-blacklist.
