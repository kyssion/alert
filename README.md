# @sinoui/alert

[![npm version](https://img.shields.io/npm/v/@sinoui/alert)](https://www.npmjs.com/package/@sinoui/alert)
[![downloads](https://img.shields.io/npm/dm/@sinoui/alert)](https://www.npmjs.com/package/@sinoui/alert)

警告提示，展现需要关注的信息。[官方文档](https://sinoui.github.io/alert/)

## 安装

```shell
yarn add @sinoui/alert
```

## 简单示例

```tsx
import React from 'react';
import Alert from '@sinoui/alert';

function Demo() {
  return <Alert message="提示信息" />;
}
```

更多示例请参考[官方文档](https://sinoui.github.io/alert/)。

## 本地开发

项目中有以下有用的命令。

### `yarn start`

在开发和监听模式下启动项目。当代码发生变化时就会重新编译代码。它同时会实时地向你汇报项目中的代码错误。

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

### 预览文档

```shell
yarn doc:dev
```

### 编译并打包文档

```shell
yarn doc:publish
```

### 发布文档

在发布文档之前，在`package.json`中配置好`homepage`，如下所示：

```json
{
  "homepage": "https://sinouiincubator.github.io/editable-data-table"
}
```

配置完之后就可以执行下面的命令行发布文档：

```shell
yarn doc:publish
```
