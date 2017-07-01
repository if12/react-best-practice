### React的更好实践

[英文](./README.md)

### 目的

希望能把我在项目实践中遇见到的问题给记录下来。也希望看到这个repo的人可以提供一些建议。

### 温馨提示

1. [组件名首字符必须是大写](./details/user-defined-component-must-be-capitalized.md)
2. [组件的返回值必须是唯一一个元素](./details/component-return-only-one-child.md)
3. [不要修改prop](./details/props-are-read-only.md)
4. 不要直接修改State
5. 如果元素会重新排序就不要用数组下标做key
6. 如果某些值可以通过props或者state计算出来的, 那么它不太需要放在state
7. [props.children使用场景](./details/props-children.md)
8. [暴露更多的React组件](./details/export-more-components.md)
9. [使用PureComponent](./details/pure-component.md)
10. [我可以在构造方法加载数据吗?](https://github.com/facebook/react/issues/9021)
11. [DOM元素在componentDidUpdate之前是不渲染的](https://github.com/facebook/react/issues/9033)
12. bind方法尽量都放在Component constructor

### 资料
* [React.js Best Practices for 2016](https://blog.risingstack.com/react-js-best-practices-for-2016/)
* [React Official Doc](https://facebook.github.io/react/)
* [Best Practices for Component State in React.js](http://brewhouse.io/blog/2015/03/24/best-practices-for-component-state-in-reactjs.html)
* [React Pattern](http://reactpatterns.com/)
* [React 技巧和最佳实践](http://www.jianshu.com/p/90a72128ec76)
