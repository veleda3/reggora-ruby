# Reggora

## Welcome to `Reggora` gem!
### `Reggora` gem works for `Lender` and `Vendor` APIs supported by [Reggora](https://sandbox.reggora.io/).

![ruby_ver](https://img.shields.io/badge/Requires-Ruby%202.4%2B-red)
![curr_ver](https://img.shields.io/badge/Version-2.1.0-blue)

## Installation


```ruby
gem 'reggora'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install reggora

## Usage

- Initializing Library

  `@lender_api_client = Reggora::LenderApiClient.new(user_name, password, int_token)`

- Make request

  `@_user = Reggora::User.new(@lender_api_client)`

  `@_user.find(user_id)`


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/Reggora/reggora-ruby. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Contributors
|Contributor|
| :--: |
|[![dansteren_pic](https://avatars1.githubusercontent.com/u/5455419?s=120&v=4)](https://github.com/dansteren) |
|[@dansteren](https://github.com/dansteren)<br>[@Simple Nexus](https://github.com/SimpleNexus)|


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Reggora project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/Reggora/reggora-ruby/blob/master/CODE_OF_CONDUCT.md).
