# EasyRedisLock

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'easy_redis_lock'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install easy_redis_lock

## Usage

  Easy Usage:
  ```
  EasyRedisLock::GateKeeper.new.with_lock("unique_lock_key") { # code to wrap in the redis lock }
  ```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
