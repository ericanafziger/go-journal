# GoJournal

### By Erica Nafziger and Lina Shadrach

## Description
This project was designed to display basic CRUD functionality with a program with similar functionality to KickStarter or Go Fund Me using AngularJS. Users can add postings, 'back' projects they care about, and delete project. 
This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.26.

## View Project 
* Clone repo from github
* cd go-journal in terminal to navigate to project directory
* Follow 'Adding Firebase Configuration' instructions below to link project to database
* Run npm install in the terminal
* Run bower install in the terminal
* Finall follow 'Development server' instructions below

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Adding Firebase Configuration
* Create file named api-keys.ts in /src/app/
* Visit firebase.google.com to set up a firebase account
* Create new project
* Click "Add Firebase to your web app" button
* Include your given credentials with the following format in your api-keys.ts file:

* export var masterFirebaseConfig = {
    * apiKey: "xxxx",
    * authDomain: "xxxx.firebaseapp.com",
    * databaseURL: "https://xxxx.firebaseio.com",
    * storageBucket: "xxxx.appspot.com",
    * messagingSenderId: "xxxx" };
* On the left hand menu navigate to Database and then the tab rules
* Change both read and write rules to the boolean true
* Navigate to the Data tab and click on the three dropdown dots
* Choose import JSON and upload the sample-albums.json file from the project directory to get started using the app

## Deploying to GitHub Pages

Run `ng github-pages:deploy` to deploy to GitHub Pages.

### License

*MIT*
Copyright (c) 2017 **Erica Nafziger and Lina Shadrach**
