# MERN-Bus_Seat_Booking_system
This repository is for seat booking system for the buses. Used MERN

# MFRP (My First Real Project) 
A Bus ticket booking application made using MERN Stack (MongoDB, Express js, React js, Node js)

The Bus ticket application is composed of the following Features:

# Front-End
Sign-In & Sign-Up Pages.

Uses Token based system, so only registered users can access the website passport js.

Password hashing using passport js.

Has a profile page, which will display all information about the signed in user.

List of cities for users to choose from (starting city & destination city).

Getting list of bus's of different companies with various details.

Seat selection page has a very user friendly environment, which also generates dynamic forms for storing data's of passengers.

Has a Confirmation page, which gets a debit card data using react-credit-cards. This version of the application does not include handling the payment process.

Final page has a ticket displaying component, it displays all passenger data and also generates a random number as a transaction ID.

# Back-End
Uses Express js based application for the backend process.

Uses MongoDB atlas for storing the collections.

Uses passport js for authenticating user and token based system.

Uses passport js for hashing the password before sending the data to the cloud.

This version does not support dynamic seat data being stored from cloud.

# Developed With
Visual Studio Code - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring
Node.js - Javascript runtime
React - A javascript library for building user interfaces
Babel - A transpiler for javascript
Webpack - A module bundler
SCSS - A css metalanguage
Bootstrap 4 - Bootstrap is an open source toolkit for developing with HTML, CSS, and JS
Axios - Promise based HTTP client for the browser and node.js
Express js - Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
MongoDB atlas - MongoDB Atlas is the global cloud database service for modern applications.
Passport Js - Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application.

# Available Scripts
In the project directory, you can run:

# yarn start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

# yarn test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

# yarn build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

# yarn eject
Note: this is a one-way operation. Once you eject, you can’t go back!

If you aren’t satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

# Learn More
You can learn more in the Create React App documentation.

To learn React, check out the React documentation.

Code Splitting
This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

Analyzing the Bundle Size
This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

Making a Progressive Web App
This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

Advanced Configuration
This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

Deployment
This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

yarn build fails to minify
This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
