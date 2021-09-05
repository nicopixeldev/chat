# Chat Socket

Welcome to my Chat App based on [sockets.io](https://socket.io/),
[node](https://nodejs.org/en/), html and JS.

## Run the Application

👉  [Live App](https://nicopixel-chat.netlify.app/) deployed into netlify (with heroku for server side) 
👉 Run `git clone https://github.com/nicopixel/chat`, `cd chat`, `yarn` or `npm install` and `npm run start` to run the application in http://localhost:3000


## Features

👉 Joining page and select chat based on room name <br/> 👉
[SERVER side](./server/index.js) based on [node](https://nodejs.org/en/),
[express](https://expressjs.com/), and [sockets.io](https://socket.io/) <br/> 👉
[FRONTEND side](./public/js/chat.js) based on html,
[mustache template](https://github.com/janl/mustache.js), and
[sockets.io](https://socket.io/). No React framework involved here <br/> 👉
Share with the chat room your location thanks to
[Navigator interface](https://developer.mozilla.org/en-US/docs/Web/API/Navigator)

## Scripts

-   `npm run start`: run the application in http://localhost:3000
-   `npm run develop`: run the application in http://localhost:3000 in
    development mode with nodemon
-   `npm run check`: check the application looking for errors with eslint
-   `npm run format`: apply code syntax formatting with prettier

## Joining Page

![](./docs/images/chat-joining-room.png) Join form which allows you choose a
public nickname and select the Room to enter. To select an existing room you
must select exactly the same room name.

## Chat Room

![](./docs/images/chat-room.png) This is the main page: the chat room where you
can broadcast messages and share you location with all users in the room
