# Direct State Variable Mutation in React

This example demonstrates a common mistake in React: directly manipulating the state variable instead of using the `setState` function. This error leads to unexpected behavior because the component won't re-render when the state changes, and it violates React's principles of immutability. 

## Bug

The `bug.js` file shows an attempt to increment the state variable `count` directly. This causes the component to not re-render after the `useEffect` hook runs.