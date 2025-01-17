# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using catch-all routes ('/*') in React Router v6.  The catch-all route, intended to handle 404 errors, unexpectedly redirects to the home page instead of displaying the appropriate not-found component.

The issue is due to a conflict between the order of routes and the behavior of the catch-all route, which should be placed as the last route within the Routes component. This is demonstrated in the `App.js` file.  The solution, in `AppSolution.js`, provides the corrected route order.