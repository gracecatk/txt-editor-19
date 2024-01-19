# Project README

## Project Overview

This project is designed to create a web application with a client-server architecture, utilizing technologies such as npm, webpack, IndexedDB, service workers, and Render for deployment. The application aims to provide a functional text editor with features like bundling JavaScript files, saving content using IndexedDB, and deploying on Render with proper build scripts.

## Folder Structure

Upon opening the application in your editor, you should observe the following folder structure:


## Running the Application

1. Open your terminal and navigate to the root directory.
2. Run the command `npm run start` to start up the backend and serve the client.

## Bundling JavaScript Files

When running the text editor application from your terminal, webpack will bundle your JavaScript files, ensuring that the text editor functions in the browser without errors.

## Webpack Plugins

Running webpack plugins will generate the following files:
- HTML file
- Service worker
- Manifest file

## IndexedDB Integration

- Upon opening the text editor, IndexedDB will immediately create a database storage.
- Entering content and clicking off the DOM window will save the content in the text editor with IndexedDB.
- Reopening the text editor after closing it will retrieve the content from IndexedDB.

## Installation and Desktop Icon

1. Click on the "Install" button to download the web application as an icon on your desktop.
2. Loading the web application should result in a registered service worker using workbox.

## Deployment on Render

When deploying to Render, ensure that you have proper build scripts for a webpack application.

Feel free to explore and enhance the features of the text editor application according to your project requirements. Happy coding!
