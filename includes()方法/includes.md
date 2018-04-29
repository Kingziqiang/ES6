
## Array.prototype.includes()方法的介绍

1. includes(searchElement[, fromIndex])方法用来判断一个数组是否包含一个指定的值，如果包含则返回true，否则返回false。
   + searchElement:需要查找的元素
   + fromIndex:从该索引处开始查找 searchElement。如果为负值，则按升序从 array.length + fromIndex 的索引开始搜索。默认为 0
   + 如果fromIndex 大于等于数组长度 ，则返回 false 。该数组不会被搜索,如果小于0则整个数组都会被搜索

   + 返回值: Boolean

2. include()是一个通用的方法，并不要求this一定是一个数组对象,它可以被用于其他对象上,比如类数组。

## include()和indexOf()的区别

- includes()方法支持查找NaN

- includes()方法返回的是Boolean,indexOf()方法返回要查找值得索引,没有该值得话返回-1;

- 这两个方法都支持查找undefined;