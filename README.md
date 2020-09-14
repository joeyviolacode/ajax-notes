# Notify

## Description

This was a project I worked on at Momentum.  It uses a simple database to store notes.  Everything is done on the front end with JS, though I used an "object" for the notes themselves.  Since meeting the base specs was straightforward, I played around a lot with different ways of trying to do things.

## Getting started

This application uses [json-server](https://github.com/typicode/json-server) for it's API. To make sure it is installed, you will need to run the following commands:

```sh
npm install
cp sample-db.json db.json
```

To run json-server, run the following command:

```sh
npm start
```

This will start json-server and a web server. It should open a browser window at the same time. You will need to leave this running while you're using the app.

The URL for the app is `http://localhost:8080`.

The URL for the API is `http://localhost:3000/notes/`.
