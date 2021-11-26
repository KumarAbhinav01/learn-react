---
sidebar_position: 2
---
# Create React App

[Create React App](https://github.com/facebook/create-react-app) is a comfortable environment for learning React, and is the best way to start building a new single-page application in React.

It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. You’ll need to have `Node >= 14.0.0 and npm >= 5.6` on your machine. To create a project, run:

```
npx create-react-app my-app
```

After running this command it will start downloading the essential packages. Now use **cd** command to go inside folder.

```
cd my-app
```

Now use **npm** command to start the development server.
```
npm start
```

Then open [http://localhost:3000](http://localhost:3000) to see your app.

![create-react-app!](../../static/img/gif1.svg)


## Creating an App
To create a new app, you may choose one of the following methods:

### npx
```
npx create-react-app my-app
```
:::tip Remember

npx comes with npm 5.2+ and higher, see instructions below for older npm versions

:::
If you use npm 5.1 or earlier, you can't use npx. Instead, install create-react-app globally:
```
npm install -g create-react-app
```
Now you can run:
```
create-react-app my-app
```

### npm
```
npm init react-app my-app
```
npm init `<initializer>` is available in npm 6+

### Yarn
```
yarn create react-app my-app
```
`yarn create` is available in Yarn 0.25+

## Output
Running any of these commands will create a directory called `my-app` inside the current folder. Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── serviceWorker.js
    └── setupTests.js
```

No configuration or complicated folder structures, only the files you need to build your app. Once the installation is done, you can open your project folder:
```
cd my-app
```

## Scripts
Inside the newly created project, you can run some built-in commands:

### `npm start` or `yarn start`
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm run build` or `yarn build`
Builds the app for production to the build folder. It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

Your app is ready to be deployed.