# Flip the Boolean

### Challenge

Create a function that reverses a boolean value and returns the string "boolean expected" if another variable type is given.

### Solution

```
function reverse(bool) {
	return (bool = bool) ? "false" : "true";
}

 let result = reverse(true);
 return result;
```