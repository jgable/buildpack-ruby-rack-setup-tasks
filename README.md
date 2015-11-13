# Heroku Buildpack for running rake tasks before the heroku-buildpack-ruby runs

This is basically a bastardized fork of the [heroku-buildpack-ruby](https://github.com/heroku/heroku-buildpack-ruby)
buildpack that will just setup ruby, bundle install and run a rake task.
