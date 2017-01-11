# Day 4: The Gory Details

## `10:00 - 10:55` - Talk: Multi Module Architecture (with [Tal Kol](mailto:talkol@wix.com))
Wix One App is a mega-app which hosts dozens of mini-apps from various groups within Wix. Each mini-app is a separate [*module*](https://github.com/wix-private/wix-react-native-framework/blob/master/modules.md) with distinct lifecycle. Also, how do we implement scenarios spanning multiple modules?

## `11:00 - 11:55` - Talk: Performance Horror Stories (with [Rotem Mizrachi](mailto:rotemm@wix.com))
We're running on devices with limited resources. Our framework is also a delicate one, with multiple congestion points. What should we watch out for? How do we investigate the system when performance goes south?

## `12:00 - 12:55` - Talk: Experiments, BI & Monitoring (with [Noam Cocos](mailto:noamc@wix.com))
What's different for [Petri](https://github.com/wix/petri) experiments on mobile? How do we report BI on mobile? What are the tools we use to monitor our apps in production? We're going to see some code and experience the tools involved in live demos.

## `13:00 - 14:00` - Lunch Break
Let's eat together and get to know each other. Don't run to your home teams.

## `14:00 - 15:00` - Talk: Testing Redux (with [Yedidya Kennard](mailto:yedidyak@wix.com))
The base of the testing pyramid consists of unit tests. How well does our stack accomodate them? We'll see how to write tests for our business logic with [redux-testkit](https://github.com/wix/redux-testkit) in a live coding session showing actual test implementations for each of Redux's building blocks (reducers, selectors, thunks, etc).

## `15:00 - 18:30` - Workshop: Unit Test Your Project (with [Yedidya Kennard](mailto:yedidyak@wix.com))
Add some business logic tests with [redux-testkit](https://github.com/wix/redux-testkit) to the project you've made on the first day. Make sure you experiment with at least one test for each of the basic constructs of Redux (reducers, selectors, thunks, etc). Experiment with mocking for your unit tests using [jest](https://facebook.github.io/jest/). Experiment with an integration test using a mock store spanning actions from multiple files.
