This easy steps will allow you to start building a ES6 JS app with TDD using Jest. 
In the current vertion we are aiming to test with the --watch -o flag, that runs the test on changed and  uncomited files, so we need a git repo. We are installing the dependencies with the -D flag. This installs them as DevDependencies 


prerequisites: 
-NPM
-Computer Literacy
-Basic git knowledge

Create a repo for the project
Create the corresponding folder in your system and initialize the repository
npm init -y (or without the -y flag if you want to go thru the detailed initialization)
npm install webpack webpack-cli @babel/core @babel/preset-env babel-loader babel-polyfill jest  -D

copy webpack.config.js
copy babel.config.js

Optional: asset managment:
npm install css-loader style-loader file-loader csv-loader xml-loader -D 

webpack entry point is src/app.js
webpack output goes into distr/app.bundle.js