# React MUI Start

## **Description**
My personal start point for --dev with react instead use the command
    create react app

## How to use 
Clone from GitHub repository with
    git clone [url]
    npm i
    npm run start

## Install truobleshooting
In case webpack dependencies not starting for...
    [webpack-cli] TypeError: cli.isMultipleCompiler is not a function
        at Command.<anonymous> (C:\Users\user\Desktop\programar\react-mui\gitHubUserSearch\node_modules\@webpack-cli\serve\lib\index.js:146:35)
        at async Promise.all (index 1)
        at async Command.<anonymous> (C:\Users\user\Desktop\programar\react-mui\gitHubUserSearch\node_modules\webpack-cli\lib\webpack-cli.js:1674:7)

run the following commands
    npm install --save-dev webpack-cli 
    npm upgrade --save-dev webpack-cli

it should work at http://localhost:3007/ port.