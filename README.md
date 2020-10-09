# topology-demo

如何使用 es6+webpack 方式编译使用的 demo

**该案例是基于topology的es6demo改成适配最新插件版本的demo**

目前对应插件版本
```
"@topology/activity-diagram": "^0.3.0",
"@topology/class-diagram": "^0.3.0",
"@topology/core": "^0.3.1",
"@topology/flow-diagram": "^0.3.0",
"@topology/sequence-diagram": "^0.3.0",
```


# Development

## 1. 安装依赖库

```
[demo#] yarn
# 或
[demo#] npm install

```

## 2. 编写 es6

需要使用 topology 的业务逻辑在 index.js 中，通过下面命令编译成 es5 的文件，使 index.html 直接使用。

```
# build
[demo#] npm run build

```

## 3.在 index.html 中使用

参考 index.html

# License

MIT © le5le.com
