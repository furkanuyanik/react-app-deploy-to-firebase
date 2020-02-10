# react-app-deploy-to-firebase
How to deploy a React Application to Firebase


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
#### Which Firebase CLI features do you want to set up for this folder? : (Selected Hosting) 
##### ( ) Database
##### ( ) Firestore
##### ( ) Functions
##### (*) Hosting
##### ( ) Storage
##### ( ) Emulators
