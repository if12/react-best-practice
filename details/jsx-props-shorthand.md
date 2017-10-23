## jsx props属性缩写

```js
class Table extends Component {
    render() {
        const { dataSource, columns } = this.props;
        return (
            <Spin tip="加载中...">
            <div>
                <h1>Table</h1>
                <Table dataSource={dataSource} columns={columns} />
            </div>
            </Spin>
        );
    }
}
```

可以写成

```js
class Table extends Component {
    render() {
        const { dataSource, columns } = this.props;
        return (
            <Spin tip="加载中...">
            <div>
                <h1>Table</h1>
                <Table {...{dataSource, columns}} />
            </div>
            </Spin>
        );
    }
}
```

参考 [#9115](https://github.com/facebook/react/pull/9115/files#diff-f980151ad39d027fddfc016e4683d40b)
