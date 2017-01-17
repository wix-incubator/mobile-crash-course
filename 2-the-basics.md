# Day 2: The Basics

## `10:00 - 10:55` - Talk: Native vs JavaScript - What Goes Where (with [Tal Kol](mailto:talkol@wix.com))
In React Native you can write native code (ObjC/Swift/Java) and you can write code in JavaScript. What are the pros and cons of each side? How do we split projects between these two worlds.

## `11:00 - 11:55` - Talk: CI, Build & Distribution (with [Rotem Mizrachi](mailto:rotemm@wix.com))
Mobile is a unique ecosystem, how does it translate to our CI, what's different? What do our projects look like and how do we build them? How do we distribute our code and deploy apps to production?

## `12:00 - 12:55` - Talk: Navigation - Idea, Pains & Roadmap (with [Daniel Zlotin](mailto:danielzl@wix.com))
Navigation includes the entire skeleton of the app - core UI components like the navigation bar, tab bar and side menu; and how we move between screens. How is mobile navigation different from web? How's our [native library](https://github.com/wix/react-native-navigation) different from the stock one?

## `13:00 - 14:00` - Lunch Break
Let's eat together and get to know each other. Don't run to your home teams.

## `14:00 - 14:30` - Talk: Code Organization (with [Daniel Zlotin](mailto:danielzl@wix.com))
To kick start the discussion that follows, we'll start with a short overview on how we structure our projects and split our codebase according to different areas of concern. We follow the [Flux](https://facebook.github.io/flux/) architecture pattern with a very clear unidirectional flow of data.

## `14:30 - 17:30` - Show & Tell: One Scenario, Start to Finish (with [Daniel Zlotin](mailto:danielzl@wix.com))
Time to show everybody what you've been working on yersterday. Each of you will present his project for 5 minutes and then take a little longer to walk through a single scenario on the actual code from start to finish. For example, from the moment the user clicks on a button, to the action being dispatched, to the state being updated and the components being rerendered as a result.

In addition, did you face any dilemmas you want to share? Did you struggle with anything special?

####The purpose is group feedback:
* Is the code well organized?
* Is there clear separation between views and logic?
* Does the scenario flow well between different parts of the codebase? (according to our Flux conventions)
* How is the state modeled? Any accidental complexity?
* What would you design differently?
* Any feedback on code style? React tips or gotchas?

## `17:30 - 18:30` - Workshop: Implement One Suggestion (with [Daniel Zlotin](mailto:danielzl@wix.com))
Take one of the main feedbacks you've received from the group and address it in your code. Refactor to your heart's desire. Try to be open minded and experiment outside of your original comfort zone.
