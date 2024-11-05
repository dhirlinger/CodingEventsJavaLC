DESCRIPTION

Coding Events is a Collection of Coding Events. Each event includes event name, description, event category, and tags. Events, event categories, and tags can be added or deleted by the user. 

===========================

CURRENT STATE

The app is currently a work in progress and with no real thought for frontend or UI design. 

===========================

FUTURE PLANS

In addition to an upgrade on the frontend design several functional upgrades are needed. These upgrades are listed below: 

- Each event needs a date and time.
- After user class is added the app will need a boolean to determine if a user is signed in
- and user id of the current signed in user should be used to grab addtional data to display such as - greeting, user only options like viewing, adding, editing, and deleting user parameters.
  
- A user class is needed with the following parameters
  
PK id 

First Name stored in a user name class / name id - one to one

Last Name stored in a user name class / name id - one to one

Email stored in user email class / one to one user id to email id

Password / stored in a password class / one to one password id to user id

Saved Events - one to many user id to event id 

Description (of user) - String  

Location (of user) stored in user location class / one to many user id to user location id

Image (link) - String
