# Head-Body-Tail

### Challenge

Write a function that takes four string arguments. You will be comparing the first string to the three next strings. Verify if the first string starts with the second string, includes the third string, and ends with the fourth string. If the first string passes all checks, return the string "My head, body, and tail.", otherwise, return "Incomplete.".

#### Examples

```
"Onomatopeia", "on", "mato", "ia" ➞ "Incomplete."

"Centipede", "Cent", "tip", "pede" ➞ "My head, body, and tail."

"apple", "AP", "PPL", "LE" ➞ "Incomplete."
```

#### Notes

You'll always get exactly four strings as arguments.
Tests are case sensitive.

### My Solution

```
function verifySubstrs(mainStr, head, body, tail) {
  if(mainStr.startsWith(head)){
    if(mainStr.endsWith(tail)){
      if(mainStr.includes(body)){
      	return "My head, body, and tail.";
      }
    }
  }
	return "Incomplete.";
}
```

#### A Better Solution

I have since found a much better way to do this:

```
function verifySubstrs(mainStr, head, body, tail) {
  return mainStr.startsWith(head) && mainStr.includes(body) && mainStr.endsWith(tail) ? "My head, body, and tail." : "Incomplete.";
}
```
