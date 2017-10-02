# Preliminaries

Before starting the crash course, you should familiarize yourself with some basic concepts. Feel free to skip the parts you already know.

*Why? Since we have attendees from different backgrounds (eg. native mobile vs. web frontend) this helps us create a baseline and avoid spending course time on basics that some of you may find boring.*


### Installation prerequisites

Ensure that you fulfill all required environment setup and software prerequisites before starting the training.

> * Xcode 9.0 (or later)
> * [Android Studio latest version](https://developer.android.com/studio/index.html)
> * Android SDK
> * JS IDE - WebStorm/VSCode/IntelliJ..
> * [Detox](https://github.com/wix/detox)
> * [AppleSimulatorUtils](https://github.com/wix/AppleSimulatorUtils) 
> * [NVM](https://github.com/creationix/nvm#install-script)
> * NPM: `nvm install stable`


## 1. Modern JavaScript syntax

We write business logic in modern JS (ES6+), you should be familiar with the basic language syntax.

* If you don't usually work with JS, here's a [single page with all basic syntax](http://betterexplained.com/articles/the-single-page-javascript-overview) (ES5)
* JS has become a modern language from ES6, here's a [list of all new features](https://github.com/lukehoban/es6features) (ES6)
* The most useful feature beyond ES6 is async-await, here's Tal's [blog post about it](https://hackernoon.com/an-ode-to-async-await-7da2dd3c2056#.pyx0twijy) (ES8)

## 2. React Native basics

Our stack is based on React Native, you should play with it a little before the course starts.

* Install [all required software](https://facebook.github.io/react-native/docs/getting-started.html) on your Mac in advance! Both **iOS** (Xcode) and **Android** (Android Studio)
* Complete this basic [tutorial](https://facebook.github.io/react-native/docs/tutorial.html) for React Native (even if you don't know React)
* Make sure you are able to [create a new RN app](https://facebook.github.io/react-native/docs/getting-started.html#testing-your-react-native-installation) and run it on a simulator

## 3. Flux dataflow with redux

The MVC pattern is iffy with React (and declarative programming in general), we use Flux instead.

* One of the most popular Flux implementations is a library named [redux](https://github.com/reactjs/redux), skim through its insanly long [docs](http://redux.js.org)
* It's actually much easier and faster to learn redux by example from Tal's [detailed blog post](https://hackernoon.com/redux-step-by-step-a-simple-and-robust-workflow-for-real-life-apps-1fdf7df46092#.qrxxpd867)
* It's important to understand how to model your app's state, this [blog post](https://hackernoon.com/avoiding-accidental-complexity-when-structuring-your-app-state-6e6d22ad5e2a#.gchj7syn3) will help you

## Last but not least

Why does the Wix mobile stack incorporate these things?! See this [ReactNext video](http://youtube.com/watch?v=abSNo2P9mMM) by Tal
