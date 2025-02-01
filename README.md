# React Native: Uninitialized State Variable Error

This repository demonstrates a common error in React Native applications: attempting to access a state variable or prop before it has been initialized. This often happens with asynchronous data fetching.

## Problem

The `uninitializedState.js` file shows how accessing a state variable before it's populated by an asynchronous operation leads to an error. The component tries to render the data before it's ready.

## Solution

The `uninitializedStateSolution.js` file demonstrates the solution using the optional chaining operator (`?.`) and a conditional rendering approach to safely access the data only when it's available.