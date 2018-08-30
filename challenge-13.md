# Reverse the Order of a String

### Challenge

Create a function that takes a string as its argument and returns the string in reversed order.
#### Examples
```
"Hello World" ➞ "dlroW olleH"

"The quick brown fox." ➞ ".xof nworb kciuq ehT"

"Edabit is really helpful!" ➞ "!lufpleh yllaer si tibadE"
```

#### Notes

You can expect a valid string for all test cases.

### Solution

```
function reverse(str) {
    let splitString = str.split(""); 
    let reverseArray = splitString.reverse(); 
    let joinArray = reverseArray.join("");
	  return joinArray; 
}
```