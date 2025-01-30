# React Router Dom v6 Nested Route Rendering Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem is that the nested routes are defined correctly in the code, but the child components within those nested routes fail to render. The parent route renders successfully, but the content of the nested routes remains blank. 

The `App.js` file contains the buggy code. `AppSolution.js` shows the corrected version. The solution involves carefully examining the route definitions and ensuring proper nesting and component structure within the `Routes` component.