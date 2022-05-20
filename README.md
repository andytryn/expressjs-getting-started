# expressjs-getting-started

A Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started on Heroku with Node.js](https://github.com/heroku/node-js-getting-started).

## Run Locally

```sh
$ git clone https://github.com/andytryn/expressjs-getting-started.git # or clone your own fork
$ cd expressjs-getting-started
$ npm install
$ npm start
```
Your app should now be running on [`localhost:5000`](http://localhost:5000/).

## Structure
```
project
├── app
│   ├── controllers
│   │   ├── api
│   │   │   └── example.js
│   │   └── example.js
│   │
│   ├── public
│   │   ├── javascript
│   │   └── stylesheets
│   │       └── example.css
│   │
│   ├── routes
│   │   ├── api
│   │   │   └── example.js
│   │   └── example.js
│   │
│   └── services
│       └── example.js
│
├── bin
│   └── www <-- HTTP server runner
│
├── config
│   ├── config.json <-- General configurations file
│   └── routes.js <-- General routes
│
├── main.js <-- Main app file
├── tests.js < -- Tests file
├── Procfile < -- Heroku Support
└── package.json
```

## Make from scratch

```sh
$ npx express-generator expressjs-getting-started --view=ejs
```
note: change `expressjs-getting-started` to your name project