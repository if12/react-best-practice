### 背景
毕竟现在的React这么火，写有关React的文章或者代码应该还是挺受欢迎的。这样子就有很多人star，想想还是美好的。
不过确实**没有最好的实践，只有更好的实践，没有最好的框架，只有适合的框架**。程序员还是不能很容易就被忽悠了。

### 目的
希望能把我在项目实践中遇见到的问题，记录下来。也希望看到这个repo的人可以提供一些建议。

### React文档
1. [组件名首字符必须是大写](./user-defined-component-must-be-capitalized.md)
2. [组件的返回值必须是唯一一个元素](./component-return-only-one-child.md)
3. [不要修改prop](./props-are-read-only.md)
4. 不要直接修改State
5. Don't using indexes for `Keys` if the items can reorder
6. If something can be derived from eithor props or state, it probably shouldn't be in the state.
7. Some components don't know their children ahead of time, such as Sidebar and Popup, we recommend that such components use 
the special children to pass children element directly into their output.
8. Using Dot Notation for JSX Type: it's convenient if you have a single module that exports many React components
9. PureComponent, 在你只需要它更新的时候才更新，不过注意的是它是用了浅比较.
10. [Can I load data in the constructor](https://github.com/facebook/react/issues/9021)

### 资料
* [React.js Best Practices for 2016](https://blog.risingstack.com/react-js-best-practices-for-2016/)
* [React Official Doc](https://facebook.github.io/react/)
* [Best Practices for Component State in React.js](http://brewhouse.io/blog/2015/03/24/best-practices-for-component-state-in-reactjs.html)
* [React Pattern](http://reactpatterns.com/)
* [React 技巧和最佳实践](http://www.jianshu.com/p/90a72128ec76)
