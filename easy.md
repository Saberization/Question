## 简单

#### 1. 下面结果为真的表达式是：(C)

    A:  null instanceof Object
    B:  null === undefined
    C:  null == undefined
    D:  NaN == NaN

#### 2. 以下javascript代码，在浏览器中运行的结果是：

```js
var arrTemp = [1, 2, 3];

arrTemp.shift();
arrTemp.push(1);
arrTemp.unshift(2);

var arrNew = arrTemp.concat([1, 2]);

console.log(arrNew);
```

    A: [2,2,3,1,1,2]
    B: [2,1,2,1,1,2]
    C: [2,2,3,1,[1,2]]
    D: [2,1,2,1,[1,2]]

#### 3. 以下javascript代码，输出结果为：

```js
var person = {
    fname: 'John',
    lname: 'Doe',
    age: 25
};
var txt = '';

for (key in person) {
    txt += person[key];
}

alert(txt);
```

    A:  JohnDoe25
    B:  fname:"John",lname:"Doe",age:25
    C:  fname:John,lname:Doe,age:25
    D:  fnamelnameage

#### 4. 白屏时间first paint 和可交互时间dom ready的关系是？(A)

    A:  先触发first paint，后触发dom ready
    B:  先触发dom ready，后触发first paint
    C:  一起触发
    D:  没关系

#### 5. 下列描述中，关于 js 函数定义方式，正确的是 (C)

    A:  function add(a,b){return a+b;}函数表达式
    B:  var add=new Function(‘a’,’b’,’return a+b’)函数表达式
    C:  function add(a,b){return a+b;}函数声明
    D:  var add=function(a,b){return a+b;}函数声明
    E:  var add=new Function(‘a’,’b’,’return a+b’);函数声明

#### 6. 下面符合一个有效的javascript变量定义规则的是？(A)

    A:  _$te$t2
    B:  with
    C:  a bc
    D:  2a

#### 7. 下面有关javascript系统方法的描述，错误的是？(B)

    A:  parseFloat方法：该方法将一个字符串转换成对应的小数
    B:  isNaN方法：该方法用于检测参数是否为数值型，如果是，返回true，否则，返回false。
    C:  escape方法： 该方法返回对一个字符串编码后的结果字符串
    D:  eval方法：该方法将某个参数字符串作为一个JavaScript执行

#### 8. 只能输入零和非零开头的数字，正确的正则表达式是 (A)

    A:  ^(0|[1-9][0-9]*)$
    B:  ^(0|[1-9][1-9]*)$
    C:  ^(0|[1-9][0-9])$
    D:  ^\+[1-9][0-9]*$

#### 9. 在准备XMLHttpRequest对象时，在send()前需要调用哪个方法？(B)

    A:  prepare ()
    B:  open ()
    C:  init ()
    D:  build ()

#### 10. 请问在javascript程序中,alert(undefined==null)的输出结果是？(C)

    A: null
    B: undefined
    C: true
    D: false
    E: 以上答案都不正确

#### 11. 在前提：var arr = [1,3,2] 下，下面哪个操作会返回一个数组，并且不是arr？(C)

    A:  arr.push(3)
    B:  arr.reverse()
    C:  [].concat.call(arr, [])
    D:  [].sort.call(arr)

#### 12. 以下描述错误的是 (A)

    A:  cookie以及loaclStorage都会伴随着http请求发送到服务器
    B:  get提交的url会有长度的限制，而post提交的数据则可以比较大
    C:  在javascript中可以操作cookie
    D:  javascript在浏览器的执行是单线程的
    E:  html5中的新增存储方式包括localStorage/sessionStorage

#### 13. 关于 this 的工作原理，下面 4 种情况的描述哪一个是错误的？(C)

    A:  在全局范围内，this指向全局对象（浏览器下指window）
    B:  对象函数调用时，this指向当前对象
    C:  全局函数调用时，this指向全局函数
    D:  使用new实例化对象时，this指向新创建的对象

