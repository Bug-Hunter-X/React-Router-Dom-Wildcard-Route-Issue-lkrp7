# React Router Dom Wildcard Route Issue

This repository demonstrates a common issue with wildcard routes (`/*`) in React Router Dom v6.  When a wildcard route is nested under other routes, it will not match any additional paths.

The issue arises because the wildcard route is considered a child of other routes which means any path matching the other routes will prevent the wildcard route from being considered. 