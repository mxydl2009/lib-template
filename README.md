## JavaScript 库模板

- 创建 JavaScript 库的模板;
- 集成 Rollup 打包构建, 构建产物包含 ES Module 规范和 CommonJS 规范的代码;
- 集成 babel 转译（打包构建、nyc 收集测试覆盖率）;
- 集成 mocha 测试，nyc 收集测试覆盖率;
- 集成 jsdoc 相关工具，生成文档（HTML 和 Markdown 格式, markdown 文本写入 READMD.md 文件）;
- 添加 npm version hook 命令和脚本，在更改 version 前提示检查，更改 version 后自动 git 提交、推送，自动 npm publish;
