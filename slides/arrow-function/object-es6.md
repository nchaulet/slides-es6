```javascript
// ES6
var obj = {
    onClick() {
        console.log(this);
    },
    init() {
        document.addEventListener('click', () => {
            this.onClick()
        });
    }
};
```
