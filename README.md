# Block Boost server

A tiny relay so Block Boost players can see each other online when the game runs outside Claude
(for example on itch.io). It passes small "presence" messages between players in the same room and stores nothing.

Run locally: `npm install` then `npm start` (listens on port 8787, or `$PORT`).

Deploy on Render: New > Web Service > this repo > Language Node > Build `npm install` > Start `npm start` > Free.
Then put the `wss://...onrender.com` address into the game's `ONLINE_SERVER` setting.
