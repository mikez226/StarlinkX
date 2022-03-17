## Starlink

![starlink-demo](https://user-images.githubusercontent.com/50295329/158712899-8f883817-3470-461b-aeae-3db06de58738.gif)

### Project Description

Ready for a space adventure? Starlink is a React.js project to track satellites in real-time based on geo-location. Users can enter parameters including longtitude and latitude to find all matched satellites, and then select one or a few satellites to view their animated trajectory on a world map for a custom duration. The real-time satellite tracking functionality is enabled by [N2YO.com](https://www.n2yo.com/).

### Technical Details

A lightweight frontend project based on **React.js**, Starlink uses **Ant Design** for user-friendly UI components and **D3** for dynamic satellite visualization. It also uses the **Axios** library to make AJAX requests and **create-react-app-buildpack** to deal with CORS issues. It is now deployed on **Heroku** and served via **Nginx** for better stability.

The app is bootstrapped using **create-react-app** boilerplate. The React component layout diagram is illustrated as below:
![component-diagram](https://user-images.githubusercontent.com/50295329/158712969-479d29f3-f2bb-4c09-ae81-199b53575313.png)

### How to Use
1. Visit the [Starlink website](https://starlink521.herokuapp.com/), enter all the parameter settings on the upper-left panel and click "Find Nearby Satellite". If you have no clue about the settings, feel free to use the example settings in the table below.

| Parameter | Unit | Range | Example |
| :----: | :----: | :----: | :----: |
| Longtitude | degree | -180 - 180 | 50 |
| Latitude | degree | -90 - 90 | 60 |
| Elevation | meter | -413 - 8850 | 2000 |
| Altitude | degree | 0 - 90 | 80 |
| Duration | second | 0 - 90 | 20 |

2. Select the satellites you want to see on the bottom-left panel, click "Track on the map" and wait for the animation to load. Notice that "no data" will appear if there are no satellite on your specified geo-location, which means you need to go back and adjust your satellite settings.
3. View the selected satellite paths on the world map, and be awed!

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

### For Developers

* To develop locally, download the project from my GitHub, cd into the folder and run `npm install`. You can later run `npm start` to start the app on the default localhost:3000 port and  `npm run build` to build the project for production.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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
