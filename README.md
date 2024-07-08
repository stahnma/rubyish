# Rubyish

This is a project to play with Ruby and Flox and see if we can get an
environment where most ruby tools work.

# The goal

Get the top 15 or so rubygems that have Native Extensions building with Flox.
See `Gemfile` for the list (the commented out ones are broken still)

# Usage

    flox activate
    bundle

# The test

The `test.rb` file tries to load/require all the gem to ensure they at least
can be `required`.

    bundle exec ./test.rb


# Platforms

Tested on Mac aarch64 and Linux x86_64 so far.

# License

MIT
