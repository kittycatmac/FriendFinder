# Friend Finder Application

# Description
Friend Finder implements friend matching base on the user's responses to a survey of ten questions. The user answers the questions with values from 1 (Strongly Disagree) to 5(Strongly Agree). When the survey is submitted, an existing user record closest the current user's responses is found and returned. The closest set of user answers is defined as the set with the lowest absolute difference for all ten qestions combined.

This application is implemented using Node.js and Express server on the back end and Materialize CSS framework on the front end.

# Demo
Friend Finder is delployed to Heroku. Please take a look here.

# Installation
To install the application follow the instruction below.

git clone git@github.com:kittycatmac/FriendFinder.git
cd friend-finder
npm install

# Running Locally
To run the application locally and access it in your browser, first set the PORT enviroment variable to the value of your choice. Example below.

export PORT=3030 then run Node.js
node server.js

The application will now run locally on PORT, in this case that is port 3030. You can then access it locally from your browser at the URL localhost:PORT.

# Author
Catherine McMillen

# Link
https://kittycatmac.github.io/FriendFinder/