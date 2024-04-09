# 2. C++

## 2.1. C++ 概述

C++ 是一种面向对象的编程语言，是由 Bjarne Stroustrup 在 20 世纪 80 年代初在美国新泽西州 Murray Hill 的 AT&T 贝尔实验室开发的。它是在 C 语言的基础上进行了扩展，添加了许多新特性。C++ 的命名来自于 C 语言中的递增运算符 ++，因为它被认为是 C 的一个超集，比 C 领先一个版本，所以被命名为 C++。

编程语言中首次使用类构造的例子出现在 1967 年的 Simula 语言中，它是从 Algol 演变而来的。C++ 的发明者 Bjarne Stroustrup 在他的博士研究中使用了 Simula 语言编写模拟计算机系统的仿真程序。他发现 Simula 语言非常具有表现力，使他能够以高度抽象的方式工作，但当他运行程序以获得他论文所需的数值结果时，他发现性能太慢了，他永远无法按时完成工作。因此，他将自己的程序改用 C 重新编写。但他做了一件非常聪明的事情。他编写了一个转换程序，该程序会接受一个类似于 C 的程序，并在其基础上添加类的扩展，然后将其转换为纯 C 代码。结果是一种最初被称为“**C with classes**”的语言，后来成为 C++。这个转换程序成为 AT&T 的“`cfront`”编译器，它可以将 C++ 代码转换为 C 代码。“`cfront`”是用 C++ 编写的第一个应用程序。

## 2.2. C++ 字符集

一个 C++ 程序是按照一定的顺序编写的一系列指令集合。这些指令包括**关键字**、**变量**、**函数**、**对象**等，使用 C++ 定义的字符集合。它是由各种字符、数字和符号组成的集合，可以在 C++ 程序中使用。它包括以下内容：

<div style="text-align: center;">
    表 2.1
</div>
<style>
    table{
        margin: auto;
    }
</style>
<table>
<thead>
  <tr>
    <th>NO.</th>
    <th>C++ 字符集元素</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1.</td>
    <td>大写字符: A - Z</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>小写字符: a - z</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>0 - 9</td>
  </tr>
  <tr>
    <td>4.</td>
    <td>符号</td>
  </tr>
</tbody>
</table>

<div style="text-align: center;">
    表 2.2
</div>
<table><thead><tr><th>符号</th><th>名称</th><th>符号</th><th>名称</th></tr></thead><tbody><tr><td>~</td><td>波浪</td><td>&gt;</td><td>大于</td></tr><tr><td>&lt;</td><td>小于</td><td>&amp;</td><td>与</td></tr><tr><td>|</td><td>或</td><td>#</td><td>哈希</td></tr><tr><td>&gt;=</td><td>大于等于</td><td>&lt;=</td><td>小于等于</td></tr><tr><td>==</td><td>等于</td><td>=</td><td>赋值</td></tr><tr><td>!=</td><td>不等于</td><td>^</td><td></td></tr><tr><td>{</td><td>左大括号</td><td>}</td><td>右大括号</td></tr><tr><td>(</td><td>左括号</td><td>)</td><td>右括号</td></tr><tr><td>[</td><td>左方括号</td><td>]</td><td>右方括号</td></tr><tr><td>/</td><td>正斜杠</td><td>\</td><td>反斜杠</td></tr><tr><td>:</td><td>冒号</td><td>;</td><td>分号</td></tr><tr><td>+</td><td>加号</td><td>-</td><td>减号</td></tr><tr><td>*</td><td>乘</td><td>/</td><td>除</td></tr><tr><td>%</td><td>模运算</td><td>,</td><td>逗号</td></tr><tr><td>'</td><td>单引号</td><td>"</td><td>双引号</td></tr><tr><td>&gt;&gt;</td><td>右移</td><td>&lt;&lt;</td><td>左移</td></tr><tr><td>.</td><td>句号</td><td>_</td><td>下划线</td></tr></tbody></table>

## 2.3. C++ 标记

C++ 程序中最小的单元称为 C++ 标记。C++ 定义了六种类型的标记：
1. 关键字；
2. 标识符；
3. 常量；
4. 字符串；
5. 操作符；
6. 特殊字符；

