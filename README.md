# Jogging Tracker App

It is a Ruby on Rails app that allows users to create an account and insert jogging times. There are 3 types uf users:

-normal user: can add jogging times and see a weekly report of the inserted times

-manager: can CRUD users

-admin: can CRUD users and all records

Each time entry when entered has a date, distance, and time.
When displayed, each time entry has average speed.
Filter by dates from-to.
Report on average speed & distance per week.

The password is hashed. Every page has access control so only logged in users can do specific actions.
All actions are done without refreshing the page, using Ajax.

## Getting started
To get started with the app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```
If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
```
<<<<<<< HEAD

![Alt text](screenshots\Captură ecran (159).png?raw=true "Optional Title")
=======
>>>>>>> 53dff7222b3f2d5a4fe4f2bda45473c8aff8c32d
