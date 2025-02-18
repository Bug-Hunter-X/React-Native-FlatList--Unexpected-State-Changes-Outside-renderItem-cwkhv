# React Native FlatList: Unexpected State Changes Outside renderItem

This repository demonstrates a common error in React Native's FlatList component where state updates outside of the `renderItem` method cause unexpected behavior. The bug and its solution are shown in separate files.

## Bug
The `FlatListBug.js` file shows an example of attempting to modify state in the `keyExtractor` function. This incorrect approach leads to unpredictable state changes and improper rendering.

## Solution
The `FlatListBugSolution.js` file provides a correct implementation.  State updates are properly handled within the `renderItem` method, ensuring that the `FlatList` component functions as intended.

## How to reproduce the bug
1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app using a React Native environment. Observe that the list does not update correctly.
4. Examine the `FlatListBugSolution.js` file for the correct approach.