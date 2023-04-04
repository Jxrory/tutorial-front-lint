# 前端规范构建教程

学习如何构建前端规范

## 推荐 IDEA

- [VSCode](https://code.visualstudio.com/)
- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur)
- [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## 构建过程

#### 配置编辑器 [editorconfig](https://editorconfig.org/)

[editorconfig 配置文档](https://github.com/Jxrory/tutorial-front-lint/blob/main/docs/0-vue%E5%89%8D%E7%AB%AF%E5%BC%80%E5%8F%91%E8%A7%84%E8%8C%83-vscode.md)

对应的 commit: [a04c3c091ab95cabeb02d3189c5354542eb06db9](https://github.com/Jxrory/tutorial-front-lint/commit/a04c3c091ab95cabeb02d3189c5354542eb06db9)

#### 代码格式化工具 `prettier`

[prettier 配置文档](https://github.com/Jxrory/tutorial-front-lint/blob/main/docs/1-prettier%E9%85%8D%E7%BD%AE.md)

对应的 commit: [b2b147f48a3f1db8deb3cddbfb8d63665672963d](https://github.com/Jxrory/tutorial-front-lint/commit/b2b147f48a3f1db8deb3cddbfb8d63665672963d)

#### 代码规范检查 `eslint`

[eslint 配置文档](https://github.com/Jxrory/tutorial-front-lint/blob/main/docs/2-eslint%E9%85%8D%E7%BD%AE.md)

对应的 commit: [baf4a15721ea9512fdba1c958155751c27c5baf8](https://github.com/Jxrory/tutorial-front-lint/commit/baf4a15721ea9512fdba1c958155751c27c5baf8)

#### 样式规范检查 `stylelint`

[stylelint 配置文档](https://github.com/Jxrory/tutorial-front-lint/blob/main/docs/3-stylelint%E9%85%8D%E7%BD%AE.md)

对应的 commit: [3cc5b9aca02aec712e0afe42685c90529213e5da](https://github.com/Jxrory/tutorial-front-lint/commit/3cc5b9aca02aec712e0afe42685c90529213e5da)

#### git 提交代码规整 `lint-staged` & `husky`

[husky & lint-staged 配置文档](https://github.com/Jxrory/tutorial-front-lint/blob/main/docs/4-husky%E9%85%8D%E7%BD%AE.md)

对应的 commit: [db0385ac95fc1fa4fcb791e4b9ef292690aaccb0](https://github.com/Jxrory/tutorial-front-lint/commit/db0385ac95fc1fa4fcb791e4b9ef292690aaccb0)

#### commit 提交信息规范 `cz-git` & `commitlint`

[cz-git & commitlint 配置文档](https://github.com/Jxrory/tutorial-front-lint/blob/main/docs/6-commitlint%E9%85%8D%E7%BD%AE.md)

对应 commit: [24a6b1e53070b60d7ebc1127b7823f177de3c445](https://github.com/Jxrory/tutorial-front-lint/commit/24a6b1e53070b60d7ebc1127b7823f177de3c445)

## 项目安装与运行

```sh
npm install
```

### 热部署运行

```sh
npm run dev
```
