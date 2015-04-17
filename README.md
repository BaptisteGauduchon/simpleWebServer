# simpleWebServer
Dead simple web server that I use to fast-deploy static website / web application, mostly locally.
It's written using the awesome **node.js + express.js** combo. Logging done via *morgan*.

## Usage :
1. download & extract repository locally
2. in terminal : `npm install && npm start` (web server started at `localhost:80`)
3. in browser : type in `localhost`

*prerequist : node.js & NPM installed*

*if you get **EADDRINUSE** error, check that you don't already have something running on port 80.*

## How it work :
Simply copy-paste your website / application into the "public" folder. You can safely override the dummy files / folders in there.

## Disclaimer :
this is **NOT** intended for anything other than dev purpose, as this is **NOT SECURE AT ALL**.
If you want more, you should move to SSL / TLS secured web server.
GIYF.
