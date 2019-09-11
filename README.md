# React Electron 应用模版

## 简介

本项目实现了使用 React 来构建 Electron 应用的功能，语言为 TypeScript。

## 可用脚本

- `yarn start` React 开发模式，行为同 create-react-app
- `yarn start-app` 利用 React 开发模式启动 electron 应用，**必须先开始运行 `yarn start`**
- `yarn build-app` 构建软件安装包，构建完成的安装包位于 dist 文件夹下

## 自定义

- electron 的主运行脚本位于 public/electron.js
- 主页模版为 public/index.html
- 应用图标为 public/icon.png
- 根据需要，修改 package.json
  - `name`
  - `version`
  - `author`
  - `description`
  - `build` electron-builder 相关选项，可参考文档修改

另外需要注意，新添加的 npm 包必须位于 `devDependencies` 中。