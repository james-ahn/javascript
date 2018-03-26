# ES 6

## rest parameter(...numbers)

- ES5 (using Array.prototype.slice.call)
```
function arr() {
  console.log(arguments); // 유사배열인 [1,2,3,4,5,true,null,undefined]
  var arg = Array.prototype.slice.call(arguments, 2);
  console.log(arg); // [3,4,5,true,null,undefined]
}
arr(1,2,3,4,5,true,null,undefined);
```

- ES6
```
function arr(x , y, ...rest) {
  console.log(rest); //[3,4,5,true,null,undefined]
}
arr(1,2,3,4,5,true,null,undefined);

```


