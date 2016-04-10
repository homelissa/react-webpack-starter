# react-webpack-starter

A small repo to kick off react/webpack projects. Goodies include:
  - transpiles es6 to es2015 via Babel
  - dev environment with hot module replacement via webpack
  - linting via eslint
  - testing with mocha, expect, jsdom, and React TestUtils
  - style using less or css
  - data-urlification of small images

## Get Started:
```
npm install
npm run test
npm run dev
```

To add your own files, simply delete `src/ExampleComponent` and `test/ExampleComponent-test`, and add your own top-level component to `src/index.js`. New tests must end in `-test.js` to be found.

Dev server runs on port `3001`

Create a minified production bundle with `npm run build`