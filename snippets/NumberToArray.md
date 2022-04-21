# Convert a Number to an Array

### Code: 
```js
const numberToArray = number => [...`${number}`].map(element => parseInt(element));
```
### Examples:
```js
numberToArray(12345); // [1, 2, 3, 4, 5]
numberToArray(54321); // [5, 4, 3, 2, 1]
```
