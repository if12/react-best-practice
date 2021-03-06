### React Better Pratice

[中文](./README-zh.md)

### Purpose

Take the problem I suffer in the real world down. And strongly hope who look into this
repo to give me some advices.

### Tips

* [User-defined Component Must Be capitalized](./details/user-defined-component-must-be-capitalized.md)
* [Component Return Only One Child](./details/component-return-only-one-child.md)
* [Don't **Modify** Props](./details/props-are-read-only.md)
* Don't Modify State Directly
* Don't using indexes for **Keys** if the items can reorder
* If something can be derived from eithor props or state, it probably shouldn't be in the state.
* [props.children Use Case](./details/props-children.md)
* [To Export More React Component](./details/export-more-components.md)
* [Using PureComponent](./details/pure-component.md)
* [Can I load data in the constructor](https://github.com/facebook/react/issues/9021)
* [DOM is not rendered before componentDidUpdate](https://github.com/facebook/react/issues/9033)
* bind function in Component constructor
* [React computed property](./details/computed.md)
* [White space between inline element](./details/white-space-between-inline-element.md)
* [Controlled input setState to null](./details/controlled-input-to-null.md)
* [Don't return prop.children conditional in the render function](./details/return-children-conditional.md)
* [JSX props shorthand](./details/jsx-props-shorthand.md)
* [Don't mix up Controlled and Uncontrolled](./details/dont-mix-up-controlled-and-uncontrolled.md)
* [How to Get cross-level ref](./details/cross-level-ref.md)
* [Input fires unnecessary using Chinese IME](./details/using-chinese-ime.md)

### Fiber

Let's see what happened into [Fiber](./details/fiber.md).

### Inspired

* [Show a better warning when accidentally returning from constructor](https://github.com/facebook/react/issues/11381)
* [Check .length before accessing characters](https://github.com/facebook/react/issues/11460)
* [Fix DEV performance regression by avoiding Object.assign on Fibers](https://github.com/facebook/react/pull/12510)

### Reference

* [React.js Best Practices for 2016](https://blog.risingstack.com/react-js-best-practices-for-2016/)
* [React Official Doc](https://facebook.github.io/react/)
* [Best Practices for Component State in React.js](http://brewhouse.io/blog/2015/03/24/best-practices-for-component-state-in-reactjs.html)
* [Ryan Florence's Compound Components](https://www.youtube.com/watch?v=hEGg-3pIHlE)
* [React Pattern](http://reactpatterns.com/)
* [React 技巧和最佳实践](http://www.jianshu.com/p/90a72128ec76)
* [Andrew Clark's tweet](https://twitter.com/acdlite/status/974437383939743746)
