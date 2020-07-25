# Express React Boilerplate

It is a Boilerplate starter kit for Javascript application with [Express](https://expressjs.com "ExpressJS") in back-end and [React](https://reactjs.org "ReactJS") (Typescript) in front-end.

Back-end is bootstrapped with `express-generator` and front-end is bootstrapped with `create-react-app` typescript option.

front-end and back-end both uses `ESlint` for JavaScript common syntax errors and `Prettier` for style issues and automatically reformats your code to ensure consistent rules are being followed.

***
### Getting Started :zap:

1. Clone the repo -> `git clone https://github.com/rekrus/express-react-boilerplate`
2. Change directory to project -> `cd express-react-boilerplate`
3. Install server dependencies -> `npm install`
4. Install client dependencies -> `cd client && npm install`
5. Create `.env` file in client -> `cp .env.example .env` // (sets react `PORT=5000` and `SKIP_PREFLIGHT_CHECK=true`)
6. Start client and server with -> `npm run app`

Hureyy, There you go :tada:

***
### Available scripts :page_facing_up:

##### `npm run dev`
Runs express server with in `development` mode with using `nodemon`


##### `npm run client:start`
Runs React app in the `development` mode. opens application in the browser.


##### `npm run app`
Runs express and react server at the same time by using `concurrently` package.


##### `npm run lint`
Runs `ESlint` scan for server files and return errors.


##### `npm run lint:fix`
Runs same `ESlint` scan for server but also auto-fixes the errors.


##### `npm run client:lint`
Runs `ESlint` scan command for client (react) files and return errors.


##### `npm run client:lint:fix`
Runs `ESlint` scan command for client files and also auto-fixes the errors.


##### `npm run app:lint`
Runs `ESlint` scan for both server and client files using `concurrently` and returns errors on the console.

***
### License :white_check_mark:
[The MIT License](LICENSE.md)
