# React Native: TypeError: Cannot read properties of null (reading '...')

This repository demonstrates a common error in React Native applications: `TypeError: Cannot read properties of null (reading '...')`. This error arises when attempting to access a property of an object that is currently null or undefined.  The provided code showcases the bug and its solution using optional chaining and nullish coalescing.

## Bug Description
The bug occurs primarily when working with asynchronous data fetching, where the data may not be immediately available when a component tries to render.  Accessing properties of objects before their values are assigned leads to the error.

## Solution
The solution involves using optional chaining (`?.`) and the nullish coalescing operator (`??`). Optional chaining safely accesses nested properties, returning undefined if any intermediate property is null or undefined.  Nullish coalescing provides a default value if the result is null or undefined.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` (or `npx react-native run-ios`) to start the app.
