## Mutiple returns

```javascript

var fn = () => {
  return {x: 1, y: 3};
};

var {x, y} = fn();

console.log(x); // 1
console.log(y); // 3

```
