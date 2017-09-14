// lesson1 作业
1. 类比代码执行流程
老师的意思是让我们用生活中的例子来说明代码执行流程吗？第一节课没赶上，只能靠猜测了，补作业，不废话！
首先代码肯定是为了解决问题的，也就是换种语言描述生活中的需要的场景，并能够高效执行的。比如计算器，比如百度搜索关键词JavaScript，以搜索为例子说明
1、用户打开百度网址；此时通过浏览器和和百度服务器链接上了，服务器端收到用户请求，等待用户输入；
2、用户输入关键字JavaScript点击搜索；此时提交了数据，需要服务器端搜索想要的东西
3、服务器端收到用户的关键字后，解析关键字，比如分词等等，然后根据搜索引擎的算法匹配客户需要的数据，并组装数据，返回数据给用户。（此处理过程是用户来说是黑盒的）
4、浏览器返回服务器端数据给客户。用户得到想要的信息或者链接。

2. 运行环境 （我理解是解析代码的程序，我们应该用工具来运行，比如浏览器／JDK/node.js等等，下面的为抄的，目前了解仅限于字面）
JavaScript有两种运行环境
浏览器运行环境： 基于浏览器的 javascript 前端 JS
Node.js运行环境：基于服务端的 javascript 后端 Node.js

3. V8引擎（更多的时候用浏览器，真没关注过浏览器的实现框架和逻辑）
V8是Google开发的开源JavaScript引擎。
JavaScript 引擎的基本工作是把开发人员写的 JavaScript 代码转换成高效、优化的代码， 这样就可以通过浏览器进行解释甚至嵌入到应用中。


4. 编译器/解释（执行）器 
编译器：将JavaScript语言转换为机器能理解的二进制代码，机器只能读010101的语言
解释（执行）器 ：解析0110101是啥意思，如同人与机器的翻译软件


5. 内置库
使用工具的一部分吧，能够高效处理请求（浏览器）／编译代码（jdk／node.js）等等，都是将一些常用的函数封装，然后方便第三方调用


6. 第三方库
同内置库一样，只是属于第三方，不属于我们使用工具的本身，使用时需要引用

7. 学习JS的方向
当前诉求：看懂别人写的代码，终极目标：实现自己的需求