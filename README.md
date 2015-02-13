# Shellject

Store your secret environment variables with GPGME, and inject them into your current shell when needed.

[![Build Status](https://travis-ci.org/sergei-matheson/shellject.svg?branch=master)](https://travis-ci.org/sergei-matheson/shellject)
[![Code Climate](https://codeclimate.com/github/sergei-matheson/shellject/badges/gpa.svg)](https://codeclimate.com/github/sergei-matheson/shellject)
[![Test Coverage](https://codeclimate.com/github/sergei-matheson/shellject/badges/coverage.svg)](https://codeclimate.com/github/sergei-matheson/shellject)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'shellject'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install shellject

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment. Run `bundle exec shellject` to use the code located in this directory, ignoring other installed copies of this gem.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/sergei-matheson/shellject/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Test your changes (`bundle exec rake`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request
