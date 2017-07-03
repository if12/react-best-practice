## 行内元素之间空格问题

下面你可能在用React会写的代码

```js
render() {
  return (
    <div>
      <span>Hello</span>
      <span>React</span>
    </div>
  )
}
```

突然你会发现出来的代码居然是HelloReact, 居然中间不会出现空格。但是如果用HTML还是可以出现折行的。感觉这个有点是JSX的锅。

解决方案是在中间加上`{' '}`
```js
render() {
  return (
    <div>
      <span>Hello</span>
      {' '}
      <span>React</span>
    </div>
  )
}
```

#### 参考

[React #1643](https://github.com/facebook/react/issues/1643)