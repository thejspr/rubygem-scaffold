# Gem Intro

This is a basic gem scaffold for making building new gems easier.

## Setup

Rename name `chromarks` to the new gem's name.

    mv lib/chromarks lib/gem_name
    find . -type f -print0 | xargs -0 sed -i 's/Chromarks/GemName/g'
    find . -type f -print0 | xargs -0 sed -i 's/chromarks/gem_name/g'

## Installation

Add this line to your application's Gemfile:

    gem 'chromarks'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install chromarks

## Usage

TODO: Write usage documentation.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
