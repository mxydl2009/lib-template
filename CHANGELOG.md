# 变更日志

## 2.1.0 / 2024.07.10

- npm 上传采用黑名单.npmignore 的配置方式;
- 删除 LICENSE 文件，由脚手架来统一生成;

## 2.2.0 / 2024.07.10

- 在 package.json 添加 repository 配置;

# 2.2.1 / 2024.07.13

- 添加 npm version hook 命令和脚本，在更改 version 前提示检查，更改 version 后自动 git 提交、推送，自动 npm publish;
