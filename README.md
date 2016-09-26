# Passport && sails js

a [Sails](http://sailsjs.org) application

# Prerequisites
node v6
sails 0.12.4

# Install
sails lift

# Instructions
### http://localhost:1337/post - the very first time it should redirect you to the login page
It should go to the main page "http://localhost:1337/"

### go to http://localhost:1337/signup for signing up
You can register the user that you want to use in the system
### go to http://localhost:1337/login for logging in
{
  "message": "Logged In Successfully",
  "user": {
    "email": "admin@gmail.com",
    "createdAt": "2016-09-26T18:32:57.520Z",
    "id": 1
  }
}

### now you should be able to access this page http://localhost:1337/post, even though it's going to show you just an empty array (there aren't any posts yet)
[]
### go to http://localhost:1337/logout for logging out

## Ref
http://iliketomatoes.com/implement-passport-js-authentication-with-sails-js-0-10-2/

