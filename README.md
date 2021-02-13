# React native web app
This is a very basic react native web application. <br>
I have used react native managed by expo <br>
Main goal is to make react native web app running in gh-pages <br>

You can see the live demo: https://johnkirang.github.io/react-native-app/

## What i did

### Make sure have installed following in your system,
* Min node-version req is 10.19.0. if you use a below node versions. Building and running app in web dont work
* Expo-cli used is 4.1.6
* git

### Created an empty project using
    expo init react-native-app
    cd react-native-app
    npm i gh-pages
    expo start --web

### Changes in package.json
    Added homepage url
    Added scripts
    "build": "expo build:web",
    "deploy": "gh-pages -d web-build"

### Created repository in git and commited the code
    
### Build the webapp using
    expo build:web

### Deploy it to gh-pages
    npm run deploy

## Now your own React-Native Web app is deployed to gh-pages and ready to use.....:-)


