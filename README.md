# devfood-api

Base api for devfood project, developed for a week super full stack 2019 OneBitCode.


##### Requirements:

* [Ruby 2.5](https://www.ruby-lang.org)
* [Rails 5.2](https://rubyonrails.org/) 
* [Postgresql](https://www.postgresql.org/) 
* [Ransak - gem](https://github.com/activerecord-hackery/ransack) 
* [Geocoding - gem](http://www.rubygeocoder.com)

##### Install and run application

Change in the database.yml file the connection data with your postgresql server.

To create your database, simply enter the following commands into the terminal:
```sh
$ db rails: create
```
```sh
$ db rails: migrate
```
The database started to do the following:
```sh
rails s
```