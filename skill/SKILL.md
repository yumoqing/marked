---
name: marked-repo
version: 1.0.0
description: Marked 仓库：371 个文件，主语言HTML 143，JavaScript 31，JSON 14
trigger_conditions:
  - 需要理解、修改或排障 marked 的代码
  - 在 marked 里定位入口、数据表、对外契约或构建方式
---

# marked 仓库技能

> 由仓库实际内容生成的骨架（README/目录/模型定义/契约/构建脚本逐项取证）。新增判断与坑位请直接在下面对应小节补充。

## 定位

**Marked**

<a href="https://marked.js.org"> <img width="60px" height="60px" src="https://marked.js.org/img/logo-black.svg" align="right" /> </a> Checkout the [demo page](https://marked.js.org/demo/) to see marked in action ⛹️ Our [documentation pages](https://marked.js.org) are also rendered using marked 💯 Als

- 远端：`https://github.com/yumoqing/marked.git`
- 默认分支：`master`（共 2944 个提交）
- 最近提交：2023-02-19 `81c54df` bugfix
- 规模：371 个文件；HTML 143，JavaScript 31，JSON 14

## 目录结构

- `test/` — 测试（301 个文件）
- `docs/` — 文档（24 个文件）
- `src/` — 源码（10 个文件）
- `.github/` — 9 个文件
- `lib/` — 库代码（3 个文件）
- `man/` — 2 个文件
- `.devcontainer/` — 1 个文件
- `api/` — 1 个文件
- `bin/` — 启动/控制脚本（1 个文件）
- 根文件：`.editorconfig`、`.eslintignore`、`.eslintrc.json`、`.gitattributes`、`.gitignore`、`.releaserc.json`、`LICENSE.md`、`Makefile`、`README.md`、`SECURITY.md`

## 构建与运行

- `package.json`：`marked` v4.2.12，main=`./lib/marked.cjs`，scripts=test/test:all/test:unit/test:specs/test:lint/test:redos
- `Makefile`

## README 要点与注意（摘自 `README.md`）

- 章节：Demo、Docs、Compatibility、Installation、Usage、License

## 建议阅读顺序

1. `README.md`
2. `docs/`

