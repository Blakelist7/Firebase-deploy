# Setup

 check Node.js version using `node -v`

`npm install -g firebase-tools`  installs Firebase locally

## Firebase Login

 login into firebase account

`firebase login`

enter your credentials

## For React Projects
### Important

`npm run build`

 It will create a `build` directory with a production build of your app

## Initialise Firebase

 before using this command make sure you first created a project in firebase console

 cd to directory of the project you wish to deploy

`firebase init`

## Main Config Especially for React Projects

What do you want to use as your public directory? build <br>

Configure as a single-page app (rewrite all urls to /index.html)? <br>

File ***build/index.html*** already exists. Overwrite? (y/N) N

## Deploy to Firebase

`firebase deploy`





