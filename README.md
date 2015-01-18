# spring-commands-thor

This gem implements the `thor` command for
[Spring](https://github.com/jonleighton/spring).

## Usage

Add to your Gemfile:

``` ruby
gem "spring-commands-thor", group: :development
```

If you're using spring binstubs, run `bundle exec spring binstub thor` to generate `bin/thor`.
Then run `spring stop` to pick up the changes.

## Note
This is a stripped-down clone of (https://github.com/jonleighton/spring-commands-rspec) for thor.
