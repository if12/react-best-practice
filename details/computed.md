## React计算属性

很明显, React是不支持计算属性, 像Vue/Ember等其他框架就存在。
对于Vue, 你可以这样子定义

```js
computed: {
  fullname: {
    return this.firstname + this.lastname;
  }
}
```

最重要的是当你的firstname修改了, 你对应的fullname也会跟着修改。

所以这个确实是有很大的使用场景的, 对于React来讲, 有时候在写组件的时候, 为了便于使用者, 暴露的API尽可能少点, 可以基于props来计算的属性就用props。这个时候就存在一个问题如果你只在constructor才对props来计算出另外一个属性的话, 很容易出现数据不统一。因为如果外层的组件触发了setState了, 可能需要对你这个组件的props进行修改了, 那么你在constructor通过props计算得出的属性就没用了, 那么你就得在**componentWillReceiveProps**的时候再来一次计算。在维护方面很重要的地方就是统一管理, 分散的话你要做**至少两次**同样的操作。

所以咱们可以想想React组件一定会经过的流程是什么呢? 对的, **render**处理函数都会执行的, 不管它是初始化还是更新操作。我们可以把计算属性函数放在render里面, 但是这个时候就需要加上缓存了, 因为有时候没必要重新计算的。咱们可以用到[reselect](https://github.com/reactjs/reselect)库或者自己写一个缓存代理。


#### 参考

* [React #240](https://github.com/facebook/react/issues/240)