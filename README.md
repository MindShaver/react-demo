# React Demo

### To Get Started -
* Install the latest version of [NodeJS](https://nodejs.org/en/download/)
* Make sure to have [Visual Studio Code](https://code.visualstudio.com/download) installed (or your preferred text editor)
* Clone this repository
* With git bash (or whatever you like to use) perform an npm install
* Navigate to the `src/` folder
* Run the command `nodemon server.js` to start your server

Once you have the server running, we are ready to create our app. I've taken care of the foundation, but if you're curious I'll go over what I've done.

### The Server

Using the npm package `connect` to serve up our static file, node will create the local server on `localhost:5000` and serve `index.html`

### Vendor Folder

The vendor folder contains our library dependancies (Babel, React, ReactDOM).

### Images Folder

Some stock images that line up with what we are getting back from the API.

### Semantic-Dist

This is a style library that will let us bypass 99% of the CSS we'd have to write. It's similar to bootstrap in that you just use classes to style your HTML.