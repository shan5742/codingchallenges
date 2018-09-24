# Pi to N Decimal Places

###Challenge

Given a number n, write a function that returns PI to n decimal places.

#### Examples

```
5 ➞ 3.14159

4 ➞ 3.1416

15 ➞ 3.141592653589793
```

#### Notes

n will not be above 15, to keep this challenge simple.
Round up the last digit if the next digit in PI is greater or equal to 5 (see second example above).
The return value must be a number, not a string.

### Solution

```javascript
function myPi(n) {
  return Number(Math.PI.toFixed(n));
}
```
