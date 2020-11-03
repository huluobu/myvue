# vue笔记

## vue 
    用 Vuejs 来做前端框架，对于处理数据的方面可以完全的
    替换掉原有的 dom 操作的理念（之前我们常用的原生 js 以及 jquery
    类库），通过 Vuejs 框架提供的指令，前端开发人员不再关心 dom 是

## 冒泡机制
    使用.stop 来对事件的冒泡机制进行阻止
    js 中的事件的冒泡指的是，在触发了内层元素的同时，也会随之
    继续触发外层元素（外层元素包裹了内层元素），在做点击的过程中，
    点击了内层元素，也可以认为是同时点击了外层元素。所以两个事件
    都会触发。

## v-mode数据绑定
对 v-bind 的绑定数据的形式得出一个结论，v-bind 只能
实现数据的单向绑定，从模型（M）绑定到视图（V），使用 VM 将数
据去渲染视图，但是我们无法通过该形式实现数据的双向绑定。
双向数据绑定