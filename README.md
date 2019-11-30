# capslock-website


## install
1. you can follow the [instructions on the jekyll site](https://jekyllrb.com/docs/installation/) on how to install ruby, rubyGems GCC, make any jekyll.
2. got to [rubys site](https://rubyinstaller.org/) and install ruby, the in the `cmd` run `gem install jekyll bundler`.

## setup
- clone the repo
- `cd` into the repo
- run in the cmd `bundle install`

## run
- run `bundle exec jekyll serve --open-url --livereload --config _config_dev.yml`

## comman errors
- on run `bundle exec...` error: `Unable to load the EventMachine C extension; To use the pure-ruby reactor, require 'em/pure_ruby'`, you can renove `--livereload` or find check [this issue](https://github.com/oneclick/rubyinstaller2/issues/96#issuecomment-434619796)