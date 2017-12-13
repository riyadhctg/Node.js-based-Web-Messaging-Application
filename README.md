# Real-Time-Chat-App-With-NodeJS
Real time chat app with nodeJS (express, socket) that support multiple clients

<h2>Initializing an Express app:</h2>
<ul>
 <li>Install Node.js https://nodejs.org/en/</li>
<li>Install Express https://expressjs.com/</li>
<li>Install Express Generator https://expressjs.com/en/starter/generator.html</li>
<li>Follow the instruction on this page to generate an express project and when creating a express project use '-e' in the option to use EJS engine (default is Jade)</li>
<li>This will generate a bunch of files including app.js and index.ejs</li>
 </ul>

<h2>Create the real time Chat app:</h2>
-I included my app.js and index.ejs in this repository with detail comments which you can use
-Please create a free account in mlab to replace the 'dbUrl' string in app.js
-Disable the 'app.set('port', port);' in the www bin if you are using my app.js code as it has its own server listenner code

<h2>Test:</h2>
-Open 'http://localhost:8000/' in two browser tabs (8000 is the port I used)
-Now you can chat between the tabs and all the messages will be synced in real time

