# PWA - Text Editor

## Description

Using this existing web application, the goal is to set up it up and configure it as a PWA (Progressive Web Application). 

## Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Testing](#installation)
- [Preview](#preivew)
- [Deployment](#deployment)

## Usage

When we enter `npm run start` from the root directory, the application will run and start.

## Testing

Look inside the package.json in the project root folder. Notice also a script named "start:dev". It uses a node package called concurrently to start up both your server and client environments at the same time when you are in development. 

  - So to test locally, just run `npm start:dev`. 

  - To test how it will work in production, run `npm start`. 
  
In the *client/package.json* file, you'll see that the build script invokes Webpack, and from there Webpack does its thing.

## Preview 

![Preview](https://i.imgur.com/Sg4hDdE.png)

## Deployment

[Heroku](https://text-editor-sws-4a6e1a55dd5d.herokuapp.com/) 

[GitHub Repository](https://github.com/seanwsutter/text-editor-sws)

