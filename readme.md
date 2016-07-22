
Create a WorkoutLog  directory

create two directories client and server inside of WorkoutLog directory

in command line  cd to wherever WorkoutLog is/lives

when you clone this you will need to add a file called .env in the /server directory

the contents should contain your global constant:

JWT_SECRET=this_is_a_secret


then go to the server directory and run npm install
run the server using node app.js from the server directory

in the /client directory run npm install and bower install
run the http_server using npm start