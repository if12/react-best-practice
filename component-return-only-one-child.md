## 组件的返回值必须是唯一一个元素

> A React component can't return multiple React elements, but a single JSX expression can have multiple children, 
so if you want a component to render multiple things you can wrap it in a div.

不然在编译的时候babel会报错 `Adjacent JSX elements must be wrapped in an enclosing tag`

### 参考

[JSX Children](https://facebook.github.io/react/docs/jsx-in-depth.html#jsx-children)