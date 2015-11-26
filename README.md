# Angular & Express Seed Application
This repository helps you save lot of time and efforts bootstrapping and configuring the environment
of a new Angular and Express project.

If you're one of the following, then you definitely need to use this seed repo:
- If you're new to Angular and need a sample working application
- If you're familiar with Angular, and create many prototypes and proof of concepts
- If you're about to create medium size project and need solid base to start from
- If you're busy man, and need to save lot of time, it only takes few seconds to get your hands dirty with what really matters to you!

I tried here to include most common libraries, check "Stack" section.

## Seed
###It's very easy to start your own project using this seed repo:
1) Download seed.sh here: https://github.com/AbuMuslimAmr/angular-express-seed/blob/master/seed.sh
2) place this shell script wherever you need your project on your PC
3) grant this script executable permission, run: "chmod u+x seed.sh" (learn more)
4) create a new repository on your github or bitbucket
5) configure seed.sh using vim or any other text editor
6) run the script: bash seed.sh
7) tada! you have got everything ready for you, just start getting your hands dirty.
 
###Sample configurations:
NEW_PROJ_REMOTE=https://github.com/AbuMuslimAmr/test-clone.git
NEW_PROJ_NAME=test-clone
INITIAL_COMMIT_MESSAGE="Initial commit"
FIND_KEYS=('ngApp' 'other-key-word')
REPLACE_KEYS=('newNgApp' 'other-value')

## Stack
- Bootstrap
- Express
- Angular
  - restangular
  - ui.bootstrap
  - ui.router
  - lodash
- Grunt
  - es6 (babel)
  - concat
  - jshint
  - less
  - watch

## Install
If you don't have grunt-cli installed:<br>
```
npm install -g grunt-cli
```

then,

```
git clone git@github.com:AbuMuslimAmr/angular-express-seed.git
cd <project-root>
sudo npm install
bower install
```

## Build
```
grunt
```

## Run express server:
open new terminal tab:<br>
```
node express
```
<br>
You can configure port from 'express/express-config.js'

App then should be up and running on port 3000 (by default).