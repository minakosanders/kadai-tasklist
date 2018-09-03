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
* 

```
user = User.last

task = user.tasks.build
task.content = "test"
task.status = "1"

task = user.tasks.build(content: "test", status: "1")

task.valid?
task.save

task = user.tasks.create(content: "test", status: "1")

```
