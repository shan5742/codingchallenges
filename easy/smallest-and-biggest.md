# Find the Smallest and Biggest Numbers

###Challenge 

Create a function that takes an array of numbers and return both the minimum and maximum numbers, in that order.

#### Examples
```
[1, 2, 3, 4, 5] ➞ [1, 5]

[2334454, 5] ➞ [5, 2334454]

[1] ➞ [1, 1]
```

### Solution
```
function minMax(arr) {
	const min = arr.reduce((a, b) => Math.min(a, b));
	const max = arr.reduce((b, a) => Math.max(b, a));
	return [min, max]
}
```