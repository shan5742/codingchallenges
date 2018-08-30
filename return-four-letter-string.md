# Return the Four Letter Strings

### Challenge

Create a function that takes an array of strings. Return all words in the array that are exactly four letters.

#### Examples
```
["Ryan", "Kieran", "Jason", "Matt"] ➞ ["Ryan", "Matt"]

["Tomato", "Potato", "Pair"] ➞ ["Pair"]

["Kangaroo", "Bear", "Fox"] ➞ ["Bear"]
```

**Notes**
You can expect valid strings for all test cases.

### Solution

```
function isFourLetters(arr) {
	const result = arr.filter(word => word.length === 4);
	return result
}
```