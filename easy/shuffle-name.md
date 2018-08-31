# Shuffle the Name

### Challenge

Create a function that accepts a string (of a persons first and last name) and returns a string with the first and last name swapped.

### Solution

```
function nameShuffle(str){
  return str.split(' ').reverse().join(' ');
}
```

This challenge was completed by combining the split and join method.