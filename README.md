# react-electron-starter
A starting point if you are creating a React.JS application using create-react-app and Electron.JS

# Setup
- Clone this repository
- Open the ```package.json``` file and edit the ```name``` key to ```<your_project_name>```
- Open the terminal in the project root directory and run the following command: ```npm install```

# Description
- This project is created using create-react-app (https://www.npmjs.com/package/create-react-app) and Electron.JS (https://www.npmjs.com/package/electron)
- Other libraries implemented are concurrently (https://www.npmjs.com/package/concurrently) and wait-on (https://www.npmjs.com/package/wait-on)
- The main Electron.JS process file is located in the public folder of the root directory and the React.JS code resides in the src folder of the root directory.
- react-router-dom (https://www.npmjs.com/package/react-router-dom) has been implemented in the ./src/Router.js file and all the React.JS components reside in the ./src/compoenents folder. A good practice would be to keep all the files for a single component under one folder and that folder should reside in the ./src/components folder.

P.S. This react app is still not ejected and REDUX has not been implemented. Might go for it in the future. :smile: