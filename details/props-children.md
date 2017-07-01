## props.children使用场景

> Some components don't know their children ahead of time, such as Sidebar and Popup, we recommend that such components use 
the special children to pass children element directly into their output.

当你不知道你的组件的子组件是什么的时候, 可以通过this.props.children去获取到子组件。比如Popup, TabPane等组件都可以。