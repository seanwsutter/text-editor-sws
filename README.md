# PWA - Text Editor

## Description

Using this existing web application, the goal is to set up it up and configure it as a PWA (Progressive Web Application). 

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Testing](#installation)
- [Preview](#preivew)
- [Deployment](#deployment)

## Installation

Click the Install button in the PWA!

![Install](https://i.imgur.com/UfRnCWa.png)

Alternatively click the icon in the right side of the URL bar. Shown Below

![Install](https://i.imgur.com/5q0eZav.png)

## Testing

Look inside the package.json in the project root folder. Notice also a script named "start:dev". It uses a node package called concurrently to start up both your server and client environments at the same time when you are in development. 

  - So to test locally, just run `npm start:dev`. 

  - To test how it will work in production, run `npm start`. 
  
In the *client/package.json* file, you'll see that the build script invokes Webpack, and from there Webpack does its thing.

## Uninstall

Close the PWA or click uninstall shown here:

![Uninstall](https://i.imgur.com/Wfh2KSo.png)

If you need to start from scratch and remove the existing PWA:

* Delete the PWA from your hard drive
* Kill the server session running in VS Code
* In Chrome, go to localhost:3000, If it does load open up the dev console, go to Application -> Service Workers and click the Unregister Worker link.

![Uninstall](https://i.imgur.com/Wfh2KSo.png)

## Deployment

[Heroku](https://text-editor-sws-4a6e1a55dd5d.herokuapp.com/) 

[GitHub Repository](https://github.com/seanwsutter/text-editor-sws)

