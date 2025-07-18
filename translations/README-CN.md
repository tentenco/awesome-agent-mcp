# 🤖 Awesome Agent MCP

> 精选的 AI 智能体和模型上下文协议 (MCP) 学习资源清单

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**创建者：** [Tenten.co - AI 优先产品代理商](https://tenten.co/)

## 📋 目录

- [介绍](#介绍)
- [AI 智能体](#ai-智能体)
  - [框架与库](#框架与库)
  - [开源项目](#开源项目)
  - [商业平台](#商业平台)
  - [开发工具](#开发工具)
- [模型上下文协议 (MCP)](#模型上下文协议-mcp)
  - [官方资源](#官方资源)
  - [MCP 服务器](#mcp-服务器)
  - [MCP 客户端](#mcp-客户端)
  - [教程与指南](#教程与指南)
- [学习资源](#学习资源)
- [社区](#社区)
- [贡献](#贡献)
- [许可证](#许可证)

## 🚀 介绍

欢迎来到最全面的 AI 智能体和模型上下文协议 (MCP) 学习资源集合。这个精选清单汇集了构建复杂 AI 智能体系统和利用标准化上下文协议所需的基本工具、框架、教程和资源。

### 什么是 AI 智能体？

AI 智能体是能够感知环境、做出决策并采取行动以实现特定目标的自主软件系统，无需持续的人工干预。这些智能系统结合了大型语言模型 (LLM) 的力量与使用工具、访问外部数据源和执行复杂多步骤工作流程的能力。

### 什么是模型上下文协议 (MCP)？

模型上下文协议 (MCP) 是 Anthropic 于 2024 年 11 月推出的开放标准，革命性地改变了 AI 应用程序连接数据源和工具的方式。将 MCP 视为"AI 应用程序的 USB-C"——它为 AI 模型访问外部资源提供了标准化、安全的方式。

## 🤖 AI 智能体

### 框架与库

#### 多智能体框架

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- 开发 LLM 应用程序的综合框架
- 具有工具、记忆和智能体能力的广泛生态系统
- 支持多个 LLM 提供商和向量数据库

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- 构建有状态、多角色应用程序的图形框架
- 建立在 LangChain 之上，具有增强的控制流程
- 适合复杂的智能体工作流程和状态管理

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- 微软的多智能体对话系统框架
- 使多个智能体能够协作完成复杂任务
- 支持代码执行和对话智能体

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- 基于角色的协作 AI 多智能体框架
- 智能体像团队一样协作，具有明确的角色和目标
- 内置任务委派和结果聚合

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- 微软的 AI 编排框架
- 支持多种编程语言（C#、Python、Java）
- 基于插件的架构，可扩展功能

**[OpenAI Swarm](https://github.com/openai/swarm)** ⭐ 13k+
- 轻量级多智能体编排框架
- 专注于智能体交接和协调
- 最小依赖且易于理解

#### 单智能体框架

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- 构建具有记忆和知识的 AI 智能体框架
- 内置对工具、存储和向量数据库的支持
- 与流行的 LLM 提供商轻松集成

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- 建立在 Pydantic 上的类型安全智能体框架
- 适合重视类型安全的 Python 开发者
- 内置验证的清洁 API 设计

### 开源项目

#### 通用智能体

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- 首批自主 AI 智能体之一
- 能够将目标分解为子任务并执行
- 网页浏览、文件操作和代码执行能力

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- 简单但强大的任务驱动自主智能体
- 使用 OpenAI 和向量数据库进行任务管理
- 持续创建和执行任务以达成目标

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- 专门从事代码生成和软件开发的 AI 智能体
- 能够从自然语言描述构建完整应用程序
- 具有人工反馈的迭代开发过程

**[MetaGPT](https://github.com/geekan/MetaGPT)** ⭐ 44k+
- 模拟软件公司的多智能体框架
- 智能体扮演产品经理、架构师、工程师等角色
- 能够生成包含文档的完整软件项目

#### 专业智能体

**[SWE-agent](https://github.com/princeton-nlp/SWE-agent)** ⭐ 13k+
- 专门解决 GitHub 问题的 AI 智能体
- 能够理解代码库并实施修复
- 专为软件工程任务设计

**[Aider](https://github.com/paul-gauthier/aider)** ⭐ 20k+
- 终端中的 AI 配对编程工具
- 与现有代码库和 git 仓库协作
- 支持多个 LLM 提供商

### 商业平台

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- 构建自定义副驾驶的企业平台
- 与 Microsoft 365 和 Azure 服务集成
- 无代码/低代码开发环境

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- 客户服务和销售的 AI 智能体平台
- 常见商业用例的预构建智能体
- 与 Salesforce CRM 和生态系统集成

**[Google Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder)**
- Google Cloud 构建 AI 智能体的平台
- 与 Google 的 AI 模型和服务集成
- 企业级安全性和可扩展性

### 开发工具

**[AgentOps](https://github.com/AgentOps-AI/agentops)** ⭐ 2k+
- AI 智能体的可观察性平台
- 性能监控和调试工具
- 成本跟踪和优化洞察

**[LangSmith](https://smith.langchain.com/)**
- LLM 应用程序开发平台
- 调试、测试和监控能力
- 智能体性能评估框架

**[E2B](https://e2b.dev/)**
- AI 智能体的云运行时
- 安全的代码执行环境
- 智能体部署和扩展的 API

## 🔌 模型上下文协议 (MCP)

### 官方资源

**[模型上下文协议网站](https://modelcontextprotocol.io/)**
- 官方文档和规范
- 入门指南和教程
- 架构概述和最佳实践

**[MCP GitHub 组织](https://github.com/modelcontextprotocol)**
- 官方 MCP 仓库和工具
- 参考实现和 SDK
- 社区贡献和示例

**[Anthropic MCP 文档](https://docs.anthropic.com/en/docs/mcp)**
- Claude 特定的 MCP 集成指南
- API 文档和示例
- 安全最佳实践

### MCP 服务器

#### 数据库与存储

**[SQLite MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- 连接到 SQLite 数据库
- 执行查询和检索数据
- 模式内省能力

**[PostgreSQL MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- 完整的 PostgreSQL 数据库集成
- 高级查询能力
- 连接池和优化

**[MongoDB MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/mongodb)**
- NoSQL 数据库连接
- 基于文档的数据操作
- 聚合管道支持

#### 文件系统与云存储

**[文件系统 MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- 本地文件系统访问
- 文件读取、写入和操作
- 目录遍历和搜索

**[AWS S3 MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3 存储桶集成
- 对象存储和检索
- 元数据管理

**[Google Drive MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)**
- Google Drive 文件访问
- 文档协作功能
- 共享和权限管理

#### API 与网络服务

**[GitHub MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHub 仓库集成
- 问题和拉取请求管理
- 代码搜索和分析

**[Slack MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slack 工作区集成
- 消息发送和检索
- 频道和用户管理

**[Notion MCP 服务器](https://github.com/modelcontextprotocol/servers/tree/main/src/notion)**
- Notion 工作区连接
- 页面和数据库操作
- 内容创建和编辑

### MCP 客户端

**[Claude Desktop](https://claude.ai/download)**
- Anthropic 官方桌面客户端
- 原生 MCP 服务器集成
- 安全的本地数据访问

**[Continue](https://continue.dev/)**
- VS Code 和 JetBrains 扩展
- 开发的 MCP 服务器支持
- 代码完成和协助

### 教程与指南

**[MCP 快速入门指南](https://modelcontextprotocol.io/quickstart)**
- 逐步设置说明
- 第一个 MCP 服务器创建
- 基本客户端集成

**[构建您的第一个 MCP 服务器](https://modelcontextprotocol.io/tutorials/first-server)**
- 服务器开发演练
- TypeScript 和 Python 示例
- 测试和调试技术

## 📚 学习资源

### 文档

**[LangChain 文档](https://python.langchain.com/)**
- LangChain 框架的综合指南
- API 参考和示例
- 集成教程和最佳实践

**[AutoGen 文档](https://microsoft.github.io/autogen/)**
- 微软 AutoGen 框架指南
- 多智能体系统教程
- 代码示例和用例

**[OpenAI API 文档](https://platform.openai.com/docs)**
- OpenAI API 参考和指南
- 函数调用和工具使用
- 智能体开发最佳实践

### 课程与教程

**[DeepLearning.AI - LangGraph 中的 AI 智能体](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- 构建 AI 智能体的实践课程
- LangGraph 框架深度探讨
- 真实世界项目实现

**[DeepLearning.AI - 使用 crewAI 的多 AI 智能体系统](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- 多智能体系统开发
- CrewAI 框架精通
- 协作智能体工作流程

**[DeepLearning.AI - MCP：构建丰富上下文的 AI 应用程序](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)**
- 模型上下文协议基础
- 构建 MCP 服务器和客户端
- 与现有应用程序集成

### 书籍

**"使用 LangChain 构建 LLM 应用程序" by Valentina Alto**
- LangChain 开发的综合指南
- 实用示例和用例
- 生产部署策略

**"AI 智能体：理论与实践" by Stuart Russell**
- AI 智能体的理论基础
- 决策制定和规划算法
- 多智能体系统和协调

### 研究论文

**[ReAct：在语言模型中协同推理和行动](https://arxiv.org/abs/2210.03629)**
- 推理和行动的基础论文
- 使用工具的语言模型框架
- 实验结果和分析

**[Toolformer：语言模型可以自学使用工具](https://arxiv.org/abs/2302.04761)**
- 自监督工具学习方法
- API 集成和使用模式
- 性能评估和基准

## 🌟 社区

### 论坛与讨论平台

**[LangChain Discord](https://discord.gg/langchain)**
- 活跃的 LangChain 开发者社区
- 实时帮助和支持
- 框架更新和公告

**[AutoGen Discord](https://discord.gg/autogen)**
- 微软 AutoGen 社区中心
- 多智能体开发讨论
- 研究协作机会

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- 社区讨论和新闻
- 项目分享和反馈
- 教程推荐

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- 一般 AI 智能体开发社区
- 框架比较和评论
- 用例讨论和示例

### GitHub 社区

**[Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents)**
- AI 智能体项目的综合列表
- 社区贡献和更新
- 项目发现和探索

**[LangChain 社区](https://github.com/langchain-ai/langchain/discussions)**
- 官方 LangChain 讨论
- 功能请求和反馈
- 社区驱动的改进

## 🤝 贡献

我们欢迎对这个精选列表的贡献！请在提交拉取请求之前阅读我们的[贡献指南](CONTRIBUTING.md)。

### 如何贡献

1. **分叉仓库**并创建新分支
2. **在适当的类别中添加您的资源**
3. **遵循现有条目使用的格式**
4. **确保资源是高质量且相关的**
5. **提交拉取请求**并提供清晰的描述

## 📄 许可证

本作品采用[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-sa/4.0/)进行许可。

---

## 🚀 通过 AI 自动化转型您的业务

准备好为您的业务利用 AI 智能体和 MCP 的力量了吗？**[Tenten](https://tenten.co)** 是您值得信赖的 AI 优先产品代理商，专精于尖端 AI 自动化咨询和实施。我们的专家团队帮助企业集成复杂的 AI 智能体系统、实施模型上下文协议解决方案，并通过智能自动化转型运营。

无论您是希望简化工作流程、增强客户体验，还是构建自定义的 AI 驱动应用程序，Tenten 都能提供推动真正商业价值的企业级解决方案。从策略和设计到开发和部署，我们引导您完成 AI 转型旅程的每一步。

**[与我们的 AI 专家预约会议](https://tenten.co/contact)**，了解 AI 智能体和 MCP 如何革命化您的业务运营。

### 🔗 探索更多 Tenten 资源

- **[开发者博客](https://developer.tenten.co/)** - 技术洞察和教程
- **[Shopify 开发者博客](https://shopify.tenten.co/)** - 电商 AI 解决方案
- **[Tenten AI 博客](https://tenten.co/learning/)** - AI 行业洞察和趋势
- **[GEO (AI SEO) by Tenten](https://geo.tenten.co/zh-tw)** - AI 驱动的 SEO 解决方案
- **[领先的 Webflow 代理商](https://tenten.co/solution/webflow-agency)** - 网页开发专业知识
- **[Shopify Plus 代理商](https://tenten.co/solution/shopify)** - 电商平台解决方案
- **[Tenten AI - AI 转型咨询](https://tentenai.com/)** - 在 AI 时代重新定义业务

### 📱 与 Tenten 连接

- **[在 Instagram 上关注我们](https://instagram.com/tenten.co)** - 幕后花絮和更新
- **[订阅我们的 YouTube](https://www.youtube.com/@tenten_ai)** - 视频教程和洞察
- **[在 LinkedIn 上连接](https://www.linkedin.com/company/tentenco)** - 专业更新和行业新闻
- **[在 Threads 上加入我们](https://www.threads.net/@tenten.co)** - 快速更新和讨论
- **[在 TikTok 上关注](https://www.tiktok.com/@tenten.ai)** - 短视频 AI 内容
- **[在 X (Twitter) 上关注](https://x.com/tentencretaive)** - 实时更新和洞察
- **[订阅我们的电子报](https://tenten.co/page/company/newsletter)** - 每周 AI 洞察直送您的邮箱
- **[探索我们所有的链接](https://linktr.ee/tenten.co)** - 一站式访问所有 Tenten 资源

---

*这个精选列表由社区维护，并由 [Tenten.co](https://tenten.co/) 策划。最后更新：2025 年 7 月*

