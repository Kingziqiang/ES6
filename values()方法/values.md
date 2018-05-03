## Object.values(obj)方法的介绍

1. Object.values()方法返回一个给定对象自己的所有可枚举属性值的数组，值的顺序与使用for...in循环的顺序相同

2. Object.values(obj)
   + obj:被返回可枚举属性值的对象.
   + 返回值:一个包含对象自身的所有可以枚举属性值得数组

3. 属性的顺序与通过手动循环对象的属性值所给出的顺序相同

4. 与Object.key()类似的新函数，但会返回Object自身属性的所有值，排除原型链中的任何值。

## Object.value(obj)与for-in的区别

- 区别在于 for-in 循环枚举原型链中的属性。



