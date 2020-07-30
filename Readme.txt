to start peer server::
peerjs --port 3001

"start": "concurrently --kill-others \"nodemon server.js\" \"peerjs --port 443\""