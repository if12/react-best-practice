## Fiber

写这个是为了追踪Fiber的相关内容

### [New Core Algorithm](https://github.com/facebook/react/issues/6170)

这个Fiber真正成立的一个类似RFC内容

### [New Reconciler Infra](https://github.com/facebook/react/pull/6690)

第一个有关Fiber的相关PR

### [Fiber Principles](https://github.com/facebook/react/issues/7942)

简单了解了下它的原理

### [Fiber数据结构](https://github.com/facebook/react/blob/v16.1.0/packages/react-reconciler/src/ReactFiber.js#L56-L147)

### [How React Fiber Works](https://www.facebook.com/groups/2003630259862046/permalink/2054053404819731/)

不用stack递归, 通过while模拟

### [Lin Clark - A Cartoon Intro to Fiber](https://www.youtube.com/watch?v=ZCuYPiUIONs)

这个要看多次, 不然听不太懂

### [Andrew Clark: What's Next for React](https://www.youtube.com/watch?v=aV1271hd9ew&feature=youtu.be)

有一个`Stack frame`跟`Fiber`的对比

|Stack frame| Fiber|
|:--:|:--:|
|subroutine(function)|component type|
|body|children|
|return address|parent|
|arguments|props|
|return value|DOM elements|

### [React Fiber Architecture](https://github.com/acdlite/react-fiber-architecture)

virtual stack frame

### [React Fiber Resources](https://github.com/koba04/react-fiber-resources)

别人总结的React Fiber资料