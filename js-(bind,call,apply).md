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

#bind：

使用方法同call类似；不同的是bind没有立即调用；bind() 生成的新函数返回后，你想什么时候调就什么时候调
