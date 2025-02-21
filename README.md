# Cursor 提示词仓库

该仓库为 Cursor IDE 的提示词仓库，提供了一套完整的 AI 辅助编程规则体系。

## 目录结构

```txt
.cursor/
├── docs/             # 项目索引文档
├── global-setting/   # 全局配置
├── notepads/         # 项目笔记
├── rules/            # 项目规则
├── sessions/         # 项目会话
```

## 快速开始

### 1. 添加全局规则

设置 "[Rules for AI](https://docs.cursor.com/context/rules-for-ai)"，该规则是全局规则。

位置：Settings > General > Rules for AI

参考：[.cursor/global-setting/rule-for-ai.md](.cursor/global-setting/rule-for-ai.md)

![Cursor 全局规则](/assets/global-rules.png)

### 2. 添加索引

设置 "[Codebase Indexing](https://docs.cursor.com/context/codebase-indexing)" 和 "Docs"。

位置：Settings > Features > Codebase Indexing

备注：[.cursorignore](.cursorignore) 文件中添加的规则，不会被 cursor 索引，但是可以被 chat 和 composer 上下文引用。类似 git 的 [.gitignore](.gitignore) 文件。

![Cursor 索引和文档](/assets/indexing-and-docs.png)

### 3. 使用项目规则

1. 克隆当前项目仓库

2. 复制规则文件：将 `.cursor` 目录下的 `rules` 目录下的文件复制到你的项目中。

此时 settings 中就可以查看到已有的规则。

选择你所需的规则文件，不需要的规则文件可以删除。

![Cursor 规则文件](/assets/project-rules.png)

## 贡献指南

1. Fork 本仓库
2. 创建特性分支
3. 提交变更
4. 发起 Pull Request
5. 等待审核
6. 合并到主分支
