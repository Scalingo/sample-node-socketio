# Sample Node.js application with Socket.IO

This application defines a Node.js application using the Socket.IO framework for WebSocket.

This sample is running on: https://node-socketio.is-easy-on-scalingo.com/

## Deploy via Git

Create an application on https://scalingo.com, then:
```shell
scalingo --app my-app git-setup
git push scalingo master
```

And that's it!

## Deploy via One-Click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://dashboard.scalingo.com/create/app?source=https://github.com/Scalingo/sample-node-socketio#master)

## Running Locally

```shell
docker compose build
docker compose run --rm web npm install
docker compose up
```


## Links

Documentation: https://doc.scalingo.com/languages/nodejs/websocket-web-same-port
