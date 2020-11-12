# Javascript

## javascript简介

### 简介

JavaScript 是脚本语言

JavaScript 是一种轻量级的编程语言。

JavaScript 是可插入 HTML 页面的编程代码。

JavaScript 插入 HTML 页面后，可由所有的现代浏览器执行。

JavaScript 很容易学习。

### 能做的事情

对事件反应

改变html中的内容

改变html图像

改变 HTML 样式

验证输入

### 与java的关系

JavaScript 与 Java 是两种完全不同的语言，无论在概念上还是设计上。
 Java（由 Sun 发明）是更复杂的编程语言。

ECMA-262 是 JavaScript 标准的官方名称。

 JavaScript 由 Brendan Eich 发明。它于 1995 年出现在 Netscape 中（该浏览器已停止更新），并于 1997 年被 ECMA（一个标准协会）采纳

### ECMAScript版本

JavaScript 已经由 ECMA（欧洲电脑制造商协会）通过 ECMAScript 实现语言的标准化。

| 年份 | 名称           | 描述                                               |
| ---- | -------------- | -------------------------------------------------- |
| 1997 | ECMAScript 1   | 第一个版本                                         |
| 1998 | ECMAScript 2   | 版本变更                                           |
| 1999 | ECMAScript 3   | 添加正则表达式  添加 try/catch                     |
|      | ECMAScript 4   | 没有发布                                           |
| 2009 | ECMAScript 5   | 添加 "strict mode"，严格模式 添加 JSON 支持        |
| 2011 | ECMAScript 5.1 | 版本变更                                           |
| 2015 | ECMAScript 6   | 添加类和模块                                       |
| 2016 | ECMAScript 7   | 增加指数运算符 (**)  增加 Array.prototype.includes |

ECMAScript 6 也称为 ECMAScript 2015。

ECMAScript 7 也称为 ECMAScript 2016。

## JavaScript用法

### 标签

如果想要在html界面中插入JavaScript，就要使用标签

```
<script>...</script>
此标签会告诉浏览器JavaScript从哪里开始在哪里结束
```

### 函数与事件

通常我们把JavaScript代码放入函数中，就可以在事件发生时调用该函数。

### 在head或body的JavaScript

您可以在 HTML 文档中放入不限数量的脚本。

脚本可位于 HTML 的 body 或 head 部分中，或者同时存在于两个部分中。

通常的做法是把函数放入 head 部分中，或者放在页面底部。这样就可以把它们安置到同一处位置，不会干扰页面的内容。

### 外部的JavaScript

也可以把脚本保存到外部文件中。外部文件通常包含被多个网页使用的代码。

外部 JavaScript 文件的文件扩展名是 .js。

如需使用外部文件，请在 script 标签的 "src" 属性中设置该 .js 文件

```
<script src="myScript.js"></script>
```

**注意：**外部脚本不能包含JavaScript标签。

## JavaScript输出

### 显示数据

JavaScript没有任何打印或者输出的函数，但是可以通过不同的方式输出数据。

- 使用 **window.alert()** 弹出警告框。
- 使用  **document.write()** 方法将内容写到 HTML 文档中。
- 使用 **innerHTML** 写入到 HTML 元素。
- 使用 **console.log()** 写入到浏览器的控制台。

## JavaScript语法

### 字面量

在编程语言中，一般固定值称为字面量（常量），如3.14。

**数字（Number）字面量** 可以是整数或者是小数，或者是科学计数(e)。

```
3.14
```

**字符串（String）字面量** 可以使用单引号或双引号:

```
"wowowo"
'miao'
```

**表达式字面量** 用于计算：

```
5+6
```

**数组（Array）字面量** 定义一个数组：

```
[40, 100, 1, 5, 25, 10]
```

**对象（Object）字面量** 定义一个对象：

```
{firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"}
```

**函数（Function）字面量** 定义一个函数：

```
function myFunction(a, b) { return a * b;}
```

### 变量

在编程语言中，变量用于存储数据值。

JavaScript 使用关键字 **var** 来定义变量， 使用等号来为变量赋值：

```
var x,length;
```

### 操作符

JavaScript使用**算术运算符**来计算值；

使用**赋值运算符**来给变量赋值。

### 语句

