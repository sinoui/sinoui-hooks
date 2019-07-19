# sinoui-hooks

这是由[ts-lib-scripts](https://github.com/sinoui/ts-lib-scripts)创建的 TypeScript 库项目。

用于收集通用性 hooks,与任何 UI 库无关

## 本地开发

### 开发规范说明

1. 使用命令行新建项目模块
2. 所有 hooks 及 hooks 中的方法都必须有注释和必需的类型声明
3. 所有 hooks 都要按照[接口 API 文档规范](https://sinoui.github.io/sinoui-guide/docs/doc-of-api-standard)编写文档
4. hooks 相关文档编写时，如果涉及使用场景，需要可运行的示例

项目中有以下有用的命令。

### `yarn build`

打包，并将打包文件放在`dist`文件夹中。使用 rollup 对代码做优化并打包成多种格式（`Common JS`，`UMD`和`ES Module`）。

### `yarn lint`

`yarn lint`会检查整个项目是否有代码错误、风格错误。

开启 vscode 的 eslint、prettier 插件，在使用 vscode 编码时，就会自动修正风格错误、提示语法错误。

### `yarn format`

`yarn format`可以自动调整整个项目的代码风格问题。

### `yarn test`

`yarn test`以监听模式启动 jest，运行单元测试。

开启 vscode 的 jest 插件，会在文件变化时自动运行单元测试。

### 添加模块

```shell
yarn gen my-ts-module
```

## 启动 docz

```shell
yarn doc:start
```
