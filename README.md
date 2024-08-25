# fakeStackOverflow
Instructions to setup and run project

2-Person Group Project (Similar levels of Collaboration & Effort put in)

Project Background Information

"fake Stack Overflow" is best viewed in a 1920 x 1080 (or larger) screen resolution monitor.

Open a terminal and run: "mongod". Then open another terminal and pull the project code.

Once project has been cloned and in the project directory, to set up the database run command of the form: node server/init.js mongodb://127.0.0.1:27017/fake_so admin@gmail.com Pass@1234

You are running node script at server/ called init.js with mongodb argument to create database fake_so and run default port 27017 with next 2 arguments being admin email and password (you can modify the given email and password to your liking).

Then, run the server with the command: nodemon server/server.js

Now, open another terminal and navigate to project directory. Change directory to client/ using "cd client/" Now run the front end using the command: npm start
