# Redux - Combined Reducers

The most common state shape for a Redux app is a plain Javascript object containing "slices" of domain-specific data at each top-level key. Similarly, the most common approach to writing reducer logic for that state shape is to have "slice reducer" functions, each with the same (state, action) signature, and each responsible for managing all updates to that specific slice of state. Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object.

# review

the main advantage of Context API over Redux is that instead of importing actions and using them we get to manipulate the state directly on the component we are currently on. Context API is also easy to set up and is as effective as Redux.

Reducers are functions that take the current state and an action as arguments, and return a new state result.

An action is a plain JavaScript object that has a type field. You can think of an action as an event that describes something that happened in the application.

The only way to change the state is to emit an action, an object describing what happened. If the changes outside the store are intended to modify the state, dispatch should be used instead. ... If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part.

dispatch is a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change. With React Redux, your components never access the store directly - connect does it for you.
