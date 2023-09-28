
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Dyly4g6C)
# Homework 2 - Dev Setup and Deployment

This assignment is intented to help you set up your development environment for React. You will create a simple React App and deploy using one of the methods covered in lecture.

## Step 1
- Install `npx` following the instructions here: https://www.npmjs.com/package/npx
- run `npx create-react-app my-first-app` to create the React application
- In the newly created app, replace the contents of `App.js` including your name:

```
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <p>Hello CSCI E-39!</p>
        <p>
          My name is ____________
        </p>
      </header>
    </div>
  );
}

export default App;
```
- move all of the contents of `my-first-app` to the repos root directory (e.g. for mac/linux `rm my-first-app/README.md && rm my-first-app/.github && mv my-first-app/* .`). Make sure you do not copy over the `README.md` and `.github` that was generated by `create-react-app` into this repo.
- run `npm install`
- start the app with `npm start`. If you are getting a warning about `@babel/plugin-proposal-private-property-in-object`, you can fix this by adding `"@babel/plugin-proposal-private-property-in-object":"7.21.11"` to your `dependencies` in `package.json`.
- verify the app is running
- modify line 6 in `App.test.js` to:

`const linkElement = screen.getByText(/Hello CSCI E-39!/i);`

- make sure all tests pass when running `npm run test` 

## Step 2
Deploy the application using Github Pages (https://github.com/prof-tejera/react-deployment-code#github-actions) or a different method if you prefer. As long as the URL is avaliable on the public internet and live for 2 weeks, then you can use whatever method you want.

## Submitting
Edit this file (README.md) and complete the following:

- URL to live application:  https://prof-tejera.github.io/homework-2-MannyAdumbire/
- What code editor are you using? VSCode

That is all!
