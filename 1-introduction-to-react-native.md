# Day 1: React Native Architecture & Data Flows

## `10:00-10:30` - Talk:Introduction (with [Lev Vidrak](mailto:levv@wix.com))

Who are you and where are you from?! We're spending the entire week together, so some customary meet and greet. A short introduction. We'll talk about mobile engineering @ Wix and our mobile stack in general. We'll also talk about the main mobile products being developed and who's making them.

## `10:40-12:00` - Talk: ReactNative architecture - part 1 (with [Tal Kol](mailto:talkol@wix.com))

Introduce the main aspects of React Native, why we are working in RN framework in Wix, differences between native and RN development that you should remember.

This goal is to become familiar with mobile dev philosophy and the reasons we chose React Native.

## `12:00-13:00` - Lunch Break

## `13:00-13:40` - Workshop: Init a React Native project (with [Daniel Zlotin](mailto:danielz@wix.com))

The goal is to have a working RN dev environment **on both platforms!**

## `13:50-15:30` - Talk: ReactNative architecture - part 2 (with [Tal Kol](mailto:talkol@wix.com))

We will dive into React Native internals to explore the main components of the RN framework,
following that we will see how do we split projects between Native and JavaScript and what are the pros and cons of each side.

## `15:40-16:15` - Talk: Flux Design Pattern & Redux (with [Yedidya Kennard](mailto:yedidyak@wix.com))
Go over Redux's key ideas, a design pattern that was inspired by Flux.

## `16:20-17:00` - Talk: Introduction to RemX (with [Nir Yosef](mailto:niryo@wix.com ))
Can we offer you an alternative dataflow to Redux, with less boilerplate and simpler tests? We'll introduce you to remx, a much more convenient state management library.


## `17:00-19:00` - Workshop: remx Data-flow with React Native (with [Yedidya Kennard](mailto:yedidyak@wix.com) &  [Nir Yosef](mailto:niryo@wix.com ))

In order to get the juices running, we'll spend some time working on a hands-on project. We'll use this project as a baseline for the other workshops in the next few days.
We will implement a simple reddit client app as described in [this](https://hackernoon.com/redux-step-by-step-a-simple-and-robust-workflow-for-real-life-apps-1fdf7df46092) blog post, in `react-native`, with `react-native-navigation`.

We will build an app with remx that:

1. displays a loading indicator until topics list is fetched from reddit
  * https://www.reddit.com/subreddits/default.json
2. displays a list of topics
3. when topic is clicked, pushes a screen and displays a loading indicator until posts from the topic is fetched
  * https://www.reddit.com/${subredditUrl}hot.json
4. displays the posts list from this topic
5. when post is clicked, shows a modal with the post detail (image/text)

