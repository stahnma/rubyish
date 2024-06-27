# Rubyish

This is a project to play with Ruby and Flox and see if we can get an environment where most ruby tools work.

# Global
Path for the bundle

# Mac
Therubyracer library symbol missing (but this might be totally dumb and not needed)

# Linux
1. crti.o issue resolved with glibc on linux
eventmachine  / thin  not working
fast_jsonparser not working

# Notes
- Look at miniracter instead of rubyracer
- I need to file enhancement for cross platform stuff

# The goal

Get the top 15 or so rubygems that have Native Extensions building with Flox.
See `Gemfile` for the list (the commented out ones are broken still)

# The test
The `test.rb` file tries to load/require all the gem to ensure they at least can be `required`.

    bundle exec ./test.rb
