
React front end for WP UP login

Once 'npm install' has been executed you can modify src and run 'npm run build' - place the build folder and it's contents into the 'frontend' folder of the WP plugin.

Then take the filename main.xxxxxxx.js from the build/static/js folder

& Replace the old build file name within WordUP-Login.php at line 18.

After this, you can zip up the frontend folder and WordUP-Login.php file into a zip file called "WordUP-Login.zip" - This can then be uploaded to any WordPress site to be used.

See standard React dev instructions below:



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
