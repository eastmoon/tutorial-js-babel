## Babel 7

+ [Babel](https://babeljs.io/docs/en/)
+ [Using babel 7 with node](https://hackernoon.com/using-babel-7-with-node-7e401bc28b04)

#### Install

+ babel core for compiler
```
npm install @babel/core @babel/cli @babel/preset-env @babel/polyfill
```

+ node.js run babel
```
npm install @babel/node
```

#### Preset

+ in packages.json setting babel

```
"babel": {
  "presets": [
    "@babel/env"
  ]
}
```
