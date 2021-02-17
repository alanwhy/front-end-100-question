# 前端 100 问

### 一些链接

原文：[前端 100 问：能搞懂 80%的请把简历给我](https://github.com/yygmind/blog/issues/43)

个人简书整合地址：[前端 100 问](https://www.jianshu.com/c/70e2e00df1b0)

git 地址：[前端 100 问](https://github.com/alanwhy/front-end-100-question)

### 每日一更

- 20210217: [Q83：var、let 和 const 区别的实现原理是什么](/questions/q83-20210217.md)
- 20210216: [Q82：周一算法题之「移动零」](/questions/q82-20210216.md)
- 20210215: [Q81：打印出 1 - 10000 之间的所有对称数](/questions/q81-20210215.md)

#### 第十三周 ⬆

- 20210214: [Q80：介绍下 Promise.all 使用、原理实现及错误处理](/questions/q80-20210214.md)
- 20210213: [Q79：input 搜索如何防抖，如何处理中文输入](/questions/q79-20210213.md)
- 20210212: [Q78：Vue 的父组件和子组件生命周期钩子执行顺序是什么](/questions/q78-20210212.md)
- 20210211: [Q77：算法题「旋转数组」](/questions/q77-20210211.md)
- 20210210: [Q76：输出以下代码运行结果](/questions/q76-20210210.md)

  ```js
    // example 1
    var a={}, b='123', c=123;
    a[b]='b';
    a[c]='c';
    console.log(a[b]);

    ---------------------
    // example 2
    var a={}, b=Symbol('123'), c=Symbol('123');
    a[b]='b';
    a[c]='c';
    console.log(a[b]);

    ---------------------
    // example 3
    var a={}, b={key:'123'}, c={key:'456'};
    a[b]='b';
    a[c]='c';
    console.log(a[b]);
  ```

- 20210209: [Q75：数组里面有 10 万个数据，取第一个元素和第 10 万个元素的时间相差多少](/questions/q75-20210209.md)
- 20210208: [Q74：使用 JavaScript Proxy 实现简单的数据绑定](/questions/q74-20210208.md)

#### 第十二周 ⬆

- 20210207: [Q73：介绍下 BFC、IFC、GFC 和 FFC](/questions/q73-20210207.md)
- 20210206: [Q72：为什么普通 `for` 循环的性能远远高于 `forEach` 的性能，请解释其中的原因。](/questions/q72-20210206.md)
- 20210205: [Q71：实现一个字符串匹配算法，从长度为 n 的字符串 S 中，查找是否存在字符串 T，T 的长度是 m，若存在返回所在位置。](/questions/q71-20210205.md)
- 20210204: [Q70：介绍下 webpack 热更新原理，是如何做到在不刷新浏览器的前提下更新页面的](/questions/q70-20210204.md)
- 20210203: [Q69：如何把一个字符串的大小写取反（大写变小写小写变大写），例如 ’AbC' 变成 'aBc' 。](/questions/q69-20210203.md)
- 20210202: [Q68：如何解决移动端 Retina 屏 1px 像素问题](/questions/q68-20210202.md)
- 20210201: [Q67：随机生成一个长度为 10 的整数类型的数组，例如 [2, 10, 3, 4, 5, 11, 10, 11, 20]，将其排列成一个新数组，要求新数组形式如下，例如 [[2, 3, 4, 5], [10, 11], [20]]](/questions/q67-20210201.md)

#### 第十一周 ⬆

- 20210131: [Q66：ES6 代码转成 ES5 代码的实现思路是什么](/questions/q66-20210131.md)
- 20210130: [Q65：a.b.c.d 和 a['b']['c']['d']，哪个性能更高？](/questions/q65-20210130.md)
- 20210129: [Q64：模拟实现一个 Promise.finally](/questions/q64-20210129.md)
- 20210128: [Q63：如何设计实现无缝轮播](/questions/q63-20210128.md)
- 20210127: [Q62：redux 为什么要把 reducer 设计成纯函数](/questions/q62-20210127.md)
- 20210126: [Q61：介绍下如何实现 token 加密](/questions/q61-20210126.md)
- 20210125: [Q60：已知如下代码，如何修改才能让图片宽度为 300px ？注意下面代码不可修改。](/questions/q60-20210125.md)
  ```html
    <img src="1.jpg" style="width:480px!important;”>
  ```

#### 第十周 ⬆

- 20210124: [Q59：给定两个数组，写一个方法来计算它们的交集。](/questions/q59-20210124.md)
- 20210123: [Q58：箭头函数与普通函数（function）的区别是什么？构造函数（function）可以使用 new 生成实例，那么箭头函数可以吗？为什么？](/questions/q58-20210123.md)
- 20210122: [Q57：分析比较 opacity: 0、visibility: hidden、display: none 优劣和适用场景](/questions/q57-20210122.md)
- 20210121: [Q56：要求设计 LazyMan 类，实现以下功能。](/questions/q56-20210121.md)

  ```js
  LazyMan("Tony");
  // Hi I am Tony

  LazyMan("Tony").sleep(10).eat("lunch");
  // Hi I am Tony
  // 等待了10秒...
  // I am eating lunch

  LazyMan("Tony").eat("lunch").sleep(10).eat("dinner");
  // Hi I am Tony
  // I am eating lunch
  // 等待了10秒...
  // I am eating diner

  LazyMan("Tony")
    .eat("lunch")
    .eat("dinner")
    .sleepFirst(5)
    .sleep(10)
    .eat("junk food");
  // Hi I am Tony
  // 等待了5秒...
  // I am eating lunch
  // I am eating dinner
  // 等待了10秒...
  // I am eating junk food
  ```

- 20210120: [Q55：某公司 1 到 12 月份的销售额存在一个对象里面，如下：{1:222, 2:123, 5:888}，请把数据处理为如下结构：[222, 123, null, null, 888, null, null, null, null, null, null, null]。](/questions/q55-20210120.md)
- 20210119: [Q54：冒泡排序如何实现，时间复杂度是多少，还可以如何改进？](/questions/q54-20210119.md)
- 20210118: [Q53：输出以下代码的执行结果并解释为什么](/questions/q53-20210118.md)
  ```js
  var a = { n: 1 };
  var b = a;
  a.x = a = { n: 2 };
  console.log(a.x);
  console.log(b.x);
  ```

#### 第九周 ⬆

- 20210117: [Q52：怎么让一个 div 水平垂直居中](/questions/q52-20210117.md)
- 20210116: [Q51：Vue 的响应式原理中 Object.defineProperty 有什么缺陷？](/questions/q51-20210116.md)
- 20210115: [Q50：实现 (5).add(3).minus(2) 功能](/questions/q50-20210115.md)
- 20210114: [Q49：为什么通常在发送数据埋点请求的时候使用的是 1x1 像素的透明 gif 图片？](/questions/q49-20210114.md)
- 20210113: [Q48：call 和 apply 的区别是什么，哪个性能更好一些](/questions/q48-20210113.md)
- 20210112: [Q47：双向绑定和 vuex 是否冲突](/questions/q47-20210112.md)
- 20210111：[Q46：输出以下代码执行的结果并解释为什么](/questions/q46-20210111.md)

```js
var obj = {
  2: 3,
  3: 4,
  length: 2,
  splice: Array.prototype.splice,
  push: Array.prototype.push,
};
obj.push(1);
obj.push(2);
console.log(obj);
```

#### 第八周 ⬆

- 20210110：[Q45：HTTPS 握手过程中，客户端如何验证证书的合法性](/questions/q45-20210110.md)
- 20210109：[Q44：介绍 HTTPS 握手过程](/questions/q44-20210109.md)
- 20210108：[Q43：使用 sort() 对数组 [3, 15, 8, 29, 102, 22] 进行排序，输出结果](/questions/q43-20210108.md)
- 20210107：[Q42：实现一个 sleep 函数，比如 sleep(1000) 意味着等待 1000 毫秒，可从 Promise、Generator、Async/Await 等角度实现](/questions/q42-20210107.md)
- 20210106：[Q41：下面代码输出什么](/questions/q41-20210106.md)
  ```js
  var a = 10;
  (function () {
    console.log(a);
    a = 5;
    console.log(window.a);
    var a = 20;
    console.log(a);
  })();
  ```
- 20210105：[Q40：在 Vue 中，子组件为何不可以修改父组件传递的 Prop，如果修改了，Vue 是如何监控到属性的修改并给出警告的。](/questions/q40-20210105.md)
- 20210104：[Q39：介绍下 BFC 及其应用](/questions/q39-20210104.md)

#### 第七周 ⬆

- 20210103：[Q38：下面代码中 a 在什么情况下会打印 1？](/questions/q38-20210103.md)
  ```js
  var a = ?;
  if(a == 1 && a == 2 && a == 3){
  	console.log(1);
  }
  ```
- 20210102：[Q37：为什么 Vuex 的 mutation 和 Redux 的 reducer 中不能做异步操作？](/questions/q37-20210102.md)
- 20210101：[Q36：使用迭代的方式实现 flatten 函数](/questions/q36-20210101.md)
- 20201231：[Q35：请求时浏览器缓存 from memory cache 和 from disk cache 的依据是什么，哪些数据什么时候存放在 Memory Cache 和 Disk Cache 中？](/questions/q35-20201231.md)
- 20201230：[Q34：简单改造下面的代码，使之分别打印 10 和 20。](/questions/q34-20201230.md)
  ```js
  var b = 10;
  (function b() {
    b = 20;
    console.log(b);
  })();
  ```
- 20201229：[Q33：下面的代码打印什么内容，为什么？](/questions/q33-20201229.md)
  ```js
  var b = 10;
  (function b() {
    b = 20;
    console.log(b);
  })();
  ```
- 20201228：[Q32：Virtual DOM 真的比操作原生 DOM 快吗？谈谈你的想法。](/questions/q32-20201228.md)

#### 第六周 ⬆

- 20201227：[Q31：改造下面的代码，使之输出 0 - 9，写出你能想到的所有解法。](/questions/q31-20201227.md)
- 20201226：[Q30：请把俩个数组 [A1, A2, B1, B2, C1, C2, D1, D2] 和 [A, B, C, D]，合并为 [A1, A2, A, B1, B2, B, C1, C2, C, D1, D2, D]](/questions/q30-20201226.md)
- 20201225：[Q29：聊聊 Vue 的双向数据绑定，Model 如何改变 View，View 又是如何改变 Model 的](/questions/q29-20201225.md)
- 20201224：[Q28：cookie 和 token 都存放在 header 中，为什么不会劫持 token？](/questions/q28-20201224.md)
- 20201223：[Q27：关于 const 和 let 声明的变量不在 window 上](/questions/q27-20201223.md)
- 20201222：[Q26：介绍模块化发展历程](/questions/q26-20201222.md)
- 20201221：[Q25：介绍下观察者模式和订阅-发布模式的区别，各自适用于什么场景](/questions/q25-20201221.md)

#### 第五周 ⬆

- 20201220：[Q24：浏览器和 Node 事件循环的区别](/questions/q24-20201220.md)
- 20201219：[Q23：聊聊 Redux 和 Vuex 的设计思想](/questions/q23-20201219.md)
- 20201218：[Q22：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣 Object.prototype.toString.call() 、 instanceof 以及 Array.isArray()](/questions/q22-20201218.md)
- 20201217：[Q21：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化](/questions/q21-20201217.md)
- 20201216：[Q20：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？](/questions/q20-20201216.md)
- 20201215：[Q19：React setState 笔试题，下面的代码输出什么？](/questions/q19-20201215.md)
- 20201214：[Q18：React 中 setState 什么时候是同步的，什么时候是异步的？](/questions/q18-20201214.md)

#### 第四周 ⬆

- 20201213：[Q17：A、B 机器正常连接后，B 机器突然重启，问 A 此时处于 TCP 什么状态](/questions/q17-20201213.md)
- 20201212：[Q16：谈谈你对 TCP 三次握手和四次挥手的理解](/questions/q16-20201212.md)
- 20201211：[Q15：简单讲解一下 http2 的多路复用](/questions/q15-20201211.md)
- 20201210：[Q14：如何实现一个 new](/questions/q14-20201210.md)
- 20201209：[Q13：Promise 构造函数是同步执行还是异步执行，那么 then 方法呢？](/questions/q13-20201209.md)
- 20201208：[Q12：JS 异步解决方案的发展历程以及优缺点](/questions/q12-20201208.md)
- 20201207：[Q11：将数组扁平化并去除其中重复数据，最终得到一个升序且不重复的数组](/questions/q11-20201207.md)

#### 第三周 ⬆

- 20201206：[Q10：异步笔试题：async/await/setTimeout/Promise](/questions/q10-20201206.md)
- 20201205：[Q9：Async/Await 如何通过同步的方式实现异步](/questions/q9-20201205.md)
- 20201204：[Q8：setTimeout、Promise、Async/Await 的区别](/questions/q8-20201204.md)
- 20201203：[Q7：ES5/ES6 的继承除了写法以外还有什么区别？](/questions/q7-20201203.md)
- 20201202：[Q6：请分别用深度优先思想和广度优先思想实现一个拷贝函数？](/questions/q6-20201202.md)
- 20201201：[Q5：介绍下深度优先遍历和广度优先遍历，如何实现？](/questions/q5-20201201.md)
- 20201130：[Q4：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？](/questions/q4-20201130.md)

#### 第二周 ⬆

- 20201129：[Q3：什么是防抖和节流？有什么区别？如何实现？](/questions/q3-20201129.md)
- 20201128：[Q2：['1', '2', '3'].map(parseInt) what & why ?](/questions/q2-20201128.md)
- 20201127：[Q1：写 React / Vue 项目时为什么要在列表组件中写 key，其作用是什么？](/questions/q1-20201127.md)

#### 第一周 ⬆
