# Learn Redux

A simple React + Redux implementation. This will be turned into a free video series once the app is totally fleshed out.

## Running

First `npm install` to grab all the necessary dependencies. 

Then run `npm start` and open <localhost:7770> in your browser.

## Production Build

Run `npm build` to create a distro folder and a bundle.js file.

## Notes

Actions are like event listeners, they are merely actions but does not update state

Its the reducers job to update the actual state and return the updated state

A reducer takes in two things
1. the action (info about what happened)
2. copy of current state


