# chess
Multiplayer chess server implemented with Node.js

Server folder contains two files:
- chessgame.js contains the fundamental chess boardstate used by the Node server
- server.js maintains connections between clients and chess boardstates. Currently a WIP, only maintains one boardstate between all client connections.

Client folder contains HTML file for clients to connect to.
