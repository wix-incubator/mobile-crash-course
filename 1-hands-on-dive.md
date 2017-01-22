# Day 1: Hands-on Dive

## `10:00 - 10:15` - Coffee and Mingling
Who are you and where are you from?! We're spending the entire week together, so some customary meet and greet.

## `10:15 - 10:55` - Talk: Introduction (with [Tal Kol](mailto:talkol@wix.com))
A short introduction. We'll talk about mobile engineering @ Wix and our mobile stack in general. We'll also talk about the main mobile products being developed and who's making them.

## `11:00 - 11:15` - Talk: Schedule Overview (with [Tal Kol](mailto:talkol@wix.com))
We'll go over the game plan for the entire week.

## `11:15 - 18:30` - Workshop: Redux Dataflow with React Native (with TBD)
This is the first official day of the crash course. In order to get the juices running, we'll spend most of the day working on a hands-on project. We'll use this project as a baseline for the other workshops in the next few days.

There are 4 project ideas to choose from, ordered by difficulty. Choose **one** idea and aim to implement it by the end of the day.

####Some pointers:
* Use React Native version 0.38 ([how?](https://gist.github.com/talkol/b6cb414a2435062d310b2d8dfcd8b97c))
* Clone this [template](https://github.com/DanielZlotin/react-native-38-template.git) to use react-native 38 with navigation.
* Use [Redux](https://github.com/reactjs/redux) and **invest time** on well-organized [dataflow](https://hackernoon.com/redux-step-by-step-a-simple-and-robust-workflow-for-real-life-apps-1fdf7df46092#.bubcmvc8j) and correct state [modeling](https://medium.com/@talkol/avoiding-accidental-complexity-when-structuring-your-app-state-6e6d22ad5e2a)
* If you need a navigation solution, rely on [react-native-navigation](https://github.com/wix/react-native-navigation)
* Use modern JavaScript syntax (ES6+), async-await, classes. Avoid Typescript please
* If you don't have experience with TDD or testing for Redux, avoid testing for now
* Try to run your project both on iOS and Android
* Place your project on github (can be public too)

### Idea 1: Port Reddit web client from blog post to React Native
This is the easiest project since you have a working Redux project to start from. Take the Reddit [client](https://github.com/wix/react-dataflow-example) described in this [blog post](https://hackernoon.com/redux-step-by-step-a-simple-and-robust-workflow-for-real-life-apps-1fdf7df46092#.bubcmvc8j) and port it from React for the web to React Native for mobile. Avoid copying and pasting code, rewrite it from scratch. If you want to increase difficulty, look in the original source as little as possible.

### Idea 2: Reddit comment circle-jerk game in React Native
The idea for the game is showing you a random post from the reddit frontpage (simple REST [API](https://www.reddit.com/dev/api/), consume with [Fetch](https://facebook.github.io/react-native/docs/network.html)). After showing the post, it will show you 4 top level comments and you have to guess which is the topmost one. The 4 shown don’t necessarily need to be the topmost 4. Keep score. We can also actually release this game open source and publish on reddit for some sweet Wix engineering karma.

### Idea 3: Star Wars IMDB clone in React Native
Create a simple [IMDB](http://www.imdb.com/) mobile app for Star Wars films based on the [Star Wars API](https://swapi.co/). Support simple browsing by list and if you're feeling adventarous, load data in pages as you scroll. It will be nice to support search as well. Do caching in your Redux store, so data you've already downloaded won't need to be downloaded again.

### Idea 4: Slack clone in React Native and Firebase
Create a simple [Slack](https://slack.com/) clone for mobile. Create a free account on [Firebase](https://firebase.google.com/docs/database/) and use the Realtime Database with their awesome [JS SDK](https://www.npmjs.com/package/firebase) that works well on React Native. Allow users to create channels and chat in them. Invent your own simple chat protocol. There's no need to support push notifications.
