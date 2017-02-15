## 自定义组件必须首字母大写

### 原因

> When an element type starts with a lowercase letter, it refers to a built-in component like <div> or <span> and 
results in a string 'div' or 'span' passed to React.createElement. Types that start with a capital letter like <Foo /> 
compile to React.createElement(Foo) and correspond to a component defined or imported in your JavaScript file

就是说会被babel当成一个HTML标签，所以变成一个**字符串**传给`React.createElement`, 而且最重要的是不会报错

### 参考

[User-Defined Components Must Be Capitalized](https://facebook.github.io/react/docs/jsx-in-depth.html#user-defined-components-must-be-capitalized)