在 HTML 中，JavaScript 语句向浏览器发出的命令。

语句是用分号分隔。

### 注释

```
// 这是注释
/*多行注释
多行注释
多行注释*/
```

### JavaScript数据类型

- 数字
- 字符串
- 数组
- 对象

等

### 函数

JavaScript语句可以写在函数内，函数可以重复引用。

### 大小写

JavaScript对字母大小写敏感

### 字符集

JavaScript 使用 Unicode 字符集。

Unicode 覆盖了所有的字符，包含标点等字符。

### 小知识

JavaScript 中，常见的是驼峰法的命名规则，如 lastName (而不是lastname)。

## JavaScript语句

### 简介

JavaScript 语句是发给浏览器的命令。

这些命令的作用是告诉浏览器要做的事情。

### 分号

用于分隔JavaScript语句，通常我们在每条可执行语句的结尾添加分号。

### 代码

JavaScript 代码是 JavaScript 语句的序列。

浏览器按照编写顺序依次执行每条语句。

### 代码块

JavaScript 可以分批地组合起来。

代码块以左花括号开始，以右花括号结束。

代码块的作用是一并地执行语句序列。

### 语句表示符

JavaScript 语句通常以一个 **语句标识符** 为开始，并执行该语句。

语句标识符是保留关键字不能作为变量名使用。

| 语句         | 描述                                                         |
| ------------ | ------------------------------------------------------------ |
| break        | 用于跳出循环。                                               |
| catch        | 语句块，在 try 语句块执行出错时执行 catch 语句块。           |
| continue     | 跳过循环中的一个迭代。                                       |
| do ... while | 执行一个语句块，在条件语句为 true 时继续执行该语句块。       |
| for          | 在条件语句为 true 时，可以将代码块执行指定的次数。           |
| for ... in   | 用于遍历数组或者对象的属性（对数组或者对象的属性进行循环操作）。 |
| function     | 定义一个函数                                                 |
| if ... else  | 用于基于不同的条件来执行不同的动作。                         |
| return       | 退出函数                                                     |
| switch       | 用于基于不同的条件来执行不同的动作。                         |
| throw        | 抛出（生成）错误 。                                          |
| try          | 实现错误处理，与 catch 一同使用。                            |
| var          | 声明一个变量。                                               |
| while        | 当条件语句为 true 时，执行语句块。                           |

### 空格

JavaScript会忽略多余的空格。通过增加空格可以来提高程序的可读性。

### 折行

可以在文本字符串中使用反斜杠对代码行进行换行。

```
document.write("你好 \
世界!");
```

### 知识点

JavaScript 是脚本语言，浏览器会在读取代码时，逐行地执行脚本代码。而对于传统编程来说，会在执行前对所有代码进行编译。

## 变量

### 定义

变量是存储信息的容器。

### 命名

- 变量必须以字母开头
- 变量也能以 $ 和 _ 符号开头（不过我们不推荐这么做）
- 变量名称对大小写敏感（y 和 Y 是不同的变量）

### 声明

在 JavaScript 中创建变量通常称为"声明"变量。 

我们使用 var 关键词来声明变量：

```
var miaomiaomiao;
```

## 数据类型

### 简介

JavaScript 变量还能保存其他数据类型，比如文本值 (name="Bill Gates")。

在 JavaScript 中，类似 "Bill Gates" 这样一条文本被称为字符串。

JavaScript 变量有很多种类型，但是现在，我们**只关注数字和字符串。**

当您向变量分配文本值时，应该用双引号或单引号包围这个值。

当您向变量赋的值是数值时，不要使用引号。如果您用引号包围数值，该值会被作为文本来处理。

### 基本类型

**值类型(基本类型)**：字符串（String）、数字(Number)、布尔(Boolean)、对空（Null）、未定义（Undefined）、Symbol。

**引用数据类型**：对象(Object)、数组(Array)、函数(Function)。

**另外** ：symbol是ES6 引入了一种新的原始数据类型，表示独一无二的值。

### 动态类型（JavaScript是弱类型语言）

JavaScript 拥有动态类型。这意味着相同的变量可用作不同的类型：

```
var a=5；
var b=5.3;
```

### 字符串

字符串是存储字符（比如 "Bill Gates"）的变量。

