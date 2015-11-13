# Heroku Buildpack for running rake tasks before the heroku-buildpack-ruby runs

This is basically a bastardized fork of the [heroku-buildpack-ruby](https://github.com/heroku/heroku-buildpack-ruby)
buildpack that will just setup ruby, bundle install and run a rake task.

It's currently hardcoded for i18n:js:export; if you want to change that look in ruby.rb:107 as a starting point.

There is a generic `run_rake_task(name)` method that you can use to run whatever task (or multiple)
you would like.
