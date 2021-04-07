# Project: Sample application
> *A twitter like web-app built on rails.*

> *This is the sample application for the [Ruby on Rails Tutorial](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).*

----

## What needs to be done?
This web-app must accomplish the following:
- [x] Able to Sign Up, Sign in and Sign Out.
- [x] Able to edit their profile information.
- [x] Able to make posts with maximum length of 140 chars.
- [x] Able to follow and unfollow other users.
- [x] User is able to see all posts of all users he/she following on homepage.
- [x] Show posts in descending order with respect to time.

----

## Required Gems

**This project was built on Ruby version *2.0.0*.**

Following gems were installed in these versions:

| **Gem Names** |           **Gem**         | **Version** |                      **Use**                     |
| :-----------: |   :-------------------:   | :---------: |          :----------------------------:          |
|     Rails     |           'rails'         |  **4.0.8**  |    *Use for executing and rendering web-app*     |
|     Rake      |           'rake'          | **< 11.0**  |      *Use for common administration tasks*       |
|    SQLite     |          'sqlite3'        |  **1.3.8**  | *Use sqlite3 as the database for Active Record*  |
|   Bootstrap   |      'bootstrap-sass'     | **2.3.2.0** |                *For CSS Styling*                 |
|    BCrypt     |          'bcrypt'         |  **3.1.16** | *Secure hash algorithm for safely storing passwords* |
| Jquery Rails  |        'jquery-rails'     |  **3.0.4**  |      *Use jquery as the JavaScript library*      |
|     Faker     |          'faker'          |  **1.1.2**  |               *Generates dummy users*            |
| Will Paginate |      'will_paginate'      |  **3.0.4**  |             *Use in pagination of users*         |
|       ""      | 'bootstrap-will_paginate' |  **0.0.9**  |                         ""                       |
|  RSpec Rails  |        'rspec-rails'      | **2.13.1**  |                 *Use for testing*                |
|   SASS Rails  |        'sass-rails'       |  **4.0.3**  |             *Use SCSS for stylesheets*           |

You can find all gems in this [Gemfile](https://github.com/JuzerShakir/michael_hartl_sample_app/blob/master/Gemfile).


----

## Execution

Run the following commands to execute locally:

The following will install required version of ruby (make sure [rvm is installed](https://rvm.io/rvm/install).)
```bash
rvm install 2.0.0
```
```bash
rvm use 2.0.0
```
```bash
git clone git@github.com:JuzerShakir/michael_hartl_sample_app.git
```
```bash
cd michael_hartl_sample_app
```
```bash
bundle install
```
```bash
rails db:setup
```
```bash
rails s
```
