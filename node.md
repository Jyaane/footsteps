### Q1: node的内存管理

node把整个内存空间分为新生代和老生代，新生代采用Scavarge算法，消耗资源较大，该算法把新生代的空间分为from-space和to-space

### Q2：node的全局变量

process, buff, console. 定时器相关函数

### Q3：变量提升

var的变量提升

#### let/const

#### 1.暂时性死区。

###### 暂时性死区的本质就是，只要一进入当前作用域，所要使用的变量就已经存在了，但是不可获取，只有等到声明变量的那一行代码出现，才可以获取和使用该变量。

#### 2.块级作用域

### Q4：模块依赖的循环引用

会先进行缓存，exports未完成的对象，

### Q5：事件循环

6个阶段：timer---Io callback---idle/prepare---poll---check---close callback

微任务，在当前阶段的任务队列末尾插入，nextTick,promise

