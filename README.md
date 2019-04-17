# Weather Web App

## Set-Up Guide
- [Installation](#installation)
- [Development Workflow](#development-workflow)
- [Quick Overview](#quick-overview)

**0. Before doing any of this, if you're using your own laptop/desktop, make sure you've got the latest versions of node and npm installed (npm v: 4.0.5 & node v: 7.4.0) :**

```sh
node -v
npm -v
```

## Installation

**1. Clone this repository :**


**2. Install the dependencies :**

```sh
npm install
```
**3.Install the progress component **
```sh
npm install --save react-circular-progressbar
```

## Development Workflow


**1. Start a live-reload development server :**

```sh
npm run dev
```

> This is a full web server for your project. Any time you make changes within the `src` directory, it will rebuild and even refresh your browser.


**2. Generate a production build in `./build` :**

```sh
npm run build
```

**3. Start local production server with [serve](https://github.com/zeit/serve):**

```sh
npm start
```

> This simply serves up the contents of `./build`. Bear in mind, if you use this, the localhost port your server is running on will refresh, and you'll also need to restart it to see any changes you've made to the code in `src`.


## Quick Overview

- The initial run will display the iPhone version (iPhone 6/7 Plus screen size); 

- The CSS pre-processor in use is Less. You don't have to worry about the syntax and just write in normal CSS as there are helper modules to assist you (located in `style/helpers`).

- There are many weather APIs out there; this boilerplate uses OpenWeatherMap. Sign up, is free and you can find out more about it here : https://openweathermap.org/api  👌

