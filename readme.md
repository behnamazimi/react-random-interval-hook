# Random Interval Hook

### Installation

Using npm:
```
npm install react-random-interval-hook
```

Using yarn:
```
yarn add react-random-interval-hook  
```


### Exmaple

```javascript
useRandomInterval((stop) => {
  // do what you want
  
  if (stopCondition) {
    stop();
  }
}, 1000, 2000); // interval between 1000 and 2000 ms
```

### License

MIT