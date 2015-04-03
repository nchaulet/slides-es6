```javascript
// ES5
var obj = {
    onClick: function() {
        console.log(this);
    },
    init: function() {
        document.addEventListener('click', function() {
            this.onClick();
        }.bind(this));
    }
};
```
