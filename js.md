# js相关

>1.有没有用过闭包，什么情况下用闭包，你为什么要用它

>2.Promise的原理,动手实现链式调用(包含异步操作)

    原理：  
    a.函数方法全部返回this;  
    b.将执行函数依次加入队列(绑定this)，依次执行，函数最后都要执行下一个函数，返回this  

    参考了一下:(https://github.com/JanKid/delay)  
    然后自己实现了一下(https://github.com/BoringDay/tools/tree/master/chain) 

>3.seajs异步引入js的原理是啥？有没有写过异步引入js?

>4.以下输出什么，要想改输出0,1,2,3,4怎么改  
`for(var i=0;i<5;i++){  
    setTimeout(function(){  
        console.log(i)  
    },1000)
}`
