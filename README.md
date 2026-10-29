# Declare Online

## Local test
Install Node.js 20+, unzip this project, open a terminal in the `Declare_Online` folder and run:
```bash
npm install
npm start
```
Then open http://localhost:3000.

## Put it online for your friend
1. Create a GitHub repository and upload `package.json`, `server.js`, `README.md`, and the `public` folder.
2. Create a Web Service on Render and connect that repository.
3. Set Build Command to `npm install` and Start Command to `npm start`.
4. Deploy and open the public HTTPS URL.
5. Create a room and send your friend the room code. Both players open the same URL.

Rooms are stored in server memory; a server restart clears active rooms. This starter does not implement reconnect recovery or persistent storage.

## Included
Two players, private hands, room code, live updates, 9-card deal, values (A=1, 6=0, J=11, Q=12, K=13), discard then pickup, matching-rank no-pickup rule, declaration scoring, 100/200/500 score limits.
