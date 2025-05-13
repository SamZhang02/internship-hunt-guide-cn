# 贡献指南

感谢您对本项目的贡献兴趣！本指南概述了如何为我们使用 MkDocs 构建并通过 GitHub Pages 部署的静态网站做出贡献。

## 开始之前

1. Fork 本仓库
2. 按照 `mkdocs.yaml` 中的规定安装依赖项，eg.可以参考: `pip install markdown pymdown-extensions mkdocs mkdocs-material`
3. 创建新分支：`git checkout -b feature/您的功能名称` 或 `fix/问题描述`

## 贡献类型

### 小改动（拼写错误、小编辑）

对于拼写错误、语法纠正或小内容更新等小问题：

- 可以直接提交 Pull Request
- 无需先创建 issue
- 请在 PR 中清楚描述所做的更改

### 大改动（新内容、结构重组）

对于重大更改，例如：

- 添加新章节/部分
- 重组内容结构
- 大规模重写

请：

1. 先创建 GitHub issue 讨论提议的更改
2. 等待维护者的反馈
3. 商定方案后再创建 PR

## 如何贡献

1. 在功能分支上进行更改
2. 通过运行 `mkdocs serve` 在本地测试
3. 确保更改不会破坏构建
4. 使用清晰、描述性的提交信息提交更改
5. 推送到您的 fork
6. 提交 Pull Request

## Pull Request 指南

- 使用清晰、描述性的标题
- 包含对更改的详细描述
- 引用相关 issue（例如："Fixes #123: Your Title"）
- 确保您的分支与主分支同步
- 对于界面/格式更改，请包含截图（如适用）

## 文件结构

```
docs/
├── index.md
├── chapter1.md
├── chapter2.md
└── assets/
    ├── image1.png
    └── image2.png
```

章节在 `mkdocs.yaml` 中定义，Markdown 文件和资源文件存储在 `docs` 目录中。
