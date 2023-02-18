## Babel 6

+ [Setting up Babel 6](https://babeljs.io/blog/2015/10/31/setting-up-babel-6)

### Install

+ babel core for compiler
```
npm install --save-dev babel-core babel-cli babel-preset-env babel-polyfill
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
