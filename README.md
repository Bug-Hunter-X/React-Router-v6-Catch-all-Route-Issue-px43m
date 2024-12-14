This repository demonstrates a common issue encountered when using catch-all routes in React Router v6. The problem is that the catch-all route (`path="*"`) doesn't always work as expected, leading to errors or unexpected behavior.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected implementation.  The issue arises from incorrect usage of the catch-all route, causing unmatched routes to not render the NotFound component. This often occurs because of other routing issues or typos in route paths.

The solution involves ensuring the catch-all route is placed correctly within the Routes component.  By placing the catch-all route as the last route definition, it effectively catches any unmatched path.