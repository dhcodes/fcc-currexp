# Redux challenges

Redux is self-described as a "predictable state container for JavaScript apps." State (as introduced in the React challenges) is a way to manage what is displayed to a user based on that user's inputs or interactions with the application. While it's not necessary to use Redux with React, or vice-versa, the two are often used in conjunction as the features of Redux support applications built with React. Some of these features include:

- An immutable single state store or "single state of truth" through which the application makes UI updates
- Logical structure of `actions` carrying data to `reducer` functions that return a new application state
- A trackable history of changes to state

Redux is often added to a project when the complexity of managing the application's state becomes tedious. It helps minimize some of the headaches that can be caused by data mutability or passing state back-and-forth between many React components. Redux also supports debugging with tools like [Redux DevTools](https://github.com/gaearon/redux-devtools). Let's jump in to learning how Redux can simplify your React apps.

