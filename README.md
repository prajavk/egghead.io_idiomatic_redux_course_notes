# Building React Applications with Idiomatic Redux (Egghead.io)

This repo contains notes from [Dan Abramov's](https://github.com/gaearon) second [Redux course](https://egghead.io/courses/building-react-applications-with-idiomatic-redux) on Egghead.io.

## 01\. Simplifying the Arrow Functions
See how ES6 features can be used to clean up arrow functions even more. [Video](https://egghead.io/lessons/javascript-redux-simplifying-the-arrow-functions)


## 02. Supplying the Initial State
We will learn how to start a Redux app with a previously persisted state, and how it merges with the initial state specified by the reducers. [Video](https://egghead.io/lessons/javascript-redux-supplying-the-initial-state)


## 03. Persisting the State to the Local Storage
We will learn how to use store.subscribe() to efficiently persist some of the app’s state to localStorage and restore it after a refresh. [Video](https://egghead.io/lessons/javascript-redux-persisting-the-state-to-the-local-storage#/tab-transcript)


## 04. Refactoring the Entry Point
We will learn how to better separate the code in the entry point to prepare it for adding the router.
[Video](https://egghead.io/lessons/javascript-redux-refactoring-the-entry-point?series=building-react-applications-with-idiomatic-redux#/tab-transcript)


## 05. Adding React Router to the project
We will learn how to add React Router to a Redux project and make it render our root component. [Video](https://egghead.io/lessons/javascript-redux-adding-react-router-to-the-project?series=building-react-applications-with-idiomatic-redux#/tab-transcript)


## 06. Navigating with React Router `<Link>`
We will learn how to change the address bar using a component from React Router.
[Video](https://egghead.io/lessons/javascript-redux-navigating-with-react-router-link?series=building-react-applications-with-idiomatic-redux)


## 07. Filtering Redux State with React Router Params
We will learn how adding React Router shifts the balance of responsibilities, and how the components can use both at the same time.
[Video](https://egghead.io/lessons/javascript-redux-filtering-redux-state-with-react-router-params)


## 08. Using `withRouter()` to Inject the Params into Connected Components
We will learn how to use `withRouter()` to inject params provided by React Router into connected components deep in the tree without passing them down all the way down as props.
[Video](https://egghead.io/lessons/javascript-redux-using-withrouter-to-inject-the-params-into-connected-components)


## 09. Using `mapDispatchToProps()` Shorthand Notation
We will learn how to avoid the boilerplate code in `mapDispatchToProps()` for the common case where action creator arguments match the callback prop arguments.
[Video](https://egghead.io/lessons/javascript-redux-using-mapdispatchtoprops-shorthand-notation)


## 10. Colocating Selectors with reducers
We will learn how to encapsulate the knowledge about the state shape in the reducer files, so that the components don’t have to rely on it.
[Video](https://egghead.io/lessons/javascript-redux-colocating-selectors-with-reducers?series=building-react-applications-with-idiomatic-redux#/tab-transcript)


## 11. Normalizing the State Shape
We will learn how to normalize the state shape to ensure data consistency that is important in real-world applications.
[Video](https://egghead.io/lessons/javascript-redux-normalizing-the-state-shape)


## 12. Wrapping `dispatch()` to Log Actions
We will learn how centralized updates in Redux let us log every state change to the console along with the action that caused it.
[Video](https://egghead.io/lessons/javascript-redux-wrapping-dispatch-to-log-actions)


## 13. Adding a Fake Backend to the Project
We will learn about fake backend module that we will be using throughout the next lessons to simulate data fetching.
[Video](https://egghead.io/lessons/javascript-redux-adding-a-fake-backend-to-the-project)


## 14. Fetching Data on Route Change
We will learn how to fire up an async request when the route changes.
[Video](https://egghead.io/lessons/javascript-redux-fetching-data-on-route-change)


## 15. Dispatching Actions with the Fetched Data
We will learn how to dispatch a Redux action after the data has been fetched and recap how to do it when the route changes.
[Video](https://egghead.io/lessons/javascript-redux-dispatching-actions-with-the-fetched-data?series=building-react-applications-with-idiomatic-redux)


## 16. Wrapping `dispatch()` to Recognize Promises
We will learn how to teach `dispatch()` to recognize Promises so that we can move the async logic out of the components into asynchronous action creators.
[Video](https://egghead.io/lessons/javascript-redux-wrapping-dispatch-to-recognize-promises)


## 17. The Middleware chain
We will learn how we can generalize wrapping `dispatch()` for different purposes into a concept called “middleware” that is widely available in the Redux ecosystem.
[Video](https://egghead.io/lessons/javascript-redux-the-middleware-chain)


## 18. Applying Redux Middleware
We will learn how to replace the middleware we wrote and the custom code we used to glue it together with the existing core and third party utilities.
[Video](https://egghead.io/lessons/javascript-redux-applying-redux-middleware)


## 19. Updating the State with the Fetched Data
We will learn how moving the source of truth for the data to the server changes the state shape and the reducers in our app.
[Video](https://egghead.io/lessons/javascript-redux-updating-the-state-with-the-fetched-data)
