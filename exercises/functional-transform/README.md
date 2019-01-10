# Functional Transform

Requirements: transform the data into the highest ranking bar per attribute. For example:

```
{
  "chocolate": "snickers",
  "fruity": "Caramel Apple Pops",
  "caramel": "Sugar Babies",
}
```

You should use no for loops -- you should use `map` and `reduce` to transform
the json data into a single object.

# Sample code to get started
```js
const fs = require('fs');
const contents = fs.readFileSync('./data.json', 'utf8');
const json = JSON.parse(contents)
```

You can then run your code with `node functional-transform.js`

# Submitting

```
levelup submit functional-transform.js
```

# Resources

1. [Guide to Map](https://codeburst.io/learn-understand-javascripts-map-function-ffc059264783)
2. [Guide to Reduce](https://medium.freecodecamp.org/reduce-f47a7da511a9)
