SimpleWebRTCVideoChat
=====================

Install node.js on your server
npm install express@2.5.2
npm install webrtc.io

Edit dev.html to point to your server and port for the 
websocket to the node server "ws://www.walking-productions.com:8001/"

Run the server:
node server.js

The dev.html and webrtc.io file need to be on a server running on the same machine but a different port (80 usually works)

Load the dev.html file and away you go!
