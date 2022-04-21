# Filter Falsy Values from an Array

### Code:
```js
const removeFalsyValues = element => element.filter(Boolean);
```
### Examples: 
```js
removeFalsyValues([0, 1, 2, null, 3, 4, 5, 6]) // [1,2,3,4,5,6]
removeFalsyValues([0, 1, 2, null, 3, false, undefined, 4, 5, 6]) // [1,2,3,4,5,6]
```
