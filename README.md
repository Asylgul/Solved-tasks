# Solved-tasks1

* task 1
```javascript
const a = 123;
```

[Square(n) Sum](https://www.codewars.com/kata/515e271a311df0350d00000f)
 ```javascript
function squareSum(numbers){
  return numbers.reduce((sum, el) => sum + el * el, 0);
}
```

**To square(root) or not to square(root)** (https://www.codewars.com/kata/57f6ad55cca6e045d2000627)
```javascript
function squareOrSquareRoot(array) {
let arr = [];
for( let i= 0; i < array.length; i++){
  if(Math.sqrt(array[i]) % 1 === 0){
    arr.push(Math.sqrt(array[i]))
  }else{
    arr.push(Math.pow(array[i],2));
    }
}
return arr;
}
```


              