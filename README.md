
# apply 的应用总结
## 1、当数组中的值都为数字时候可以取出最大值
- Math.max.apply(null,[1,30,41])
- （ps:Math.max方法的参数中只要有一个值被转为NaN,则该方法直接返回NaN ，且null转化为1，undefined转化为NaN，0比-0大）

## 2、扁平化二维数组
- Array.prototype.concat.apply([], [[1], [2],4])
- 输出 [1,2,4]
