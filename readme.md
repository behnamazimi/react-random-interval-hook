# Random Interval Hook
Make an interval with random time delay specified with min and max delay between each call. 

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