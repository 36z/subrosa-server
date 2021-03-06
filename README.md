# Readme

Node.js server code for Subrosa.

### Requirements

* Node.js
* MySQL-compatible server (recommended: MariaDB)
* Redis
* GraphicsMagick
* URL forwaded to port 4000 (nginx will do)

### Setup
1. Clone this repository. 
2. Run `npm install`
3. Import `structure.sql`
4. Set up `config.js` (copy and edit `config.sample.js`)
5. Ensure `tmp/` can be written to by the Node process.
6. Forward `yourhostname/server/` to port 4000 where websockets is listening
7. `node main.js` or `nodejs main.js`

Connect to the server by setting a custom network in Subrosa client (bottom of start screen). You'll need to host the client locally.
