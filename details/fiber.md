## Fiber

> ### [New Core Algorithm](https://github.com/facebook/react/issues/6170)

这个是Fiber真正成立的一个类似RFC内容

> ### [New Reconciler Infra](https://github.com/facebook/react/pull/6690)

第一个有关Fiber的Pull Request

> ### [Fiber Principles](https://github.com/facebook/react/issues/7942)

概览了解下它的原理

> ### [Fiber数据结构](https://github.com/facebook/react/blob/v16.6.0/packages/react-reconciler/src/ReactFiber.js#L85-L207)

Fiber的核心，了解每一个属性代表的意思

> ### [How React Fiber Works](https://www.facebook.com/groups/2003630259862046/permalink/2054053404819731/)

不用`Stack`递归, 通过`while`模拟, 才是可以中断renderer流程的

> ### [Lin Clark - A Cartoon Intro to Fiber](https://www.youtube.com/watch?v=ZCuYPiUIONs)

这个要看多次, 不然听不太懂

> ### [Andrew Clark: What's Next for React](https://www.youtube.com/watch?v=aV1271hd9ew&feature=youtu.be)

有一个`Stack frame`跟`Fiber`的对比

|Stack frame| Fiber|
|:--:|:--:|
|subroutine(function)|component type|
|body|children|
|return address|parent|
|arguments|props|
|return value|DOM elements|

> ### [React Fiber Architecture](https://github.com/acdlite/react-fiber-architecture)

`Virtual Stack Frame`

> ### [React Fiber Resources](https://github.com/koba04/react-fiber-resources)

别人总结的React Fiber资料

> ### [All Commits about Fiber](https://github.com/facebook/react/pulls?utf8=%E2%9C%93&q=is%3Amerged%20is%3Apr%20fiber%20)

所有有关Fiber的Pull Request

> ### [React Fiber初探](http://blog.codingplayboy.com/2017/12/02/react_fiber/)

比较完整地了解下React Fiber

> ### [Didact Fiber: Incremental reconciliation](https://engineering.hexacta.com/didact-fiber-incremental-reconciliation-b2fe028dcaec)

从零开始学习Fiber，还有对应的[github代码](https://github.com/hexacta/didact)