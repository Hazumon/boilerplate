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

$ rails new library --database=postgresql --skip-turbolinks --skip-test-unit
$ cd library
$ rake db:create
$ rails generate scaffold book author:string title:string
$ rake db:migrate && rake db:rollback && rake db:migrate

* ...
