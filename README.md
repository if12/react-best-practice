### 背景
毕竟现在的React这么火，写有关React的文章或者代码应该还是挺受欢迎的。
这样子就有很多人star，想想还是美好的。不过确实没有最好的实践，只有
更好的实践，没有最好的框架，只有适合的框架。程序员还是不能很容易就被
忽悠了。

### 目的
希望能把我在项目实践中遇见到的问题，记录下来。
也希望看到这个repo的人可以提供一些建议。

### React文档
1. 组件名首字符必须是大写
2. 组件必须返回的是唯一一个元素
3. 不要修改prop [React props are read only](https://facebook.github.io/react/docs/components-and-props.html#props-are-read-only)
4. 不要直接修改State
5. Don't using indexes for `Keys` if the items can reorder
6. If something can be derived from eithor props or state, it probably shouldn't be in the state.

### 资料

* [React.js Best Practices for 2016](https://blog.risingstack.com/react-js-best-practices-for-2016/)
