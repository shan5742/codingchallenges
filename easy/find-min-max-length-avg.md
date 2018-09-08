# Find the Minimum, Maximum, Length and Average Values
### Challenge

Create a function that takes an array of numbers and returns the following statistics:
Minimum Value
Maximum Value
Sequence Length
Average Value

#### Examples
```
[6, 9, 15, -2, 92, 11] ➞ [-2, 92, 6, 21.833333333333332]

[30, 43, 20, 92, 3, 74] ➞ [3, 92, 6, 43.666666666666664]

[4.54, 8.32, 5.20] ➞ [4.54, 8.32, 3, 6.02]
```
### Solution

```
function minMaxLengthAverage(arr) {
  return [	Math.min(...arr), 
          	Math.max(...arr), 
          	arr.length, 
         		arr.reduce((a, b) => a + b) / arr.length];
}
```