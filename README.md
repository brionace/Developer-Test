# Limesharp test

### Task 1: 
```javascript

var arrayA = ['a','b','c'];

function repeats(arrayA){
    var newArr=[];
    for(var j=0;j<3;j++){
        for(var i=0;i<arrayA.length;i++){
            newArr.push(arrayA[i]);
        }
    }
    return newArr;
}
```
### Task 2:
```javascript
var str = "liMeSHArp DeveLoper TEST";

function reformat(str) {
  var j = str.replace(/[aeiou]/gi,'')
  return j[0].toUpperCase() + j(1).toLowerCase();
}
```
### Task 3:
```javascript
var arrayA = [1,0,0,0,0,0,0,0,0,1];

function next_binary_number(arrayA){
    var j = arrayA;  
    for (i = 0; i < arrayA.length; i++) {
      if (arrayA.length - 1 === 1){
        j.push(1);
      }else{
        j.push(0)
      }
      return j;
    }
}
```
