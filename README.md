# NS-Budget-Tracker-PWA

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## About

Budget-Tracker is a simple budgeting application that allows a user to manage their basic finances. For this assignment, the original application was converted to a progressive web application by integrating offline functionality and making the application downloadable and used like an app that is downloaded to a device.  

## Table of Contents

- [Made-With](#Made-with)
- [Install](#Install)
- [Notes](#Notes)
- [Application](#Application)
- [Screenshots](#Screenshots)
- [Liscense](#Liscense)
- [Credits](#Credits)
- [Questions](#Questions)

## Made-With

- MongoDB
- Express.js
- Node.js

Packages/Extras

- Mongoose
- Express.js

## Install

After cloning the repo, run "npm i" or "npm install" in the command line to install dependencies.

Node.js and MongoDB are required to run this application

## Notes

* To use the applicaication run npm start in the comand line and go to localhost:3001 in the browser. You can also test the application through the deployed application on heroku.
* You are able to use the application offline. Any information that was added while the application while offline will be stored and submitted once service is returned. This is accomplished throught IndexedDb.
* Additional offline capabilities are accieved through the service-worker. The service-worker.js file allows the application to be stored in cache so that if the user is offline, the application will fetch the data from the cached files. 
* Finally the manifest.json file converts the application into a progressive web app (PWA) and allows the application to be downloaded through a button in the URL and downloaded so that it can be used like an app installed on your device.

## Application

https://ns-budget-tracker-pwa.herokuapp.com/

## Screenshots

Cache

<img width="1431" alt="Screen Shot 2022-08-17 at 8 29 55 PM" src="https://user-images.githubusercontent.com/102773691/185266915-7921efc1-1b3d-4d7a-87f9-18944a9472a2.png">

IndexedDB

<img width="1390" alt="Screen Shot 2022-08-17 at 8 29 35 PM" src="https://user-images.githubusercontent.com/102773691/185266917-72d4568b-ef98-4e83-b764-2e363ab9bb3a.png">
## Liscense

This project is liscensed under the MIT liscense.

## Credits

Made by Nina Siegel

## Questions

For questions, email me at siegel.nina.m@gmail.com

To see more of my work visit https://github.com/nmsiegel1/
