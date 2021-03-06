# React Native Server

A quick Node/Express server boilerplate for your React Native app.

To start using this boilerplate, fork this project. 

Then click on "Clone or download" and copy the repository link. 

Open your terminal window on your computer and navigate to an area where you would like this project saved.

Type ```git clone [the repository url you copied]```. Example on next line.

It should look something like this, ```git clone https://github.com/ericdfanning/ReactNodeExpressBoilerplate.git```. Except instead of 'ericdfanning', it will show the name of your github profile.

Once it is done cloning, type ```cd ReactNodeExpressBoilerplate``` to go into the project folder.

If using node,type ```npm install``` to install all the dependencies this project needs in order to work.

Then to start the server on your local machine, type ```npm start``` into your terminal window. If it starts without error it should say "now listening on port 8000". If it gives the error ```Error: listen EADDRINUSE :::8000```, then that means you already have another program running on port '8000'. You can either stop that other program, or change the port number in this app by going to server.js and changing the port number to any 4 digit number between 3000 - 9000.