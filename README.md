# Getting Started with Fibonacci Calculator

This project was created for docker Tutorials purpose

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

## Docker Commands

to run the development server
---------

    $ docker-compose up
then access the app from : http://localhost:3000

To run the Production build
------------

    $ docker build -t react-app .
    $ docker run -p 3000:80 -d react-app
 then access the service on:  http://localhost:3000
 