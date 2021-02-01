# Homework-14
Reverse Engineering Authentication

  I. Files and folders
    A. CONFIG
      1.	MIDDLEWARE: serves to restrict access to content on the application because the user is not signed in. 
      2.	config.json: facilities connection to the server
      3.	passport.js: utilizes javascript to communicate that app will utilize user e-mail address and password to sign into the application
    B. MODELS
      1.	index.js: patches user database info to the application
      2.	user.js { requires "bcrypt" for password hashing. this makes our database secure even if compromised. Here we have JS that defines what is stored on our database };
    C. ROUTES
      1.	api-routes.js { contains routes for signing in, logging out and getting users specific data to be displayed client side };
      2.	html-routes.js { routes that check whether user is signed in, whether user already has account etc and sends them to the correct html page };
      3.	package.json { contains all package info, node modules used, version info etc };
      4.	server.js { requires packages, sets up PORT, creates express and middleware, creates routes and syncs database / logs message in terminal on successful connection to server };


