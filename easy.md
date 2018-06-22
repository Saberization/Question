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

#### 7. 下面有关javascript系统方法的描述，错误的是？

    A:  parseFloat方法：该方法将一个字符串转换成对应的小数
    B:  isNaN方法：该方法用于检测参数是否为数值型，如果是，返回true，否则，返回false。
    C:  escape方法： 该方法返回对一个字符串编码后的结果字符串
    D:  eval方法：该方法将某个参数字符串作为一个JavaScript执行