# Just Another Text Editor

> A PWA single page text editor that runs in the browser.
> Live demo [_here_](https://guarded-garden-40686.herokuapp.com/).

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Screenshots](#screenshots)
- [Setup](#setup)
- [Contact](#contact)
- [License](#license)

## General Information

- A simple text editor that runs in the browser and can be installed.
- A single-page application that meets the PWA criteria.
- Functions like a a native app on supporting systems.
- Features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser.
- The application will also function offline.

## Technologies Used

- JavaScript
- CSS3
- Node.js
- Express.js
- Webpack
- Code Mirror
- idb

## Features

- Uses local storage and IndexedDB database to store and retrieve data.
- When user clicks off the DOM window, the content in the text editor is saved with IndexedDB.
- Install button to download the web application as an icon on user's desktop.
- Static assets pre cached upon loading along with subsequent pages and static assets.

## Screenshots

![JATE](client/src/images/jate-screen.png)

## Setup

Once project has been cloned run the following to install dependencies and start server.

```
npm install && npm start
```

## Contact

Created by [@lilyso](https://github.com/lilyso) - feel free to contact me!

## License

This project is open source and available under the [MIT License](LICENSE).
