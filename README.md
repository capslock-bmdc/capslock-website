# Capslock-Website


## Install
1. Follow the [instructions on the jekyll site](https://jekyllrb.com/docs/installation/) on how to install ruby, rubyGems GCC, make any jekyll.
2. Got to [rubys site](https://rubyinstaller.org/) and install ruby, the in the `cmd` run `gem install jekyll bundler`.

## Setup
- clone the repo
- `cd` into the repo
- run in the cmd `bundle install`

## Run
- run `bundle exec jekyll serve --open-url --livereload --config _config_dev.yml`

## Common errors
- on run `bundle exec...` error: `Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'`, you can remove `--livereload` or find check [this issue](https://github.com/oneclick/rubyinstaller2/issues/96#issuecomment-434619796).
