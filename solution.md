## Return Negative

```js
const makeNegative = (num) => {
  if (num > 0) {
    num = -num
  }
  return num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] >= 0) {
      sum = sum + arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
Neither seemed to work in code wars. It is asking to return the square of a number, Im not sure if that means square root, or squared, heres both:

const sqr = (num) => {
  num = Math.sqrt(num)
  return num;
}

const sqr = (num) => {
  num = Math.pow(num,2)
  return num;
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'
  let sum = 0
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i]
  }
  return sum
}
```

## Reversed Strings

```js
function solution(str) {
  let e = ''
  for (let i = str.length - 1; i >= 0; i--) {
    e = e + str[i]
  }
  return e
}
```
