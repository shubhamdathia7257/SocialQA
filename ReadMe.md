<h1 align="center">
🌐 SOCIALQA
</h1>
<p align="center">
MongoDB, Expressjs, React/Redux, Nodejs
</p>

> SOCIALQA is a fullstack implementation in MERN [MongoDB, Expressjs, React/Redux, Nodejs] is a simple and powerful way to know what questions your audience has and which are most important to the entire group.
No more hand-raising, microphones, or wasting time on off topic questions..

MERN stack is the idea of using Javascript/Node for fullstack web development.

## clone or download
```terminal
$ git clone https://github.com/KrutikaBhatt/SocialQA
$ npm init
```

# Usage (run fullstack app on your machine)

## Prerequisites
- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^14.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

notice, you need client and server runs concurrently in different terminal session, in order to make them talk to each other

## Client-side usage(PORT: 3000)
```terminal
$ cd client   // go to client folder
$ npm i       // npm install packages
$ npm run dev // run it locally

// deployment for client app
$ npm run build // this will compile the react code using webpack and generate a folder called docs in the root level
$ npm run start // this will run the files in docs, this behavior is exactly the same how gh-pages will run your static site
```

## Server-side usage(PORT: 3000)

### Prepare your secret

run the script at the first level:

(You need to add a JWT_SECRET in .env to connect to MongoDB)

```terminal
// in the root level
$ echo "JWT_SECRET=YOUR_JWT_SECRET" >> ./server/src/.env
```

### Start

```terminal
$ npm init       // npm initiate project
$ npm install       // npm install packages
$ npm audit fix       // npm audit fix missing packages
Click on option Split   // Split the terminal
$ cd frontend   // go to frontend folder in one terminal
$ cd backend   // go to backend folder in another terminal
$ npm start // in both the terminal 1st backend and then frontend
```

# Dependencies(tech-stacks)

```terminal
"@sweetalert2/theme-dark": "^5.0.5",
"axios": "^0.21.4",
"bcryptjs": "^2.4.3",
"body-parser": "^1.19.0",
"cors": "^2.8.5",
"express": "^4.17.1",
"jsonwebtoken": "^8.5.1",
"mongoose": "^6.0.7",
"nodemon": "^2.0.13",
"sweetalert2": "^11.1.7"
```

## Standard

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

## BUGs or comments

[Create new Issues](https://github.com/KrutikaBhatt/SocialQA/issues) (preferred)

## Author
[KrutikaBhatt](https://github.com/KrutikaBhatt),
[Aayush-Chheda](https://github.com/Aayush-Chheda),
[shubhamdathia7257](https://github.com/shubhamdathia7257)

### License
[ISC]
