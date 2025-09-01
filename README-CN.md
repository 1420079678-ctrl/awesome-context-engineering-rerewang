# Awesome Context Engineering 🚀

> Context Engineering 参考资料、框架和最佳实践的精选列表，用于构建生产级 AI 系统。

[English](README.md) | 中文

## 目录

* [关于概念](#关于概念)
* [为什么选择 Context Engineering 而不是 Vibe Coding？](#为什么选择-context-engineering-而不是-vibe-coding)
* [核心框架](#核心框架)
* [企业解决方案](#企业解决方案)
* [研究与论文](#研究与论文)
* [社区与资源](#社区与资源)
* [贡献](#贡献)

## 关于概念

**Context Engineering** 代表了超越传统 prompt engineering 和 vibe coding 的演进，专注于系统化、可扩展的方法来管理 AI 系统上下文。与 vibe coding 的"随波逐流"方法不同，Context Engineering 提供了构建可靠、生产就绪的 AI 应用程序的结构化方法。

> "Context Engineering 不仅仅是编写提示 - 它是关于架构 AI 系统如何理解、维护和发展其在复杂交互和长期操作中的上下文感知能力。" - Context Engineering 社区

## 为什么选择 Context Engineering 而不是 Vibe Coding？

### Vibe Coding 方法
* **理念**："随波逐流"，拥抱指数增长，忘记代码复杂性
* **重点**：快速原型设计，快速迭代，实验性开发
* **局限性**： 
  - 缺乏系统化的上下文管理
  - 难以保持长期一致性
  - 难以扩展到简单应用程序之外
  - 企业采用潜力有限

### Context Engineering 方法
* **理念**：系统化、可扩展、可靠的 AI 系统设计
* **重点**：生产级应用程序，企业解决方案，长期可维护性
* **优势**：
  - 结构化的上下文管理框架
  - 复杂交互中的一致行为
  - 可扩展到企业级应用程序
  - 内置的可靠性和测试能力
  - 专业开发工作流

### 何时选择每种方法

| 使用场景 | Vibe Coding | Context Engineering |
|----------|-------------|-------------------|
| **快速原型设计** | ✅ 优秀 | ⚠️ 过度设计 |
| **生产应用程序** | ❌ 有风险 | ✅ 推荐 |
| **团队协作** | ❌ 困难 | ✅ 优秀 |
| **长期项目** | ❌ 不可持续 | ✅ 必需 |
| **企业使用** | ❌ 不适合 | ✅ 完美匹配 |

## 核心框架

### 🔥 BMAD-METHOD
**多代理协作的 Context Engineering 框架**
* **核心概念**：协调多个专业代理（PM、PO、架构师、开发人员、QA、UX）来维护项目上下文
* **Context Engineering 优势**：每个代理维护和传递上下文信息，确保整个开发生命周期的一致性
* **使用场景**：复杂项目规划，团队协作，上下文驱动的项目管理
* **官方资源**：[GitHub](https://github.com/bmad-code-org/BMAD-METHOD)

### 🌐 AGENTS.md
**标准化 AI 代理指令框架**
* **核心概念**：为不同平台的 AI 代理提供可预测、标准化的指令
* **Context Engineering 优势**：标准化的上下文传输格式，支持跨工具和跨平台的上下文可移植性
* **主要特性**：代理无关，灵活格式，monorepo 支持
* **使用场景**：项目文档，AI 协作，团队知识转移
* **官方资源**：[网站](https://agents.md) | [示例](https://agents.md/#examples)

### 🚀 Claude Code Spec Workflow
**自动化上下文驱动开发框架**
* **核心概念**：规范驱动开发工作流（需求 → 设计 → 任务 → 实现），具有自动化上下文管理
* **Context Engineering 优势**：分层上下文管理策略，消除冗余加载，智能文档处理，减少 60-80% 的 token 消耗
* **主要特性**： 
  - 自动化规范创建和执行
  - Bug 修复工作流（报告 → 分析 → 修复 → 验证）
  - 上下文优化命令，实现高效的文档加载
  - 类型安全的项目处理，95%+ 类型覆盖率
* **使用场景**：新功能开发，Bug 解决，项目上下文管理
* **官方资源**：[GitHub](https://github.com/Pimzino/claude-code-spec-workflow) | [文档](https://github.com/Pimzino/claude-code-spec-workflow#readme)

### ⚡ Kiro Specs
**AI 驱动的规范和上下文管理系统**
* **核心概念**：先进的规范系统，使 AI 代理能够通过结构化规范理解项目上下文
* **Context Engineering 优势**：为 AI 代理提供全面的项目理解，实现上下文感知的开发和决策
* **主要特性**： 
  - AI 可读的项目规范
  - 上下文感知的项目分析
  - AI 代理的结构化信息
  - 增强的 AI 协作能力
* **使用场景**：AI 代理训练，项目上下文文档，增强的 AI 协作
* **官方资源**：[文档](https://kiro.dev/docs/specs/) | [官网](https://kiro.dev)

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING-CN.md)。

我们正在寻找：
* 新的 Context Engineering 框架和工具
* 案例研究和实施示例
* 研究论文和学术资源
* 社区工具和资源
* 翻译和本地化

## 关于

Context Engineering 参考资料、框架和最佳实践的精选列表，用于构建生产级 AI 系统。与 vibe coding 的实验性方法不同，Context Engineering 专注于系统化、可扩展、可靠的 AI 系统开发。

### 主题标签

`context-engineering` `ai` `enterprise-ai` `production-ai` `context-management` `ai-systems` `bmad-method` `agents-md` `claude-code-spec-workflow` `kiro-specs` `rag` `vector-databases`

---

**选择 Context Engineering 来构建超越原型的生产级 AI 系统！** 🚀

*最后更新：2025年9月*
