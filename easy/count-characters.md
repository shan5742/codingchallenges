# Count Instances of a Character in a String

###Challenge

Create a function that takes a character and a string and returns the number of times that character is found in the given string.

#### Examples

```
"a", "edabit" ➞ 1

"c", "Chamber of secrets" ➞ 1

"f", "frank and his friends have offered five foxes for sale" ➞ 7
```

#### Notes

Your output must be case-sensitive (see second example).

### Solution

```javascript
function charCount(myChar, str) {
  return str.split("").filter(char => char === myChar).length;
}
```
