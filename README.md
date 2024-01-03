# Room Chat Simulator | Code practice

![Example Desktop](./public/example-desktop.png)

This repository is for self-learn websockets tecnology with Node + Socket.io by building a room chat application.
The tecnologies used in this project was **React.js** with **Vite**, **Styled Components** for the frontend and **NodeJS** and **Socket.io** for the backend.

## Deploy project in local enviroment

First you should to connect to a network and execute:

```shell
# After clone this repository

# Run chat server
cd chat-server
npm install # or pnpm install
node app.js
```

After you run the server the terminal show you a local IP, you should update the [](./src/infraestructure/socket.ts) with this IP adress for connect the frontend with the backend.

Now you can run the frontend, create another terminal in the repository directory and execute:

```shell
cd react-chat
npm install # or pnpm install
npm run dev
```
