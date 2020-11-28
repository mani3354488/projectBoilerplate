Production grade javascript project boilerplate.

Idea is to address : 

Version control
Automated CI/CD
Code Quality
Tooling
Module Support 

Build Process involves couple of stages :

Install
Lint (linter - eslint)(formatter - prettier)
Test (jest)(code coverage - nyc)
Build (transpile - babel)(pre-process )(uglify assests)(bundling files - webpack)(compress)
Push (github)
Deploy (cloud)

Technoligies used:

MERN stack
REST, GRAPHQL

Commands :

npm run lint (find the issues in the code)
npm run lint:fix (fix all the issues by formatting the code)