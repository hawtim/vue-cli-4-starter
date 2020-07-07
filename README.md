# vue-cli@4 脚手架 优化版

## 工程特性

1. `.editorconfig `增加编辑器配置
2. `.npmrc` npm 设置 `npm` 和 `node-sass` 代理
3. `.prettierrc` 优化 `prettier` 选项
4. `babel.config.js` 实现 `element-ui` 按需加载
5. `jsconfig.json` 增加 `vscode` 文件跳转
6. `jest.config.js` 增加 `identity-obj-proxy` 用于含有 `elementui` 的组件测试
7. `.eslintrc.js` 增加全局变量配置
8. `vue.config.js` 增加 `definePlugin` 和 `webpackBundleAnalyzer` 的配置，自定义 `loader`（只是举例）

## 业务特性

1. `dayjs` 用于日期处理
2. `normalize.css` 用于 `css reset`
3. `elementui` 作为前端组件库
4. `vchart` 封装的 `echart` 作为数据可视化

以上任何问题，欢迎 issues

## 项目初始化
```
npm install
```

### 开发时的编译和热更新
```
npm run serve
```

### 生产环境的编译和代码压缩
```
npm run build
```

### 运行你的单元测试
```
npm run test:unit
```

### 运行你的端对端测试
```
npm run test:e2e
```

### 校验和修复文件
```
npm run lint
```

### webpack 依赖的分析
```
npm run analyzer
```
