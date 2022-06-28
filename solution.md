## Return Negative

```js
function opposite(number) {
  if (number > 0) {
    return -number
  } else {
    return number
  }
}
```

## Sum of Positive

```js
let total = 0
for (i = 0; i < arr.length; i++) {
  if (arr[i] > 0) {
    total = total + arr[i]
  }
}
return total
```

## Function 2

```js
const square = (a) => {
  return Math.pow(a, 2)
}
//https://htmlcheatsheet.com/js/
```

## Sum Arrays

```js
function arrayPlusArray(arr1, arr2) {
  let sum = 0
  for (let i = 0; i < arr1.length; i++) sum = sum + arr1[i]
  for (let i = 0; i < arr2.length; i++) sum = sum + arr2[i]
  return sum
}
```

## Reversed Strings

```js
function solution(str){
  return str.split('').reverse().join('');
}
https://htmlcheatsheet.com/js/
```
