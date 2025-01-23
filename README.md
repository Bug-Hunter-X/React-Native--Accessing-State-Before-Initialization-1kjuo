# React Native: Accessing State Before Initialization

This repository demonstrates a common error in React Native development: attempting to access state or props before they have been fully initialized. The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version.

## Problem

In React Native, asynchronous operations and component lifecycles can lead to accessing properties (like state or props) before they have been set. This results in runtime errors.

## Solution

The solution involves carefully managing the lifecycle methods and using conditional rendering to avoid errors when dealing with potentially null or undefined values.  We can also use the `useEffect` hook for cleaner asynchronous operations in functional components.

## How to Run

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npx react-native run-android` or `npx react-native run-ios` to run the app on an emulator or device. 

Feel free to open issues or contribute to the project!