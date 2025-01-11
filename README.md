# React useEffect Hook - Missing Dependency
This example demonstrates a common error in React's `useEffect` hook: forgetting to include necessary dependencies in the dependency array. This oversight can lead to unexpected behavior, often resulting in infinite render loops or incorrect state updates. 

The `bug.js` file contains the erroneous code, where the `useEffect` hook lacks the `count` state variable in its dependency array.  The `bugSolution.js` file provides the correct implementation.