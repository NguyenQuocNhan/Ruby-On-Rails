# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# this is resolve error code when run server with my windows 10

* add below to "Gemfile": ---------------------------

  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem 'tzinfo-data'
  gem 'tzinfo'
  gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

  => commend line: rails server
  => localhost:3000

* -------------------------------------------