# substring

子串被用来截取一部分字符串。
语法:  substring(first_index,last_index). 

```js
var a = 'Hello world!';
document.write(a.substring(1,6));
```

上面的代码片段产生了 ```'ello '``` .注意 ‘w'(索引6) 不是这个子串的一部分。

我们也可以这样,
```js
var a = 'Hello world!';
document.write(a.substring(2));
```

 ``` 'llo world!'```这产生从索引2到末尾的字符串。``` 'llo world!'```

##substr

另一个方法substr()稍微有点不同。区别在于第二个参数，

it gives the number of characters.
```js
var a = 'Hello world!';
document.write(a.substr(1,6));
```

从索引 1 ('e')，切片出长度为 6 的字符串，也就是输出 ```ello w```
