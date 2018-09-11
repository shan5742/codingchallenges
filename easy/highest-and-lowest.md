# Return the Highest and Lowest Numbers

### Challenge

Create a function that accepts a string of space separated numbers and returns the highest and lowest number (as a string).

#### Examples

```
"1 2 3 4 5" ➞ "5 1"

"1 2 -3 4 5" ➞ "5 -3"

"1 9 3 4 -5" ➞ "9 -5"

"13" ➞ "13 13"
```

### Solution
```
function highLow(str) {
	const max = (Math.max(str));
	const min = (Mat.min(str));
}

return "max, min";	
```