# Repeating Letters

### Challenge

Create a function that takes a string and returns a string in which each character is repeated once.

#### Examples

"String" ➞ "SSttrriinngg"

"Hello World!" ➞ "HHeelllloo  WWoorrlldd!!"

"1234!_ " ➞ "11223344!!__  "

### Solution

```
function doubleChar(str) {
	return(str.split('').map(v => v.repeat(2)).join(''));
}
```