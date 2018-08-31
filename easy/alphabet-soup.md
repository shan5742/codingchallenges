# Alphabet Soup

### Challenge

Create a function that takes a string and returns a string with its letters in alphabetical order.

### Solution

```
function AlphabetSoup(str) {
	let arr = str.split('');
	let sorted = arr.sort();
  return sorted.join('');	
}
```