## Comprehensions

```javascript
var results = (
  for(c of customers)
    if (c.city == "Lyon")
      { name: c.name, age: c.age }
)
```
