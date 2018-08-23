

有了Promise对象，就可以将异步操作以同步操作的流程表达出来，避免了层层嵌套的回调函数。

如果某些事件不断地反复发生，一般来说，使用 Stream 模式是比部署Promise更好的选择。

这是因为立即 resolved 的 Promise 是在本轮事件循环的末尾执行，总是晚于本轮循环的同步任务

立即resolve的 Promise 对象，是在本轮“事件循环”（event loop）的结束时，



注意，Promise.reject()方法的参数，会原封不动地作为reject的理由，变成后续方法的参数。这一点与Promise.resolve方法不一致。

函数f是同步的，但是用 Promise 包装了以后，就变成异步执行了。




抛出同步错误，这时你就不得不用try...catch去捕获。    异步错误？可以用promise.catch()进行捕获

1.promise.try()
  a:还可以捕获同步错误    这样同步错误和异步错误就都可以捕获了
  b：同步代码同步执行   异步代码异步执行   提升性能


一种数据结构只要部署了 Iterator 接口，我们就称这种数据结构是“可遍历的”（iterable）。

for...of循环

for...of循环内部调用的是数据结构的Symbol.iterator方法。



类数组对象：
1.符串
2.DOM NodeList 对象
3.arguments对象




事实上，类的所有方法都定义在类的prototype属性上面。   在类的实例上面调用方法，其实就是调用原型上的方法。




























