## Babel 7

+ [Babel](https://babeljs.io/docs/en/)
+ [Using babel 7 with node](https://hackernoon.com/using-babel-7-with-node-7e401bc28b04)

### Install

+ babel core for compiler
```
npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/polyfill
```

+ node.js run babel
```
npm install--save-dev  @babel/node
```

### Setting

+ in packages.json setting babel presets

```
"babel": {
  "presets": [
    "@babel/env"
  ]
}
```

### Execute

```
npm start
```
