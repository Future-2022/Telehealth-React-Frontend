# README #

This README document all the steps are necessary to get your application up and running.


### how to run the project locally?

* you have to update this 2 files:
* src > services > api.js: The line 2: baseURL: process.env.REACT_APP_API_BASE_URL || 'https://localhost:44352/api', shoud not be commented
* public > signalR > notification.js: The line 6: localhost = true;


### How to run the project?

* `npm install`
* /public/signalR/notification.js > line 5 change localhost = true
* /src/services.api.js > uncomment line 2 to execute on localhost

Install dependencies.

* `npm start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

* `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!


