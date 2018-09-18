# react-flow-babel

Type checking with Flow, React, Babel and Webpack

Adding static type checking to your React project is easy with [Flow](https://flow.org/).
I’ll go through the steps for setting up Flow using Babel and Webpack.
Familiarity with the CLI and Yarn or NPM is important.
[This tutorial](https://medium.com/@joshuacrass/type-checking-with-flow-react-babel-and-webpack-290cbf4cd4b3) is intended for those just getting started with Flow.
For those seeking a more advanced tutorial, see the official Flow [docs](https://flow.org/en/docs/).
They are a great resource for learning more about Flow.

We’ll start with a project that already uses Webpack and Babel.
If you want to add Webpack and Babel to your project or want to start from scratch,
checkout [React, Webpack and Babel from scratch](https://medium.com/@joshuacrass/react-webpack-and-babel-from-scratch-7aea5e768945).

This tutorial will pick up where we left off with my previous tutorial on
[Javascript Linting and Formatting with ESLint, Prettier, and Airbnb](https://medium.com/@joshuacrass/javascript-linting-and-formatting-with-eslint-prettier-and-airbnb-30eb746db862).
If you want, you can clone the [repo](https://github.com/joshuacrass/react-eslint-prettier) and start from there.