### 2.3.1. 关键字

**关键字是编译器已知含义的单词**。换句话说，每个关键字的含义是固定的。您可以直接使用关键字来表示其预期的含义。您不能更改关键字的含义。您也不能将关键字用作变量、函数、数组等的名称。所有关键字都用小写字母写成。

C++ 中有 63 个关键字。以下图表列出了 C++ 中的所有关键字：

<div style="text-align: center;">
    表 2.3
</div>
<table><tbody><tr><td>asm</td><td>auto</td><td>bool</td><td>break</td><td>cae</td><td>catch</td></tr><tr><td>char</td><td>class</td><td>const</td><td>const_cast</td><td>continue</td><td>default</td></tr><tr><td>delete</td><td>do</td><td>double</td><td>dynamic_cast</td><td>else</td><td>enum</td></tr><tr><td>explicit</td><td>export</td><td>extern</td><td>false</td><td>float</td><td>for</td></tr><tr><td>friend</td><td>goto</td><td>if</td><td>inline</td><td>int</td><td>long</td></tr><tr><td>mutable</td><td>namespace</td><td>new</td><td>operator</td><td>private</td><td>protected</td></tr><tr><td>public</td><td>register</td><td>reinterpret_cast</td><td>return</td><td>short</td><td>signed</td></tr><tr><td>sizeof</td><td>static</td><td>static_cast</td><td>struct</td><td>switch</td><td>template</td></tr><tr><td>this</td><td>throw</td><td>true</td><td>try</td><td>typedef</td><td>typeid</td></tr><tr><td>typename</td><td>union</td><td>unsigned</td><td>using</td><td>virtual</td><td>viod</td></tr><tr><td>volatile</td><td>wchar_t</td><td>while</td><td></td><td></td><td></td></tr></tbody></table>

### 2.3.2. 标识符

标识符是赋予给各种程序元素的名称，如**变量**、**数组**、**函数**、**结构**等。编写标识符的规则：
+ 规则1：首字母必须是字母或下划线；
+ 规则2：从第二个字符开始，允许任意组合的数字、字母或下划线；
+ 规则3：只允许使用数字、字母和下划线。不允许使用其他符号；
+ 规则4：关键字不能用作标识符；
+ 规则5：对于 ANSI（美国国家标准协会）C++，标识符的最大长度为 32，但许多编译器支持超过 32；

合法标识符：`order_no`, `name`, `_err`, `_123`, `xyz`, `radius`, `a23`, `int_rate`。

非法标识符：`order-no`, `12name`, `int`, `x$`, `s name`, `hari+45`, `123`。

### 2.3.3. 常量

C++ 中的常量是指在程序执行过程中不会改变的固定值。C++ 中有各种类型的常量，它们被分类如下：
+ 数字常量：
  + 整型常量；
  + 实数；
+ 非数字常量：
  + 字符常量；
  + 字符串常量；

#### 2.3.3.1. 整型常量

三类：
+ 十进制常量：它们是从 0 到 9 的数字序列，没有小数部分。它可以是负数、正数或零。例如：12, 455, -546, 0。
+ 八进制常量：它们是从 0 到 7 的数字序列，第一个数字必须是 `0`。例如：034、0、0564、0123 等。
+ 十六进制常量：它们是由从 0 到 9 和 A 到 F（表示 10 到 15）的数字序列组成的。它们以 `0x` 或 `0X` 开头。例如：0x34、0xab3、0X3E 等。

#### 2.3.3.2. 实数

它们是具有小数部分的数字。它们也被称为浮点常量。例如：34.56、0.67、1.23 等。

实数常数也可以用指数或科学计数法表示，它由两部分组成。例如，数字 212.345 可以表示为 2.12345e+2，其中 e+2 表示 10 的 2 次方。这里的 e 之前的部分，即 2.12345，称为尾数，+2 是指数。指数始终是一个整数，可以写成小写或大写。

以上给出的数字可能有许多其他表示方法。我只是举了一个科学计数法中数字的例子。

