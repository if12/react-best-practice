## 跨层次获取ref

[#4936](https://github.com/facebook/react/issues/4936#issuecomment-179917137)

```js
function ComponentWithInput({ inputRef }) {
  return <div><input ref={inputRef} /></div>
}

function Parent() {
  return <ComponentWithInput inputRef={input => input && input.scrollIntoView()} />
}
```