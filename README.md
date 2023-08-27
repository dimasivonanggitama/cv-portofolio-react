# attendance-system-web-front-end

## What i did:
1. mkdir "CV and Portofolio"
2. cd "CV and Portofolio"
3. npx create-react-app cv-portofolio-react
4. cd cv-portofolio-react
5. [Github website] Create new repository on Github Website (without any options): cv-portofolio-react
6. git remote add origin https://github.com/dimasivonanggitama/cv-portofolio-react.git
7. git pull origin main
8. git add .
9. git commit -m "Initial commit"
10. git push origin main
11. git checkout -b development
12. npm start
13. [Installed dependencies section]
14. [index.js] Wrap with <ChakraProvider> on index.js
15. [App.js] import { BrowserRouter as Router, Routes, Route } from "react-router-dom";
16. [App.js] Wrap with (without "&emsp;"):
    &emsp;<Router>
    &emsp;&emsp;<Routes>
    &emsp;&emsp;&emsp;<Route path="/" element={<PageComponentName/>} />
    &emsp;&emsp;</Routes>
    &emsp;<Router>

## Installed dependecies
1. npm install react-router-dom
2. npm install @chakra-ui/react @emotion/react @emotion/styled framer-motion
3. npm install react-icons --save

## Version code:
• Preparation:\
&emsp;FE-PREP = Preparation\
&emsp;FE-ROUT = App Routes\
&emsp;FE-READ = README.md for frontend/client side

• Components:\
&emsp;FE-IMRO = Rounded Image Profile\
&emsp;FE-STEP = Preset Stepper/Tracking log

• Sections:\
&emsp;FE-LEFT = Left Section\
&emsp;FE-RIGH = Right Section

• Pages:\
&emsp;FE-MAIN = Main CV-Portofolio Page

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

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
