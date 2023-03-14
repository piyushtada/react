# react
All the things I am learning about react while doing Complete React Developer in 2023 (w/ Redux, Hooks, GraphQL)

> Press . to start vs code in the browser 

# Complete React Developer

We install React developer tools from chrome store
> JSX : html like code that we use in side js, it's an extention of js code
 Declaraive: it means we define the data and the state and react make the changes to the website to show our changes

```bash
//to get the version
node -v
npm -v
yarn -v
```

Difference bw npm vs npx
Is that with npm you keep the package in the local directory but with npx we dowload the package execute it and remove it from the local directory

# React
```bash
npx create-react-app my-app
```

**react scripts** in package.json is there to make our life simple we describe ==scripts== in the dictionary below to do what we want 
- eject: is there so we can modifiy the behaviour of build process if needed but mostly we will not need it

> Babble converts our code into something that all browser can understand in converts it
> Webpack: is chucking the big js file so the user only gets the portion need by him at that time

## manifest.json
provides setup in case user wants to download the app and run locally

## robots.txt
tells the google clawer what the app is.

React is just using functions to return some html. 

## Hooks vs Classes
Hooks are specific to the react but classes are general programming concept.
Both of them are used to create react app.


# Issues & Tips
## When you get a 3000 server is running error
[stackoverflow](https://stackoverflow.com/questions/49022731/keep-getting-something-is-already-running-on-port-3000-when-i-do-npm-start-o)
```shell
npx kill-port 3000
```
This command will stop the server on port 3000 then you can start working again.
---
# References 
