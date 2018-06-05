This application has a front-end powered by React/Redux, and a back-end providing routing and access to a MongoDB database. It's merely a full-CRUD interface for a generic resource. 

To build it, you will need both file systems. 
Add the folllowing to a .env file in the front-end:

API_URL=http://localhost:3000
NODE_ENV=development

And for the back-end:

PORT=3000
MONGODB_URI='mongodb://localhost/somedbname'

Then run MongoDB on your local host so that it's actively listening.
Remember to npm install all the necessary packages on both back and front ends.

At this point, you will be ready to run the back-end server. Use npm or nodemon to get the server running.

If the back-end is running without a problem, you can npm run-script watch the front end, and see if you can access the full CRUD functionality.




