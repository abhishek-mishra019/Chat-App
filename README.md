# Chat-App

Chat APP
For chat we used nodejs + express as server and on the front-end we used Angular. To send the messages between server and front-end I used socket.io.

Cover some npm commands that we used during the project
On the root level
Command	Explanation

1. npm init	                                        (Can be used to set up a new or existing npm package )
2. npm install cors express nodemon socket.io	      ( Install packages that we are going to use)
3. npm install -g @angular/cli	                    (Install Angular as a global package)
4. ng new client	                                  (Using Angular CLI to create a new project inside our current folder.)
5. npm run serve	                                  (We updated package.json in the root folder and added new command "serve": "nodemon server.js" under scripts property. After this we able to run npm run serve to start our node server)

In the client folder we need to run new terminal

Command	Explanation

1. npm install socket.io-client	                    (To install socket.io for our client app)
2. npm run build	                                  (Need to run this command first time to build Angular project)
3. npm run start	                                  (Start the Angular app)
