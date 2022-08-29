# Licensing Rx-Flappy!

## What is rx-flappy?
Rx-flappy is a simple game inspired by Flappy Bird, a popular game created in 2013.
The game finish if the bird touches a pipe or the ground.

This version use TypeScript with RxJS, a library for reactive programming using Observables.
## Why this repo?
This repo is for licensing under a Free Software License the project shared by NyaGarcia in the [salmorejo.tech, 2021 edition](https://salmorejo.tech/2021) event, called [@NyaGarcía/Rx-Flappy](https://github.com/NyaGarcia/Rx-Flappy).

## How are we going to do that?
There is a central issue, [#1](https://github.com/aulasoftwarelibre/Rx-Flappy/issues/1), with a checklist of the different tasks to accomplish.

We'll open and close different issues for every task, questions, discussions, problems, etc.

### branches
The *master* branch is for the project explanations.

The *gplv3* branch will be the GPLv3+ licensed project, ready to register it to the [GNU Savannah portal](https://savannah.nongnu.org/), and give it back to NyaGarcia if she agree the project changes needed to be GPLv3 licensed.

The *apache2* branch will be the Apache2 licensed project, ready to give it back to NyaGarcia as a non copyleft protected project.

### fork, edit and pull request
If you want to participate, simply take a task, fork the repo, do it and share back your changes by a pull request to the license chosen branch. (currently we are working in a GPLv3 and an Apache2 licensed project version)

## Participate!
Please take it easy, take your time, git's power allows us to fix everything!

Ask, debate and don't be afraid to share your work.

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