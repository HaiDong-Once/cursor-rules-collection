# Cursor Rules 集合

![GitHub stars](https://img.shields.io/github/stars/yourusername/cursor-rules-collection?style=social)
![GitHub license](https://img.shields.io/github/license/yourusername/cursor-rules-collection)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/cursor-rules-collection)

一套全面的、可复用的 Cursor Rules 集合，涵盖前端开发、数据分析、爬虫和其他开发实践领域。这些规则旨在提升开发效率、代码质量和项目一致性。

## 仓库更新记录
### 2025-05-07
- 新增 **core/001-user-rule.md** : 用户规则, 全局适用于 Cursor 环境
- 新增 **core/002-code-style.mdc** : 代码格式化、命名约定和一致性指南
- 新增 **frontend/300-frontend-team-code-standards.mdc** : 前端团队代码规范与标准指南
- 新增 **frontend/301-html-structure.mdc** : HTML结构和语义化编写规范
- 新增 **frontend/302-css-best-practices.mdc** : CSS最佳实践和样式指南
- 新增 **frontend/303-javascript-guide.mdc** : JavaScript编码规范和最佳实践
- 新增 **frontend/304-react-patterns.mdc** : React开发模式和组件设计指南
- 新增 **frontend/305-vue-patterns.mdc** : Vue开发模式和组件设计指南

## 📑 主要特点

- **可直接导入**：轻松将规则导入到任何 Cursor 项目中
- **分类明确**：按功能和用途分类的规则体系
- **持续更新**：不断迭代优化的最佳实践集合
- **开源共享**：欢迎贡献和使用

## 🗂️ 规则分类

仓库中的规则按以下类别组织：

### 核心规则 (001-099)
基础开发规范和通用最佳实践

### 集成规则 (100-199)
API、CLI、数据处理等集成功能的规则

### 模式/角色规则 (200-299)
特定开发模式、架构和项目角色相关规则

### 前端规则 (300-399)
前端开发专用规则

### 性能优化规则 (400-499)
性能分析和优化相关规则

### 数据处理规则 (500-599)
数据分析、爬虫和数据处理规则

### 工作流规则 (600-699)
各类工作流程和项目管理规则

## 🚀 快速开始

### 导入规则到 Cursor 项目

1. 克隆此仓库或下载特定规则文件
```bash
git clone https://github.com/HaiDong-Once/cursor-rules-collection.git
```

2. 将所需规则复制到您项目的 `.cursor/rules` 目录
```bash
cp cursor-rules-collection/core/001-core-safe.mdc your-project/.cursor/rules/
```

3. 在 Cursor 中使用规则

### 示例用法

以下是如何使用核心安全规则的示例：

```markdown
# 使用安全核心规则检查项目
按照规则 [001-core-safe.mdc](mdc:.cursor/rules/001-core-safe.mdc) 检查代码中的安全问题
```

## 📋 规则列表

请查看各目录下的 README 文件获取详细的规则说明。

## 🤝 贡献指南

我们欢迎并鼓励社区贡献新的规则或改进现有规则：

1. Fork 此仓库
2. 创建您的功能分支 (`git checkout -b feature/amazing-rule`)
3. 提交您的更改 (`git commit -m 'Add some amazing rule'`)
4. 推送到分支 (`git push origin feature/amazing-rule`)
5. 创建一个 Pull Request

## 📄 许可证

此项目基于 MIT 许可证 - 详细信息请查看 [LICENSE](LICENSE) 文件。

## 🔍 关键词

cursor, development, rules, best practices, frontend, data analysis, web scraping, performance optimization, coding standards, development workflow, AI coding assistant