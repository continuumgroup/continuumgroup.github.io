# Continuum Website

## Hacking

To set up your dev environment (assuming you have Ruby and the Bundler gem installed)

    $ bundle install
    $ cd vendor
    $ bundle exec bourbon install
    $ bundle exec neat install

### While Hacking

To watch the Sass files and compile to CSS on change

    $ bundle exec rake watch

### After Hacking

To compile the code for commit (production since it's on Github Pages)

    $ bundle exec rake compile

### Publishing your Hack

To deploy (compile, commit, push to Github Pages)

    $ bundle exec rake deploy
    $ # Or as a shortcut, include the commit message
    $ bundle exec rake deploy["Updated the foo to be bar-compatible"]