#### 14. 以下 javascript 代码，在浏览器中运行的结果是 (A)

```js
var foo = {
    n: 1
};

(function(foo) {
    console.log(foo.n);
    foo.n = 3;

    var foo = {
        n: 2
    };

    console.log(foo.n);
}(foo));

console.log(foo.n);
```

    A:  1 2 3
    B:  undefined 2 1
    C:  报错
    D:  1 2 1

#### 15. 以下代码输出结果为：(D)

```js
(function() {
    var a = b = 5;
})();

console.log(b);
console.log(a);
```

    A:  5，5
    B:  undefined，undefined
    C:  5，undefined
    D:  5，Uncaught ReferenceError: a is not defined

#### 16. 如何判断一个js对象是否是Array,arr为要判断的对象，其中最准确的方法是？ (D)

    A:  typeof(arr) // 永远返回
    B:  arr instanceof Array
    C:  arr.toString==='[object Array]';
    D:  Object.prototype.toString.call(arr) === '[object Array]';

#### 17. 以下代码弹出的结果是？(B)

```js
var name = 'World!';

(function() {
    var name;

    if (typeof name === 'undefined') {
        name = 'Saber';
        console.log('see you ' + name);
    }
    else {
        console.log('hello ' + name);
    }
}());
```

    A: Hello World!
    B: see you Saber
    C: Hello Saber
    D: see you World!

#### 18. 以下代码输出的结果是？(D)

```js
console.log(([]) ? true : false); 
console.log(([] == false ? true : false)); 
console.log(({} == false) ? true : false) 
```

    A:  false true true
    B:  true true true
    C:  true false true
    D:  true true false

#### 19. 下面求a中最大值正确的是 (D)

```js
var a = [1,4,5,2,9];
```

    A: Math.max(a)
    B: Array.max(a)
    C: Math.max.call(null, a)
    D: Math.max.apply(null, a)
    E: 以上均不是

#### 20. 以下选项中哪些属于原生 js 操作数组的方法 (A、B、D、E、F、G)

    A:  splice
    B:  shift
    C:  resort
    D:  sort
    E:  pop
    F:  push
    G:  unshift

#### 21. 下面哪些属于JavaScript的typeof运算符的可能结果：(A、C、F、G)

    A: symbol
    B: NaN
    C: boolean
    D: null
    E: array
    F: undefined
    G: string

#### 22. 下列事件哪个不是由鼠标触发的事件（D）

    A:  click
    B:  contextmenu
    C:  mouseout
    D:  keydown

#### 23. 下面关于CSS布局的描述，不正确的是？(D)

    A:  块级元素实际占用的宽度与它的 width 属性有关；
    B:  块级元素实际占用的宽度与它的 border 属性有关；
    C:  块级元素实际占用的宽度与它的 padding 属性有关；
    D:  块级元素实际占用的宽度与它的 background 属性有关。

#### 24. 下列哪个操作是W3C标准定义的阻止事件向父容器传递：(C)

    A:  e.preventDefault()
    B:  e.cancelBubble=true
    C:  e.stopPropagation()
    D:  e.stopImmediatePropagation()

#### 25. 以下关于盒子模型描述正确的是：(A)

    A: 标准盒子模型中：盒子的总宽度 ＝ 左右margin + 左右border + 左右padding + width
    B: IE盒子模型中：盒子总宽度 ＝ 左右margin + 左右border + width
    C: 标准盒子模型中：盒子的总宽度 ＝ 左右margin + 左右border + width
    D: IE盒子模型中：盒子总宽度 ＝ width

#### 26. 关于HTML语义化，以下哪个说法是正确的？()

    A: 语义化的HTML有利于机器的阅读，如PDA手持设备、搜索引擎爬虫；但不利于人的阅读
    B: Table 属于过时的标签，遇到数据列表时，需尽量使用 div 来模拟表格
    C: 语义化是HTML5带来的新概念，此前版本的HTML无法做到语义化
    D: header、article、address都属于语义化明确的标签

#### 27. 