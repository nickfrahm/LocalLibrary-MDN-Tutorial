# LocalLibrary MDN Tutorial

This project is walking through using Express-Generator to set up a simple
Express web app that shows the different capabilities of Express that can scale
to make larger and more complicated apps. I will be updating the ReadMe as I
work through it to note what I have learned. I will also be attempting all of
the extra credit assignments that are apart of the tutorial to test myself.

# Day 1

Used express-generator to build a skeleton of an Express app. Walked through
each part of app.js to see what's going on, as well as the bonus of setting up a
test route to /users/cool to display "you're so cool" on the browser from the
response.

# Day 2

Walked through the basics of Mongoose and how it interacts with MongoDB within
an application. Connected a built records into a mongo sandbox db. MongoDB set
up was easy since I've done that before, but haven't really looked at Mongoose +
schema/modeling. The tutorial has you build a very basic schema for book genres,
so I did that. Not very hard. Looking forward to writing my own schemas/models
in other apps.

# Day 3

Walked through setting up the skeletons for the controllers for this
application. I now see one common way MVC apps can be set up in Node.js--by
handling everything in the controller, then using exports.{name} to import it
directly in the route file it needs to be in. This keeps code cleaner and easier
to read.

# Day 4

Read through and did the first half of part 5 for rendering the views leveraging
the routes/controllers we have set up. Also leaarned a little about the async
npm library and saw a few use cases for it when getting data for rendering these
views.