字符串可以是引号中的任意文本。您可以使用单引号或双引号：

```
var carname="Volvo XC60";
var carname='Volvo XC60';
```

### 数字

JavaScript只有一种数字类型，极大极小的数字可以通过科学计数法来书写。

### 布尔

布尔只能有两个值：true和false

### 数组

下面的代码创建名为 cars 的数组：

var cars=new Array();
 cars[0]="Saab";
 cars[1]="Volvo";
 cars[2]="BMW";

或者 (condensed array):

var cars=new Array("Saab","Volvo","BMW");

或者 (literal array)：

```
var cars=["Saab","Volvo","BMW"]; 
```

### 对象

对象由花括号分隔。在括号内部，对象的属性以名称和值对的形式 (name : value) 来定义。属性由逗号分隔：

var person={firstname:"John", lastname:"Doe", id:5566};

上面例子中的对象 (person) 有三个属性：firstname、lastname 以及 id。

空格和折行无关紧要。声明可横跨多行：

var person={
 firstname : "John",
 lastname : "Doe",
 id    : 5566
 };

对象属性有两种寻址方式：

```
name=person.lastname;
name=person["lastname"];
```

### Undefined 和 Null

Undefined 这个值表示变量不含有值。

可以通过将变量的值设置为 null 来清空变量。

### 声明变量类型

当声明新变量时，可以使用关键词new来声明其类型

```
var carname=new String;
var x=      new Number;
var y=      new Boolean;
var cars=   new Array;
var person= new Object;
```

### 小知识

JavaScript 变量均为对象。当您声明一个变量时，就创建了一个新的对象。

## 对象

### 简介

对象包括属性和行为，几乎JavaScript中所有变量都是对象。

### 定义

你可以使用字符串来定义和创建JavaScript对象

```
var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```

### 对象属性

java是键值对的容器

通常写法为 **name：value**（键与值以冒号分割）

**键值对**在JavaScript对象中通常称为对象属性。

对象键值对的写法类似于：

- PHP 中的关联数组
- Python 中的字典
- C 语言中的哈希表
- Java 中的哈希映射
- Ruby 和 Perl 中的哈希表

### 访问对象属性

```
两种方法
person.lastName;
person["lastName"]; 
```

### 对象方法

对象的方法定义了一个函数，并作为对象的属性存储。 

对象方法通过添加 () 调用 (作为一个函数)。

```
常见对象方法
methodName : function() {
    // 代码 
}
```

### 访问对象方法

该实例访问了 person 对象的 fullName() 方法:

```
name = person.fullName();
```

如果你要访问 person 对象的 fullName 属性，它将作为一个定义函数的字符串返回：

```
name = person.fullName;
```

## JavaScript函数

### 简介

函数是由事件驱动的或者当它被调用时执行的可重复使用的代码块

### 函数语法

函数就是包裹在花括号中的代码块，前面使用了关键词 function：

```
function functionname()
{
    // 执行代码
}
```

当调用该函数时，会执行函数内的代码。

可以在某事件发生时直接调用函数（比如当用户点击按钮时），并且可由 JavaScript 在任何位置进行调用。

### 调用带参数的函数

在调用函数时，您可以向其传递值，这些值被称为参数。

这些参数可以在函数中使用。

```
调用：
myFunction(argument1,argument2)
```

```
声明：
function myFunction(var1,var2)
{
代码
}
```

### 带有返回值的函数

return x；

### 局部变量

在函数里的变量，随函数结束而被删除。

### 全局变量

在函数外声明的变量，网页上所有的脚本和函数都能访问它。

## JavaScript事件

### 简介

发生在HTML上元素的事情就是事件。

### HTML事件

 HTML 事件可以是浏览器行为，也可以是用户行为。

以下是 HTML 事件的实例：

-  HTML 页面完成加载
-  HTML input 字段改变时
-  HTML 按钮被点击

通常，当事件发生时，你可以做些事情。

在事件触发时 JavaScript 可以执行一些代码。

HTML 元素中可以添加事件属性，使用 JavaScript 代码来添加 HTML 元素。

```
<some-HTML-element some-event='JavaScript 代码'>
```

```
<some-HTML-element some-event="JavaScript 代码">
```

### 常见事件

