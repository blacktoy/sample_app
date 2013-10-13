
# Ruby on Rails Tutorial: sample application

This is the sample application for
the [*Ruby on Rails Tutorial*](http://railstutorial.org/)
 by [Michael Hartl](http://michaelhartl.com). Just to finish what I started and then leave it in vain.

Chapter 3:

-Security 

-Static pages

Chapter 4:

-Slightly improve rails taste of ruby

Chapter 5:

-Stylesheets improvement

-Compact stylesheets

-Added Users controller, sign up pages

Chapter 6:

-Create database users

-User validation: character length, email regular expression

-password encryption

Chapter 7:

-User sign up

-avatar

-stylesheets for user

Chapter 8:

-Sessions sign in, sign out

-remember token, cookies

Chapter 9:

-User edit, update, index users, delete user
   
-Adding "option={ size:50}" in app/helpers/users_helpers.rb to pass the test. Based on [stackoverflow question](http://stackoverflow.com/questions/14916144/hartl-ror-chap-9-3-1-spec-test-failure).

-Set "config.assets.compile = .." from "false" to "true" and then run $ RAILS_ENV=production bundle exec rake assets:precompile
 in order javascript render in heroku. Same as seen in css before. [Stackoverflow question](http://stackoverflow.com/questions/12624376/getting-my-images-in-css-to-work-on-rails-and-asset-pipeline-with-upgraded-app-o).
