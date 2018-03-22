# Useful-JS-Array-methods
Some simple Javascript methods for arrays

`Array.prototype.filter(i => /*condition*/); `

##### returns an array filtered according to a condition

`Array.prototype.map(i => i.property ); `

##### returns an array with the same length with just the properties we want

`Array.prototype.sort((a,b) => a >= b ? 1 : -1 ); `

##### sort the array values according to a condition

```Array.prototype.reduce((total, i) => { 
  return total + i;
}, 0);```

##### makes the Sum of elements in array

`Array.prototype.some(i => /* condition */); `

##### returns a boolean if only one verifies the condition

`Array.prototype.every(i => /* condition */); `

##### returns a boolean if all verify the condition

`Array.prototype.find(i => /* condition */); `

##### returns the first element with the condition

`Array.prototype.findIndex(i => /* condition */); `

##### returns the index of first element that satisfies the condition

`Array.prototype.splice(index, howmany, e1, e2, ... ) `

##### if howmany = 0 no element will be removed  e1 and e2 are the elements to add, then adds the rest