| 事件        | 描述                         |
| ----------- | ---------------------------- |
| onchange    | HTML 元素改变                |
| onclick     | 用户点击 HTML 元素           |
| onmouseover | 用户在一个HTML元素上移动鼠标 |
| onmouseout  | 用户从一个HTML元素上移开鼠标 |
| onkeydown   | 用户按下键盘按键             |
| onload      | 浏览器已完成页面的加载       |

### JavaScript可以做什么

事件可以用于处理表单验证，用户输入，用户行为及浏览器动作:

- 页面加载时触发事件
- 页面关闭时触发事件
- 用户点击按钮执行动作
- 验证用户输入内容的合法性
- 等等 ...

可以使用多种方法来执行 JavaScript 事件代码：

- HTML 事件属性可以直接执行 JavaScript 代码
- HTML 事件属性可以调用 JavaScript 函数
- 你可以为 HTML 元素指定自己的事件处理程序
- 你可以阻止事件的发生。
- 等等 ...

# JavaScript字符串

### 简介

JavaScript字符串用于存储和处理文本。

### 字符串

**存储**

```
var carname = "Volvo XC60";
var carname = 'Volvo XC60';
```

**索引位置：**你可以使用索引位置来访问字符串中每个字符。

```
var character = carname[7];
```

**字符串中的引号**

可以在字符串中使用与字符串引号不同的引号，也可以在字符串中添加转义字符来使用引号：

```
var answer = "It's alright";
var answer = "He is called 'Johnny'";
var x = 'It\'s alright';
var y = "He is called \"Johnny\"";
```

### 字符串长度

可以使用内置属性length来计算字符串的长度：

```
var txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
var sln = txt.length;
```

### 特殊字符

使用转义字符来表示特殊字符，例如单引号双引号。

### 字符串对象

```
通常， JavaScript 字符串是原始值，可以使用字符创建：
var firstName = "John"
但我们也可以使用 new 关键字将字符串定义为一个对象： 
var firstName = new String("John")
```

**注意**：不要创建string对象，会拖慢执行速度并产生其他副作用。

### 字符串属性

原始值字符串，如 "John", 没有属性和方法(因为他们不是对象)。 

原始值可以使用 JavaScript 的属性和方法，因为 JavaScript 在执行方法和属性时可以把原始值当作对象。

| 属性        | 描述                       |
| ----------- | -------------------------- |
| constructor | 返回创建字符串属性的函数   |
| length      | 返回字符串的长度           |
| prototype   | 允许您向对象添加属性和方法 |

### 字符串方法

| 方法                | 描述                                                         |
| ------------------- | ------------------------------------------------------------ |
| charAt()            | 返回指定索引位置的字符                                       |
| charCodeAt()        | 返回指定索引位置字符的 Unicode 值                            |
| concat()            | 连接两个或多个字符串，返回连接后的字符串                     |
| fromCharCode()      | 将 Unicode 转换为字符串                                      |
| indexOf()           | 返回字符串中检索指定字符第一次出现的位置                     |
| lastIndexOf()       | 返回字符串中检索指定字符最后一次出现的位置                   |
| localeCompare()     | 用本地特定的顺序来比较两个字符串                             |
| match()             | 找到一个或多个正则表达式的匹配                               |
| replace()           | 替换与正则表达式匹配的子串                                   |
| search()            | 检索与正则表达式相匹配的值                                   |
| slice()             | 提取字符串的片断，并在新的字符串中返回被提取的部分           |
| split()             | 把字符串分割为子字符串数组                                   |
| substr()            | 从起始索引号提取字符串中指定数目的字符                       |
| substring()         | 提取字符串中两个指定的索引号之间的字符                       |
| toLocaleLowerCase() | 根据主机的语言环境把字符串转换为小写，只有几种语言（如土耳其语）具有地方特有的大小写映射 |
| toLocaleUpperCase() | 根据主机的语言环境把字符串转换为大写，只有几种语言（如土耳其语）具有地方特有的大小写映射 |
| toLowerCase()       | 把字符串转换为小写                                           |
| toString()          | 返回字符串对象值                                             |
| toUpperCase()       | 把字符串转换为大写                                           |
| trim()              | 移除字符串首尾空白                                           |
| valueOf()           | 返回某个字符串对象的原始值                                   |