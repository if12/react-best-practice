## 不要在render函数条件判断时都返回this.props.children

### 原因

这样子会导致的情况就是children会重新创建, 会导致一些focus事件没用。
比如[Misleading reconciliation behavior due to this.props.children](https://jsfiddle.net/monkindey/hhmneth8/1/)例子, 当你输入内容的时候, 输入框
失去焦点了。


### 原理

在对React children的reconciler阶段处理存在不同。
本来是: 
```js
props: {
  children: [[<input />, <p>], <div>]
}
```

然后变成了
```js
props: {
  children: [<input />, <p>]
}
```



### 参考

* [React #8810](https://github.com/facebook/react/issues/8810)
* [React #8731](https://github.com/facebook/react/issues/8731)