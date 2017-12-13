# Real-Time-Chat-App-With-NodeJS
Real time chat app with nodeJS (express, socket) that support multiple clients

Initializing an Express app:
-Install Node.js https://nodejs.org/en/
-Install Express https://expressjs.com/
-Install Express Generator https://expressjs.com/en/starter/generator.html
--Follow the instruction on this page to generate an express project and when creating a express project use '-e' in the option to use EJS engine (default is Jade)
--This will generate a bunch of files including app.js and index.ejs

Create the real time Chat app:
-I included my app.js and index.ejs in this repository with detail comments which you can use
-Please create a free account in mlab to replace the 'dbUrl' string in app.js
-Disable the 'app.set('port', port);' in the www bin if you are using my app.js code as it has its own server listenner code

Test:
-Open 'http://localhost:8000/' in two browser tabs (8000 is the port I used)
-Now you can chat between the tabs and all the messages will be synced in real time

