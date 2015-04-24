```javascript
// ES3
var obj = {
    onClick: function() {
        console.log(this);
    },
    init: function() {
        var _this = this; // that, raoul, toto, instance, marty, ...
        document.addEventListener('click', function() {
            _this.onClick();
        });
    }
};
```
