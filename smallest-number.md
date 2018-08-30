# Find the Smallest Number in an Array

### challenge

Create a function that takes an array of numbers and returns the smallest number in the set.

#### Examples
```
[34, 15, 88, 2] ➞ 2

[34, -345, -1, 100] ➞ -345

[-76, 1.345, 1, 0] ➞ -76

[0.4356, 0.8795, 0.5435, -0.9999] ➞ -0.9999

[7, 7, 7] ➞ 7
```

#### Notes
Test cases contain decimals.

### Solution

```
function findSmallestNum(arr) {
	const min = arr.reduce((a, b) => Math.min(a, b));
  return min;
} 
```