# Day 3: Scaling & Deployment

## `10:00 - 10:55` - Talk: Multi Module Architecture (with [Omri Bruchim](mailto:omrib@wix.com))
Wix One App is a mega-app which hosts dozens of mini-apps from various groups within Wix. Each mini-app is a separate [*module*](https://github.com/wix-private/wix-react-native-framework/blob/master/modules.md) with distinct lifecycle. Also, how do we implement scenarios spanning multiple modules?



## `11:00 - 11:55` - Talk: The Mighty UI Lib (with [Eitan Sharabi](mailto:ethans@wix.com))
When everybody's code is running side by side in the same app, there's greater emphasis on a similar UI language and standardized UI components. We'll go over the [UI Lib](https://github.com/wix-private/wix-react-native-ui-lib) and see how to use it in our day to day.

## `12:00 - 13:00` - Lunch Break
FOOD FOOD FOOD - Pancake House


## `13:00 - 13:30` - Talk: Frontend & Backend Servers (with TBD)
What are the special backend concerns of our mobile stack? The fact that app updates are optional mean we always deal with old versions and have to think about backwards compatibility. We'll discuss how to address this.


## `13:30 - 14:55` - Talk: CI, Build & Distribution (with [Sergey Ilyevsky](mailto:sergeyi@wix.com))
Mobile is a unique ecosystem, how does it translate to our CI, what's different? What do our projects look like and how do we build them? How do we distribute our code and deploy apps to production?



## `15:00 - 15:55` - Talk: Detox and UI Automation Tests (with [Rotem Mizrachi](mailto:rotemm@wix.com ))
UI automation testing (E2E) is a key requirement for engineering at scale. What is the [protractor](http://www.protractortest.org) of the mobile world? [Appium](http://appium.io)? How is [detox](https://github.com/wix/detox) different? How do we deal with flakiness? What do tests look like?



## `16:00 - 18:00` - Workshop: Detoxify Your Project (with [Rotem Mizrachi](mailto:rotemm@wix.com) & [Ran Greenberg](mailto:rang@wix.com))
Learn the testing API by going over detox's own suite of [E2E tests](https://github.com/wix/detox/tree/master/detox/test/e2e). Write a few end to end scenarios, practice the testing API and try to get a feel for its limitations.

Cover your demo app with e2e tests.

