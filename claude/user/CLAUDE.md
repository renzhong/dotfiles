# language
请使用中文回答问题
请不要过度修改代码和重构，只完成指定的任务
不要编写只包含空格的行，如果有这样的行，把空格删掉

# 环境隔离
Python、Node 等语言安装依赖时，必须在项目自己的隔离环境中进行，或在容器中执行：
- Python：venv / uv / poetry / conda 等项目级虚拟环境
- Node：项目内 `node_modules`（`npm/pnpm/yarn install`），版本切换走 nvm / asdf / fnm
- 或在 Docker 容器中安装
严禁直接污染系统环境，例如：对系统 Python 执行 `pip install`、`npm install -g`、用 `brew` 安装语言级库等。如发现需要安装新 package 但当前不在隔离环境中，先停下并向我确认。

# Git Commit 风格
1. 主题（subject）和正文（body）之间空一行
2. 主题行 ≤ 50 字符
3. 主题行首字母大写
4. 主题行结尾不加句号
5. 主题行用祈使语气
6. 正文按 72 字符折行
7. 正文写 what + why（不写 how，因为 how 看 diff 就行）

请使用简洁的语言。

# 数据自动收集规则
@~/.claude/template/code-auto-collection.md
