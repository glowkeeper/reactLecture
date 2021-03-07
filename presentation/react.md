# An Introduction to GitHub

![](images/minimaLogo.svg)

Dr Steven Huckle

steve.huckle@minima.global

- - -

## Overview

+ What is React?
+ Why React?
+ Anatomy of a React project
+ A (brief) example
+ Useful resources

## Goals

1. Introduce React
2. Describe a typical build pipeline of a commercial React project
3. Show an example

# What is React?

![](images/react.png)

_Image Source: [https://www.freecodecamp.org/news/react-js-for-beginners-props-state-explained/](https://www.freecodecamp.org/news/react-js-for-beginners-props-state-explained/)_

- - -

## React

+ React is an open-source, front end, JavaScript library for building user interfaces
+ It is maintained by Facebook and a community of developers
+ HTML on its own is a declarative markup language used for describing _how_ things look
+ JavaScript is a programming language that was originally intended for browsers (client-side)
+ HTML and JavaScript work together to provide a more interactive user experience
+ React is a JavaScript framework designed to take the user (and developer) experience to the next level

# Why React?

![](images/question.svg)

_Image Source: [https://freesvg.org/black-question-mark-sign-vector-image](https://freesvg.org/black-question-mark-sign-vector-image)_

- - -

## Language Rankings

![](images/languageRankings.png)

_Image Source: [https://octoverse.github.com/](https://octoverse.github.com/)_

## Download Trends

![](images/downloadTrends.png)

_Image Source: [https://www.npmtrends.com/react-vs-vue-vs-@angular/core](https://www.npmtrends.com/react-vs-vue-vs-@angular/core)_

## Jobs

![](images/hiringTrends.png)

_Image Source: [https://www.hntrends.com/2020/dec-year-unlike-any-other-tech-tools-didnt-change-much.html?compare=React&compare=Vue&compare=Angular+2&compare=AngularJS](https://www.hntrends.com/2020/dec-year-unlike-any-other-tech-tools-didnt-change-much.html?compare=React&compare=Vue&compare=Angular+2&compare=AngularJS)_

# Anatomy of a React Project

![](images/reactReduxTypescriptWebpack.png)

_Image Source: [https://medium.com/swlh/how-to-structure-your-typescript-react-redux-app-877d1eba1c1e](https://medium.com/swlh/how-to-structure-your-typescript-react-redux-app-877d1eba1c1e)_

- - -

## Architectural Overview

![](images/anatomy.png)

## Node.js and NPM

+ `Node.js` is a JavaScript runtime environment
+ `npm` is a package manager for JavaScript
+ `npm` is the default package manager for `Node.js`

## Webpack

![](images/webpack.png)

_Image Source: [https://v4.webpack.js.org/](https://v4.webpack.js.org/)_

## Typescript

+ TypeScript extends JavaScript by adding static typing
+ It is a strict syntactical superset of JavaScript
+ TypeScript transcompiles to JavaScript.
+ TypeScript helps catch errors _at compile time_

## Redux

+ Redux is an open-source JavaScript library for managing application state
+ The state of your application is kept in a store
+ It makes application state dependable and predictable
+ Each (React) component can access any state that it needs from the store
+ It facilitates communication and sharing of data
+ Helps separate UI from state

### Redux Actions

Redux depends on actions, store, and reducers.

+ Actions are events
+ Actions are sent to the store using `store.dispatch()`
+ They are the only way you can send data from your application to your store

### Redux Store

+ The store holds the application state
+ It should be the single source of truth for that state

### Redux Reducers

Redux reducers are based on the `reduce` function in JavaScript, where a single value is calculated from multiple values, using a callback function:

```
const euros = [29.76, 41.85, 46.5];
const sum = euros.reduce((total, amount) => total + amount);
sum // 118.11
```

+ Reducers are _pure functions_ that take the current state of an application, perform an action, and return a new state
+ These states are stored as objects; they specify how the state of an application changes in response to an action

# An Example

![](images/](images/example.svg)

_Image Source: [https://freesvg.org/logo-example-fruit-apple](https://freesvg.org/logo-example-fruit-apple)_

- - -

## A Simple Something or Other

...

# Useful Resources

![](images/resources.jpeg)

_Image Source: [https://lochside.aberdeen.sch.uk/home-learning-resources/](https://lochside.aberdeen.sch.uk/home-learning-resources/)_

- - -

## React Sites

+ [https://reactjs.org/](https://reactjs.org/)
+ [https://www.w3schools.com/react/](https://www.w3schools.com/react/)
+ [https://www.typescriptlang.org/](https://www.typescriptlang.org/)
+ [https://redux.js.org/](https://redux.js.org/)
+ [https://webpack.js.org/](https://webpack.js.org/)
+ [https://nodejs.org/en/](https://nodejs.org/en/)
+ [https://www.npmjs.com/](https://www.npmjs.com/)
