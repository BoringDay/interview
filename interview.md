## Http

>1.浏览器缓存原理,请求头
简书：(https://www.jianshu.com/p/54cc04190252)


## js相关

>1.有没有用过闭包，什么情况下用闭包，你为什么要用它

>2.Promise的原理,动手实现链式调用(包含异步操作)

原理：
1.函数方法全部返回this;
2.将执行函数依次加入队列(绑定this)，依次执行，函数最后都要执行下一个函数，返回this
参考了一下:(https://github.com/JanKid/delay)
然后自己实现了一下(https://github.com/BoringDay/tools/tree/master/chain)

3.seajs异步引入js的原理是啥？有没有写过异步引入js

## vue相关

>1.怎么异步引入组件

>2.vue的数据绑定，绑定的数组和对象是怎么处理的，会出现什么问题，vue又是怎么解决的。