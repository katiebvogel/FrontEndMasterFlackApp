Using Front End Masters course to create a slack-like application built on Meteor.

There are some differences in the meteor app that I have and the one being used in the year-old F.E.M course.  
There is a main.js file being used for both server and client in the course.  When I init a new instance of meteor, there is already a separate folder for server vs. client.  

I needed to make sure and define my mongo collection in both the server/main.js and in the client/main.js files.
This was for being able to call mongo functions from the browser console.  Ex:  Comments.insert({login: 'katie', ...etc.}).  
^^This is possible because of the package "minimongo" that comes with Meteor.  
