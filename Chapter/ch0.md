# 0. OOPs 简介

## 0.1 结构化编程(STRUCTURED PROGRAMMING)

结构化编程一般采用自顶向下的设计方法，开发人员将整个程序结构
映射到不同的子部分中。

*Corrado Bohm* 和 *Guiseppe Jacopini* 两位数学家已证明：
只使用三种结构就可以编写任何计算机程序：

+ 判断结构
+ 顺序结构
+ 循环结构

在结构化编程中，程序员会将一个很大部分代码划分为一个个便于理解
的子部分（可以是函数、子程序、方法和代码块等）。
同时，程序应该使用局部变量，通过值传递或者引用传递参数。

## 0.2 过程化编程(PROCEDURAL PROGRAMMING)

过程式编程是一种基于过程调用概念的编程范式。
过程也称为例程（rutinues）、子例程、方法或函数（仅包含一系列要执行的计算步骤）。
任何给定的过程都可以在过程执行期间的任何时候调用，包括由其他过程或其本身调用。
输入通常以参数的形式在语法上指定，输出作为返回值传递。

要被认为是过程式的，编程语言应该通过具有过程的明确概念和定义它的语法来支持
过程式编程。理想情况下，它应该支持参数类型、局部变量、递归过程调用的规范
以及在单独构建的过程结构中使用过程。它还可以支持输入和输出参数的区别。

面向过程编程的特点：
+ 遵循自上而下的方法；
+ 数据的重要性不如函数；
+ 由于函数共享全局数据，因此存在数据脆弱性。；
+ 函数操纵全局数据，而不让其他函数知道；
+ 大程序被分成小模块；
+ 首先设计算法，不关心细节；

## 0.3 编程方法

任何问题都有自上而下或自下而上两种处理方式。这里举一个简单的例子来说明这个概念，
对一个数组进行排序涉及以下步骤：
(a) 比较
(b) 交换。


在最高层，必须制定一种算法，利用上述操作进行排序。算法确定后，
再制定比较和交换算法，然后再执行整个算法。因此，在这种方法中，
一开始就从顶层开始，而不去考虑实施的微小细节。

自下而上的方法正好相反。首先执行较低层次的任务，然后进行整合以提供解决方案。
在这种方法中，较低层次的结构被执行。在这里，先制定交换和比较的算法，
然后再制定整个问题的算法。

在任何情况下，将问题划分为小任务，然后解决每个任务，都能提供解决方案。
因此，必须采用自上而下或自下而上的方法将问题划分为较小的模块，然后加以解决。
在自上而下的方法中，先确定整体结构，然后再确定细节；而在自下而上的方法中，
先确定细节，然后再确定整体结构。

### 0.3.1 自顶向下(Top-Down)

1. 在自上而下的模型中，系统的概述被制定出来，而不对其中的任何部分进行详细设计。然后，通过更详细的设计来完善系统的每个部分；
2. 每个新的部分都可以再次细化，对其进行更详细的定义，直到整个规范足够详细，可以对模型进行验证；
3. 自上而下的方法强调规划和对系统的补充理解。其固有的特点是，至少在系统的某些部分的设计达到足够详细的程度之前，不能开始编码；
4. 自顶向下编程是一种编程风格，是传统过程式语言的主流，在这种编程风格中，设计首先是将复杂的部分具体化，然后再将它们连续分成较小的部分；
5. 使用自顶向下方法编写程序的技巧是编写一个主程序，程序编码完成后，程序就完成了；
6. 自顶向下编程可能会使测试复杂化，因为直到项目接近尾声时才会有可执行的程序退出；
7. C 和 Pascal 就是使用这种方法编程的一个例子；

### 0.3.2 自底向上(Bottom-Up)

1. 在自下而上的设计中，系统的各个部分被详细规定。然后将这些部件连接起来，形成更大的组件，再将这些组件连接起来，直至形成一个完整的系统；
2. 自下而上的设计所产生的程序更小、更灵活。一个较短的程序不必分成许多组件，而较少的组件意味着程序更容易阅读或修改；
3. 自下而上的设计促进了代码的可重用性。当你编写两个或更多程序时，你为第一个程序编写的许多实用程序在后续程序中也会有用。因此，代码的可重用性是自底向上方法的主要优点之一；
4. 自底向上的设计使程序更容易阅读；
5. 自下而上的设计有助于理清程序设计的思路；
6. 自下而上的程序设计可以让你进行单元测试，但在大部分系统组合起来之前，系统无法作为一个整体进行测试，这往往会导致在项目接近尾声时进行编译；
7. C++ 和 java 就是使用这种方法编程的一个例子；

## 0.4 面向对象编程(OBJECT-ORIENTED PROGRAMMING)
