# Licensing Rx-Flappy!

## What is rx-flappy?
Rx-flappy is a simple game inspired by Flappy Bird, a popular game created in 2013.
The game finish if the bird touches a pipe or the ground.

This version use TypeScript with RxJS, a library for reactive programming using Observables.
## Why this repo?
This repo branch is for licensing under a Free Software License the project shared by NyaGarcia in the [salmorejo.tech, 2021 edition](https://salmorejo.tech/2021) event, called [@NyaGarcía/Rx-Flappy](https://github.com/NyaGarcia/Rx-Flappy).

We've chosen the GPLv3+ license.

## Run the game
Basic instructions for testing the game!

### You need a npm, nodejs running environment:
easiest way in a GNU/Linux OS, could be using virtual environments:

First creating the python one (you need python virtualenv installed)
```
$ virtualenv .penv
```

Activating it
```
$ source .penv/bin/activate
```

Second, creating the nodejs one with nodeenv.
```
(.penv)$ pip install nodeenv
```
```
(.penv)$ nodeenv .env
```

Activating it
```
(.penv)$ source .env/bin/activate
```

### npm installing and deployment commands

```
(.env)$ npm install
```
```
(.env)$ npm start
```

Application will be running in http://localhost:5000