# React Router Dom v6 Number Parameter Route Rendering Issue

This repository demonstrates a bug in React Router Dom v6 where routes with numeric parameters fail to render correctly. The issue occurs when a route path contains a parameter that's a number.  The component associated with that route should render, but it doesn't. 

## Steps to Reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to `/about/123`. The About component should render, but it does not. 

## Solution
The solution involves ensuring that parameters in the URL are treated as strings.  This might involve changing how parameters are passed or received.  See `AppSolution.js` for a corrected implementation.
