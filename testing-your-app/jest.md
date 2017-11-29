# Jest

Testing react-native apps for regression is incredibly daunting as your app grows. It can quickly become a nightmare to test things manually.

Luckily, React Native ships with Jest, one of my favourite testing frameworks.

The basic setup you need to start testing your React Native app with Jest includes: 

**Install the appropriate packages:**

`yarn add jest babel-jest react-test-renderer --dev`

**Modifying your package.json to include the following:**

```
"scripts": {
    "test": "jest"
},
"jest": {
    "preset": "react-
}
    
```

**Add the following to your .babelrc:**

```
{ 
    "presets": ["react-native"]
}
```

now if you run `yarn test`  you should see your tests running.





