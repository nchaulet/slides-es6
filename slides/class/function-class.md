## Class in ES5

```javascript
var Car = function(color) {
    this.color   = color;
    this.counter = 0;
};

Car.prototype.drive = function(distance) {
    this.counter += distance;
};

```
