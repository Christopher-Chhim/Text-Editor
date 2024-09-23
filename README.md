# Text-Editor

## Description

This project is a Progressive Web Application (PWA) text editor designed for developers to create and save notes or code snippets both online and offline. Built with modern web technologies, it ensures reliable access to content by utilizing IndexedDB for local storage and a service worker for offline functionality. The application is structured as a client-server setup and is bundled using Webpack to optimize performance. This project is particularly useful for developers seeking a simple yet efficient tool for note-taking or code storage with the added benefit of offline access and persistent data across sessions.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Badges](#badges)

## Installation

Download an IDE. 
Download express.js (npm install)
Download nodemon (npm install)
Use scripts
 
## Usage

Type 'npm start' in the terminal to run the server. If functioning, the terminal should say that it is "Now listening on {PORT}". The deployed link should redirect the user to a text editor. The usage of this text editor project is aimed at providing developers with a reliable tool for creating and saving notes or code snippets both online and offline. Developers can use the text editor to write down notes, ideas, or code snippets while working on their projects, ensuring they have a handy, accessible tool that can store important information for later use. The text editor works without an internet connection thanks to the integration of IndexedDB and service workers. This ensures that users can still create, save, and retrieve their notes or snippets even when they are not connected to the internet. When users close and reopen the application, their previous content is retrieved automatically from IndexedDB, allowing them to continue where they left off without losing any data. Users can install the text editor as a PWA, which means it can be used like a native desktop application. This provides a convenient way to access the editor directly from their desktop without having to open a browser. The project is optimized using Webpack to bundle the application’s files efficiently. This ensures smooth loading times and performance, whether the user is online or offline. The text editor is built with next-gen JavaScript features, making it suitable for modern developers. It's an easy-to-use tool integrated with modern web technologies.

## Features

Client-Server Folder Structure:

- The application follows a structured setup with separate client and server folders.

Running the Application:

- When you run npm run start, it launches both the backend and frontend components, allowing the text editor to function seamlessly.

Bundling with Webpack:

- The application uses Webpack to bundle JavaScript files, ensuring that the files are efficiently packaged and optimized for the browser.

Webpack Plugins:

Webpack plugins are used to:

- Generate an HTML file to serve the application.
- Create a service worker for offline capabilities.
- Generate a manifest file, which is crucial for Progressive Web App (PWA) functionality.

Modern JavaScript Support:

- The text editor is capable of running next-gen JavaScript features without causing browser errors, ensuring compatibility and future-proofing.

IndexedDB for Offline Storage:

- IndexedDB is automatically set up when the text editor is opened. It provides a way to store data (such as notes or code snippets) in the browser even when offline.

Auto-Saving with IndexedDB:

- Content entered into the text editor is automatically saved in IndexedDB when the user clicks outside the window, ensuring that no data is lost.

Data Persistence:

- Upon reopening the application, previously entered content is retrieved from IndexedDB, allowing users to continue where they left off.

PWA Installation:

- The text editor can be installed as a desktop application via an Install button, creating an icon on the desktop.

Service Worker for Offline Access:

- A service worker is registered, allowing for offline functionality. Static assets are cached when the application is first loaded, and subsequent pages and assets are pre-cached as well.

Render Deployment:

- The application includes build scripts for deploying the application to Render, ensuring proper handling of the Webpack build for a smooth deployment process.


## License

MIT License

Copyright <2024> <Christopher Chhim>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Badges

![opensource](https://img.shields.io/badge/generator-open_source-blue)



 