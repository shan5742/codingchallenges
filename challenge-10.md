# Multiply by Length

### Challenge

Create a function to multiply all values in an array by the amount of values in that array.

### Solution

```
function MultiplyByLength(arr) {
	return arr.map(x => x * arr.length);
}
```
