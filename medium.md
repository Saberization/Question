## 中等

#### 1. 在标准的 JavaScript 中， Ajax 异步执行调用基于下面哪一个机制才能实现？(A)

    A:  Event和callback
    B:  多线程操作
    C:  多CPU核
    D:  Deferral和promise

#### 2. 使用CSS的flexbox布局，不能实现以下哪一个效果：(D)

    A:  三列布局，随容器宽度等宽弹性伸缩
    B:  多列布局，每列的高度按内容最高的一列等高
    C:  三列布局，左列宽度像素数确定，中、右列随容器宽度等宽弹性伸缩
    D:  多个宽高不等的元素，实现无缝瀑布流布局

#### 3. 关于HTTP协议，下面哪个说法是正确的？(C)

    A: HTTP协议是有状态协议。
    B: 以下是一个Http链接的response 的响应头： GET /xxx/xxx/js/lib/test.js HTTP/1.1 Host: 127.0.0.1 Connection: keep-alive Pragma: no-cache Cache-Control: no-cache Accept: */*
    C: RESTful 接口中，利用HTTP协议的method字段来描述要对资源操作的方式，比如GET表示获取资源，POST表示新增一个资源，PUT表示更新资源,DELETE 表示删除资源等等。
    D: 一个HTTP请求返回的HTTP状态码中，304表示临时重定向。

#### 4. 以下关于TCP协议说法正确的有? (C)

    A: TCP协议有拥塞控制功能，但是不能进行流量控制
    B: TCP在视频流传输方面取代了UDP的功能
    C: TCP建立连接需要3次握手，3次握手也可能对其造成被flood攻击的可能
    D: TCP是HTTP,FTP,TFTP的底层实现协议

#### 5. 下面关于进程说法正确的是: (C)

    A: 同步进程必定是阻塞的，异步进程必定是非阻塞的
    B: 同步进程必定是非阻塞的，异步进程必定是阻塞的
    C: 进程同步异步，和阻塞非阻塞没有直接关系
    D: 进程同步异步，和阻塞非阻塞有着必然关系

#### 6. 下面关于进程和线程的关系不正确的是: (D)

    A: 线程是进程的一个实体，可作为系统独立调度和分派的基本单位。
    B: 一个进程中多个线程可以并发执行。
    C: 线程可以通过相互之间协同来完成进程所要完成的任务。
    D: 线程之间不共享进程中的共享变量和部分环境。

#### 7. 关于 this 的工作原理，下面 4 种情况的描述哪一个是错误的？（C）

    A: 在全局范围内，this指向全局对象（浏览器下指window）
    B: 对象函数调用时，this指向当前对象
    C: 全局函数调用时，this指向全局函数
    D: 使用new实例化对象时，this指向新创建的对象

#### 8. 关于 css 布局中的 BFC ，描述错误的是 (A)

    A: BFC的区域会与float的元素区域重叠
    B: 计算BFC的高度时，浮动子元素也参与计算
    C: BFC就是页面上的一个隔离的独立容器，容器里面的子元素是不会影响到外面的元素
    D: BFC意为"块级格式化上下文"

#### 9. 下述有关border:none以及border:0的区别，描述错误的是？ (C、D)

    A: border:none表示边框样式无
    B: border:0表示边框宽度为0
    C: 当定义了border:none，即隐藏了边框的显示，实际就是边框宽度为0
    D: 当定义边框时，仅设置边框宽度也可以达到显示的效果

#### 10. 关于javascript，以下选项描述错误的是 (D)

    A:  在原型上扩展的可枚举方法，会被for in循环出来
    B:  使用object.defineProperty可向对象添加或者修改属性
    C:  每个对象都有prototype属性，返回对象类型原型的引用
    D:  通过hasOwnProperty可判断一个对象以及其原型链上是否具有指定名称的属性
    E:  原型链是JS实现继承的一种模型
    F:  For循环是按顺序的，for in 循环是不一定按顺序的

#### 11. 下面哪些语句可以 在JS里判断一个对象strObj是否为String。(A)

    A: strObj instanceof String
    B: typeof strObj == 'string'
    C: strObj in String
    D: 以上答案均不正确

#### 12. 下列关于比较Ajax与Flash的优缺点，相关描述正确的是？(A、B、C、D)

    A：Ajax的优势在意在于开放性，易用性及易于开发
    B：Flash的优势在于多媒体处理，可以更容易的调用浏览器以外的外部资源
    C：Ajax最主要的批评就是它可能破坏浏览器的后退功能
    D：flash 文件经常会很大，用户第一次使用的时候需要忍耐较长的等待时间