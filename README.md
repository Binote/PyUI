# py-ui

## 开发前必读

强烈推荐使用 VSCODE 编译器 并且安装 `Prettier - Code formatter`,`ESLint` 这两个插件

### ✨ 关于代码风格

本项目集成`prettier`做代码风格统一格式化,所以在书写时,大家可以不关注代码风格,按自己喜欢的写就好,在执行`commit`时会自动对代码做统一格式化.

### ✨ 关于 commit 中 emoji 的使用

为了优化`commit log`显示,本项目提交代码时,请使用如下命令替代`git commit`,并且选择合适的 `emoji` 进行提交说明,不符合格式的,`pr`将被驳回.

```
npm run ci
```

## 🚧 开发步骤 🚧

### 安装依赖

```shell
yarn install || cnpm install || npm install
```

### run 组件服务

```shell
npm run serve
```

### run 官网服务

```shell
npm run serve:main
```

### 编译组件库

```shell
npm run build
```

### run 测试服务

```shell
npm run test:unit
```
