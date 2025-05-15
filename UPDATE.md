## 2025-05-15 09:08:20
1. 新增 ESLint 配置文件 `.eslintrc.js` 和忽略文件 `.eslintignore`，实现对 React+TS 项目的代码规范约束。
2. 新增 Prettier 配置文件 `.prettierrc` 和忽略文件 `.prettierignore`，统一代码风格。
3. 新增 Stylelint 配置文件 `stylelint.config.js` 和忽略文件 `.stylelintignore`，约束样式文件规范。
4. 新增 Commitlint 配置文件 `commitlint.config.js`，规范 Git 提交信息。
5. 新增 lint-staged 配置文件 `lint-staged.config.js`，集成 eslint、prettier、stylelint 自动修复。
6. 在 `package.json` 中新增 `prepare` 脚本，自动初始化 husky。
7. 安装并初始化 husky，添加 pre-commit 和 commit-msg 钩子，实现提交前代码检查和提交信息校验。

--- 