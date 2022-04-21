# Check if all the elements in an Array are equal

### Code:
```js
const areElementsEqual = array => array.every(element => element === array[0]);
```
## Examples:
```js
areElementsEqual([1, 3, 5, 4, 7]); // False
areElementsEqual([3, 3, 3, 3, 3]); // True
```
