Simple Increment and Decrement counter application using redux and react-redux libraries.
# If you use npm:
npm install react-redux

# Or if you use Yarn:
yarn add react-redux

Redux is an open-source JavaScript library used to manage application state. React uses Redux for building the user interface. It was first introduced by Dan Abramov and Andrew Clark in 2015.

React Redux is the official React binding for Redux. It allows React components to read data from a Redux Store, and dispatch Actions to the Store to update data. Redux helps apps to scale by providing a sensible way to manage state through a unidirectional data flow model. React Redux is conceptually simple. It subscribes to the Redux store, checks to see if the data which your component wants have changed, and re-renders your component.

Redux was inspired by Flux. Redux studied the Flux architecture and omitted unnecessary complexity.

Redux does not have Dispatcher concept.
Redux has an only Store whereas Flux has many Stores.
The Action objects will be received and handled directly by Store.
