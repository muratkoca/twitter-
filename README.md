## Implementation

This implementation is based on [Ruby on Rails Tutorial](https://www.railstutorial.org/book).

## Setup

Check out this repository and then,

```console
$ bundle install
$ bundle exec rails db:migrate
$ bundle exec rails server
```

## Features

This application doesn't provide many features in order to keep it simple. Here are the features that it does include:

* See timeline
* Post new tweet
* Follow/Unfollow user

## Used gem

### For template

* slim

### For CSS Style

* bootstrap-sass
* font-awesome-sass

### For testing

* capybara
* factory_girl
* faker
* rspec
* simplecov

### For debugging

* bullet
* pry-byebug
* pry-rails
* web-console



## Test

```console
$ bundle exec rspec
```

## Data reset and sample data creation

```console
$ bundle exec rails db:reset    # Data reset
$ bundle exec rails db:populate # Create sample data
```
