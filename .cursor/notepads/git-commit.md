# Git Commit 规范指南

本文档定义了项目的 Git commit 提交规范，用于保持代码提交的一致性和清晰性。

## 规范说明

通过定义明确的规范，我们可以：

- 保持提交记录的一致性
- 提高代码管理的可读性
- 支持 Cursor 自动生成规范的 commit message
- 提升团队开发效率

## 提交格式

### 基本格式

```txt
图标 类型(story): 描述信息
```

### 类型说明

- 📝 docs：文档更新
- 🆕 feat：新增模块
- ✨ feat：亮点功能
- 🐛 fix：修复缺陷
- 🔨 refactor：代码重构
- 🎨 style：代码格式
- ✅ test：测试相关
- ⚡ perf：性能优化
- 💄 ui：界面改进

## 示例

```git
📝 docs(auth): 更新用户认证文档
🆕 feat(user): 添加用户管理模块
🐛 fix(login): 修复登录验证失败问题
🔨 refactor(api): 重构 API 接口结构
```

## 参考资料

- [git commit emoji 使用指南](https://github.com/liuchengxu/git-commit-emoji-cn)
- [gitmoji](https://gitmoji.dev/)
- [Git Commit Message StyleGuide](https://github.com/slashsBin/styleguide-git-commit-message)
- [Commit message 和 Change log 编写指南](https://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)
