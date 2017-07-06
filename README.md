# React学习笔记

这里是我学习React并做笔记的地方。

* 不友好：内容是为了我自己理解而做的，对读者不友好；
* 不规范：内容是为了我自己理解而写的，写法不规范；
* 不易学习：综上所述，并不适合初学者学习（坏笑）。

## 基于React的文档

学习笔记是基于React的[官方文档](https://facebook.github.io/react/docs/hello-world.html)，并且是挑选着摘录内容，不过下面会对内容做一些说明。

## 一些说明：

* 开始时间：2017/06/30
* 官方文档：v15.6.1

## demo01：JSX语法介绍

这个demo包含了[Introducing JSX](https://facebook.github.io/react/docs/introducing-jsx.html)和[Rendering Elements](https://facebook.github.io/react/docs/rendering-elements.html)两节。

介绍了JSX的语法糖，以及要注意的点：

* JSX可以加入一些Attributes
* JSX可以使用JS的表达式
* JSX使用JS表达式，要用{}

其外，还有React简单运行的例子。

## demo02：组件与属性

相关[Components and Props](https://facebook.github.io/react/docs/components-and-props.html)

介绍组件的使用：

* 组件可以复用
* 组件可以嵌套
* 组件名称必须大写

属性要注意的是

* 只读

推荐使用Class(ES6)

* constructor 当中可以继承props、定义state（demo03会提到）

## demo03：State和生命周期

相关[State and Lifecycle](https://facebook.github.io/react/docs/state-and-lifecycle.html)

