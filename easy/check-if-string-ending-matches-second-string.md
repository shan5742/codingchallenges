# Check if String Ending Matches Second String

### Challenge

Create a function that takes two strings and returns true if the first argument ends with the second argument; otherewise return false .

#### Rules

Take two strings as arguments.
Determine if second string matches ending of first string.
Return boolean value.

#### Examples

```
"abc", "bc" ➞ true

"abc", "d" ➞ false

"samurai", "zi" ➞ false

"feminine", "nine" ➞ true

"convention", "tio" ➞ false
```

### Solution

```
function checkEnding(str1, str2) {
  return str1.endsWith(str2);
}
```