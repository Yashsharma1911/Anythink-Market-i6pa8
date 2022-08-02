# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db. [CLICK HERE](https://docs.docker.com/get-docker/) to download Docker

## Development
When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### 1. Make sure you have what you need
To build this website, you will need to have Node >=6 downloaded and installed on your machine. If you don't already have it, you can get it [HERE](https://nodejs.org/en/download/)

### 2. Clone App
To start application you need to clone this repo first, run the following command to clone
```bash
git clone https://github.com/ObelusFamily/Anythink-Market-i6pa8.git
```

### 3. Start Docker
You can start development environment in docker. Also you can verify docker is ready by running the following commands in your terminal: ```docker -v``` and ```docker-compose -v``` 

Then, ***run ```docker-compose up``` from the project root directory*** to load Anythink's backend and frontend and to start the application

### 4. Check

#### Check backend
If Docker is working correctly, the backend should be running and able to connect to your local database.
Let's test this by pointing your browser to http://localhost:3000/api/ping

```bash
{"msg":"Pong! Seems like Everythink is working, great job!"}
```

If this message will come mean your backend is working fine.

#### Check frontend
To check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

Also, ***you can use ```docker exec``` to run*** commands on a running container.

## You are all done
It looks like your environment is ready! 😀

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact me
Website: [https://yashsharma.netlify.app/](https://yashsharma.netlify.app/)

Email: yashsharma2572@gmail.com
