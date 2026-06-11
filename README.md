# ABAP Code Review Skill for Claude Code

这是一个为 Claude Code 创建的 ABAP 代码审查技能（Skill），用于自动审查 ABAP 代码的质量、安全性和性能问题。

## 功能特性

### 审查范围
- **SQL 性能问题** - SELECT *, FOR ALL ENTRIES, 嵌套查询等
- **内存与性能** - 内部表管理、循环优化
- **安全问题** - SQL 注入、权限检查、敏感数据处理
- **编码规范** - 变量命名、异常处理、注释质量
- **现代 ABAP 特性** - 推荐使用现代语法和函数式编程

### 触发关键词
- "ABAP code review"
- "review ABAP"
- "检查 ABAP 代码"
- "ABAP 代码审查"

## 安装说明

技能文件已放置在 `.claude/skills/abap_code_review/SKILL.md`，Claude Code 会自动识别并加载此技能。

## 使用方法

当你在对话中提到上述触发关键词或分享 ABAP 代码时，skill 会自动进行代码审查并输出详细报告。

示例：
```
请帮我审查这段 ABAP 代码:
[粘贴 ABAP 代码]
```

## 审查输出格式

1. **总结** - 整体评估代码质量
2. **问题列表** - 按严重程度分类 (High/Medium/Low)
3. **行号引用** - 具体指出问题所在行
4. **修复建议** - 提供具体的代码改进方案

## 许可证

MIT License
