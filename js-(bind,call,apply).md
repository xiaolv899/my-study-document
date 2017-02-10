#apply/call 区别：

```
function a(x, y) {     
    console.log(x, y);     
    console.log(this);     
    console.log(arguments); 
} 
a.apply(null, [1, 2]); 
a.call(null, 1, 2); 
```
