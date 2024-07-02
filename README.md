# NPM Project Exercise

The purpose of this exercise is to demonstrate your understanding of how to use npm. Follow the steps below to complete the exercise. Some steps might not be directly gradable, but please do them for your own learning experience.

## Steps to Complete

1. **Create an npm project**

Initialize a new npm project in your working directory:
```bash
   npm init -y
```
2. Install the 'moment' package

Install the moment package to handle date and time formatting: 
```bash
  npm install moment
```
3. Examine the directory structure and effects on package.json

Take a look at the changes in your project directory and the package.json file. Notice the new node_modules folder and the dependencies section in package.json.

4. Delete the node_modules folder and run npm install again

Remove the node_modules folder and reinstall the dependencies:
```bash
   rm -rf node_modules
   npm install
```
5. Create an index.js file and update package.json

A. Create an index.js file in your project root directory and update the package.json file so that npm start will run it:
```bash
   touch index.js
```
B. Update the scripts section in package.json:
```bash
   "scripts": {
     "start": "node index.js"
   }
```
6. Import the 'moment' module in your application

In your index.js file, import the moment module:
```bash
   const moment = require('moment');
```
7. Use 'moment' to output the timestamp

Use moment to output the current timestamp when the response arrives, formatted as h:mm:ss a:
```bash
   console.log(`Current time: ${moment().format('h:mm:ss a')}`);
```
8. Add .gitignore to ignore the node_modules folder

Create a .gitignore file in your project root directory to ignore the node_modules folder:
```bash
   node_modules
```


      

