# Return the Factorial

### Challenge

Create a function that takes an integer and returns the factorial of that integer. That is, the integer multiplied by all positive lower integers.

#### Examples
```
3 ➞ 6

5 ➞ 120

13 ➞ 6227020800
```

#### Notes
```
Assume all inputs are >= 0.
0! = 1.
```

### Solution

```
function factorial(int) {
 if(int < 1) {
   return 1;
 } else {
   return int * factorial(int-1);
 }
}
```

A much better way than my solution above can be found below:

```
const factorial = num => num === 1 ? num : num * factorial(num - 1);
```