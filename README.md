# react-app-deploy-to-firebase
How to deploy a React Application to Firebase?

![Deployed React App](/screenshot1.png)

## 1. Create a React App
``yarn create react-app example-app``
``cd example-app``

## 2. Install package "firebase-tools"
``npm install -g firebase-tools``

## 3. Login at Firebase account
``firebase login``

## 4. Create a Project from Firebase Console
Sample name "furkan-uyanik" for me.

## 5. Deploy to created React App
``npm run build``
or
``yarn build``

## 6. Run firebase init
``firebase init``

#### Are you ready to proceed? (Y/n) : Yes
#### Which Firebase CLI features do you want to set up for this folder? : (Selected -> Hosting) 
``
() Database
( ) Firestore
( ) Functions
(*) Hosting
( ) Storage
( ) Emulators
``

* Please select an option: (Selected -> Use an existing project)
* Select a default Firebase project for this directory: (Selected -> furkanuyanik-1234)
* What do you want to use as your public directory: build
* Configure as a single-page app (rewrite all urls to /index.html)? (y/N) : No
* File build/index.html already exists. Overwrite? (y/N) : No

## 7. Deploy Firebase
``firebase deploy``


# Deploy Completed!
