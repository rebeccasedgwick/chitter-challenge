Chitter Challenge
=================

_Write a small Twitter clone that will allow the users to post messages to a public stream._  
[![Build Status](https://travis-ci.org/rebeccasedgwick/chitter-challenge.svg?branch= working-branch)](https://travis-ci.org/rebeccasedgwick/chitter-challenge)  

Features:
----

```
STRAIGHT UP

As a User
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a User
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a User
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a User
So that I can post messages on Chitter as me
I want to sign up for Chitter

HARDER

As a User
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a User
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

ADVANCED

As a User
So that I can stay constantly tapped in to the shouty box of Chitter
I want to receive an email if I am tagged in a Peep
```

Notes on functionality:
------

* You don't have to be logged in to see the peeps.
* Users sign up to chitter with their email, password, name and a username (handle)
* The username and email are unique.
* Peeps (posts to Chitter) have the name of the User and their user handle.

Bonus:
-----

* In order to start a conversation as a User I want to reply to a peep from another User.

And/Or:

* Work on the CSS to make it look good.


Technologies Used:
----
* Sinatra
* Active Record (sinatra-activerecord)
* sqlite3
* Rake

How to install and run tests:
----
* Capybara, Rspec, Rubocop, SimpleCov, Travis CI
