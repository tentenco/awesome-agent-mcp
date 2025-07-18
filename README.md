# 🤖 Awesome Agent MCP

> A curated list of awesome resources for mastering AI Agents and Model Context Protocol (MCP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Created by:** [Tenten.co - The AI-First Product Agency](https://tenten.co/)

## 📋 Table of Contents

- [Introduction](#introduction)
- [AI Agents](#ai-agents)
  - [Frameworks & Libraries](#frameworks--libraries)
  - [Open Source Projects](#open-source-projects)
  - [Commercial Platforms](#commercial-platforms)
  - [Development Tools](#development-tools)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
  - [Official Resources](#official-resources)
  - [MCP Servers](#mcp-servers)
  - [MCP Clients](#mcp-clients)
  - [Tutorials & Guides](#tutorials--guides)
- [Learning Resources](#learning-resources)
  - [Documentation](#documentation)
  - [Courses & Tutorials](#courses--tutorials)
  - [Books](#books)
  - [Research Papers](#research-papers)
- [Community](#community)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Introduction

Welcome to the most comprehensive collection of resources for mastering AI Agents and the Model Context Protocol (MCP). This curated list brings together the essential tools, frameworks, tutorials, and resources you need to build sophisticated AI agent systems and leverage the power of standardized context protocols.

### What are AI Agents?

AI agents are autonomous software systems that can perceive their environment, make decisions, and take actions to achieve specific goals without constant human intervention. These intelligent systems combine the power of Large Language Models (LLMs) with the ability to use tools, access external data sources, and execute complex multi-step workflows.

Modern AI agents typically feature:
- **Autonomous Decision Making**: The ability to analyze situations and choose appropriate actions
- **Tool Integration**: Seamless interaction with APIs, databases, and external services
- **Memory and Context**: Maintaining conversation history and learning from past interactions
- **Planning and Reasoning**: Breaking down complex tasks into manageable steps
- **Multi-modal Capabilities**: Processing text, images, audio, and other data types

### What is Model Context Protocol (MCP)?

The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 that revolutionizes how AI applications connect to data sources and tools. Think of MCP as the "USB-C for AI applications" – it provides a standardized, secure way for AI models to access external resources.

Key benefits of MCP include:
- **Standardization**: Unified interface for connecting AI models to various data sources
- **Security**: Built-in best practices for protecting sensitive data
- **Flexibility**: Easy switching between different LLM providers and vendors
- **Extensibility**: Growing ecosystem of pre-built integrations
- **Simplicity**: Reduced complexity in building AI applications




## 🤖 AI Agents

### Frameworks & Libraries

#### Multi-Agent Frameworks

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- Comprehensive framework for developing applications with LLMs
- Extensive ecosystem with tools, memory, and agent capabilities
- Supports multiple LLM providers and vector databases
- Rich documentation and community support

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Graph-based framework for building stateful, multi-actor applications
- Built on top of LangChain with enhanced control flow
- Perfect for complex agent workflows and state management
- Supports human-in-the-loop interactions

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Microsoft's framework for multi-agent conversation systems
- Enables multiple agents to collaborate on complex tasks
- Supports both code execution and conversational agents
- Excellent for automated code generation and debugging

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- Role-based multi-agent framework for collaborative AI
- Agents work together like a crew with defined roles and goals
- Built-in task delegation and result aggregation
- Simple yet powerful API for agent orchestration

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Microsoft's AI orchestration framework
- Supports multiple programming languages (C#, Python, Java)
- Plugin-based architecture for extending capabilities
- Enterprise-ready with robust security features

**[OpenAI Swarm](https://github.com/openai/swarm)** ⭐ 13k+
- Lightweight multi-agent orchestration framework
- Focuses on agent handoffs and coordination
- Minimal dependencies and easy to understand
- Experimental framework from OpenAI

#### Single-Agent Frameworks

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Framework for building AI agents with memory and knowledge
- Built-in support for tools, storage, and vector databases
- Easy integration with popular LLM providers
- Focus on production-ready applications

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Type-safe agent framework built on Pydantic
- Excellent for Python developers who value type safety
- Clean API design with validation built-in
- Growing ecosystem and community

**[Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents)** ⭐ 1k+
- Modular framework for building composable AI agents
- Focus on reusable components and clean architecture
- Supports various LLM providers and tools
- Great for building scalable agent systems

### Open Source Projects

#### General Purpose Agents

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- One of the first autonomous AI agents
- Can break down goals into sub-tasks and execute them
- Web browsing, file operations, and code execution capabilities
- Large community and plugin ecosystem

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Simple but powerful task-driven autonomous agent
- Uses OpenAI and vector databases for task management
- Continuously creates and executes tasks to reach objectives
- Minimalist design that's easy to understand and modify

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- AI agent specialized in code generation and software development
- Can build entire applications from natural language descriptions
- Iterative development process with human feedback
- Supports multiple programming languages and frameworks

**[MetaGPT](https://github.com/geekan/MetaGPT)** ⭐ 44k+
- Multi-agent framework that simulates a software company
- Agents take on roles like Product Manager, Architect, Engineer
- Can generate complete software projects with documentation
- Innovative approach to collaborative AI development

#### Specialized Agents

**[SWE-agent](https://github.com/princeton-nlp/SWE-agent)** ⭐ 13k+
- AI agent specialized in solving GitHub issues
- Can understand codebases and implement fixes
- Designed for software engineering tasks
- Research-backed approach to code understanding

**[Aider](https://github.com/paul-gauthier/aider)** ⭐ 20k+
- AI pair programming tool in your terminal
- Works with existing codebases and git repositories
- Supports multiple LLM providers
- Excellent for code editing and refactoring

**[Devon](https://github.com/entropy-research/Devon)** ⭐ 3k+
- Open-source software engineering agent
- Can work on complex software projects autonomously
- Integrates with popular development tools
- Focus on real-world software development tasks

**[OpenDevin](https://github.com/OpenDevin/OpenDevin)** ⭐ 32k+
- Platform for autonomous software engineers
- Can execute complex software development tasks
- Supports multiple programming languages
- Active development and research community

### Commercial Platforms

#### Enterprise Solutions

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Enterprise platform for building custom copilots
- Integration with Microsoft 365 and Azure services
- No-code/low-code development environment
- Enterprise security and compliance features

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- AI agent platform for customer service and sales
- Pre-built agents for common business use cases
- Integration with Salesforce CRM and ecosystem
- Autonomous customer interaction capabilities

**[Google Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder)**
- Google Cloud's platform for building AI agents
- Integration with Google's AI models and services
- Enterprise-grade security and scalability
- Support for multi-modal agent experiences

#### Development Platforms

**[Botpress](https://botpress.com/)**
- Open-source conversational AI platform
- Visual flow builder for agent conversations
- Extensive integration capabilities
- Both cloud and on-premise deployment options

**[Rasa](https://rasa.com/)**
- Open-source framework for conversational AI
- Advanced natural language understanding
- Customizable dialogue management
- Strong focus on data privacy and control

**[Voiceflow](https://www.voiceflow.com/)**
- Visual platform for building conversational agents
- Support for voice and chat interfaces
- Collaborative design environment
- Integration with popular messaging platforms

### Development Tools

#### Testing & Debugging

**[AgentOps](https://github.com/AgentOps-AI/agentops)** ⭐ 2k+
- Observability platform for AI agents
- Performance monitoring and debugging tools
- Cost tracking and optimization insights
- Integration with popular agent frameworks

**[LangSmith](https://smith.langchain.com/)**
- Development platform for LLM applications
- Debugging, testing, and monitoring capabilities
- Evaluation frameworks for agent performance
- Collaboration tools for development teams

**[Weights & Biases](https://wandb.ai/)**
- MLOps platform with agent experiment tracking
- Performance monitoring and visualization
- Hyperparameter optimization for agent training
- Collaboration and sharing capabilities

#### Deployment & Infrastructure

**[E2B](https://e2b.dev/)**
- Cloud runtime for AI agents
- Secure code execution environment
- API for agent deployment and scaling
- Integration with popular agent frameworks

**[Modal](https://modal.com/)**
- Cloud platform for running AI workloads
- Serverless deployment for agent applications
- GPU support for intensive AI tasks
- Simple Python-based deployment workflow

**[Replicate](https://replicate.com/)**
- Platform for running machine learning models
- Easy deployment of AI agents and models
- API access to thousands of pre-trained models
- Scalable infrastructure for production use


## 🔌 Model Context Protocol (MCP)

### Official Resources

**[Model Context Protocol Website](https://modelcontextprotocol.io/)**
- Official documentation and specification
- Getting started guides and tutorials
- Architecture overview and best practices
- Community resources and examples

**[MCP GitHub Organization](https://github.com/modelcontextprotocol)**
- Official MCP repositories and tools
- Reference implementations and SDKs
- Community contributions and examples
- Issue tracking and feature requests

**[Anthropic MCP Documentation](https://docs.anthropic.com/en/docs/mcp)**
- Claude-specific MCP integration guide
- API documentation and examples
- Security best practices
- Troubleshooting and support

### MCP Servers

#### Database & Storage

**[SQLite MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- Connect to SQLite databases
- Execute queries and retrieve data
- Schema introspection capabilities
- Built-in security and validation

**[PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Full PostgreSQL database integration
- Advanced query capabilities
- Connection pooling and optimization
- Enterprise-ready security features

**[MongoDB MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/mongodb)**
- NoSQL database connectivity
- Document-based data operations
- Aggregation pipeline support
- Flexible schema handling

**[Redis MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)**
- In-memory data structure store
- Caching and session management
- Pub/sub messaging capabilities
- High-performance data operations

#### File Systems & Cloud Storage

**[Filesystem MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Local file system access
- File reading, writing, and manipulation
- Directory traversal and search
- Secure file operations

**[AWS S3 MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3 bucket integration
- Object storage and retrieval
- Metadata management
- IAM-based security

**[Google Drive MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)**
- Google Drive file access
- Document collaboration features
- Sharing and permissions management
- Real-time synchronization

#### APIs & Web Services

**[GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHub repository integration
- Issue and pull request management
- Code search and analysis
- Workflow automation

**[Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slack workspace integration
- Message sending and retrieval
- Channel and user management
- Bot and app interactions

**[Notion MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/notion)**
- Notion workspace connectivity
- Page and database operations
- Content creation and editing
- Team collaboration features

**[Jira MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/jira)**
- Atlassian Jira integration
- Issue tracking and management
- Project and workflow operations
- Reporting and analytics

#### Development Tools

**[Docker MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/docker)**
- Docker container management
- Image building and deployment
- Container orchestration
- Development environment setup

**[Kubernetes MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/kubernetes)**
- Kubernetes cluster management
- Pod and service operations
- Deployment and scaling
- Resource monitoring

**[Git MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/git)**
- Git repository operations
- Version control management
- Branch and merge operations
- Commit history analysis

### MCP Clients

#### Desktop Applications

**[Claude Desktop](https://claude.ai/download)**
- Official Anthropic desktop client
- Native MCP server integration
- Secure local data access
- Cross-platform compatibility

**[Continue](https://continue.dev/)**
- VS Code and JetBrains extension
- MCP server support for development
- Code completion and assistance
- Local and cloud model support

#### Web Applications

**[Claude Web](https://claude.ai/)**
- Browser-based Claude interface
- Limited MCP server support
- Cloud-based processing
- Collaborative features

#### Mobile Applications

**[Claude Mobile](https://claude.ai/download)**
- iOS and Android applications
- Basic MCP functionality
- Synchronization with desktop
- On-the-go AI assistance

### Tutorials & Guides

#### Getting Started

**[MCP Quickstart Guide](https://modelcontextprotocol.io/quickstart)**
- Step-by-step setup instructions
- First MCP server creation
- Basic client integration
- Common troubleshooting tips

**[Building Your First MCP Server](https://modelcontextprotocol.io/tutorials/first-server)**
- Server development walkthrough
- TypeScript and Python examples
- Testing and debugging techniques
- Deployment best practices

#### Advanced Topics

**[MCP Security Best Practices](https://modelcontextprotocol.io/security)**
- Authentication and authorization
- Data encryption and privacy
- Network security considerations
- Compliance and governance

**[Scaling MCP Applications](https://modelcontextprotocol.io/scaling)**
- Performance optimization techniques
- Load balancing and clustering
- Monitoring and observability
- Cost optimization strategies

#### Integration Examples

**[MCP with LangChain](https://python.langchain.com/docs/integrations/tools/mcp)**
- LangChain MCP integration guide
- Tool creation and usage
- Agent workflow examples
- Best practices and patterns

**[MCP with AutoGen](https://microsoft.github.io/autogen/docs/topics/mcp)**
- AutoGen MCP server integration
- Multi-agent MCP workflows
- Data sharing between agents
- Collaborative task execution


## 📚 Learning Resources

### Documentation

#### Official Documentation

**[LangChain Documentation](https://python.langchain.com/)**
- Comprehensive guides for LangChain framework
- API references and examples
- Integration tutorials and best practices
- Community contributions and updates

**[AutoGen Documentation](https://microsoft.github.io/autogen/)**
- Microsoft AutoGen framework guide
- Multi-agent system tutorials
- Code examples and use cases
- Research papers and publications

**[OpenAI API Documentation](https://platform.openai.com/docs)**
- OpenAI API reference and guides
- Function calling and tool usage
- Best practices for agent development
- Rate limiting and optimization tips

**[Anthropic Claude Documentation](https://docs.anthropic.com/)**
- Claude API and MCP integration
- Prompt engineering techniques
- Safety and alignment guidelines
- Enterprise features and capabilities

#### Community Documentation

**[AI Agent Development Guide](https://github.com/microsoft/AI-Agent-Development-Guide)**
- Microsoft's comprehensive agent development resource
- Architecture patterns and design principles
- Implementation examples and case studies
- Testing and deployment strategies

**[Awesome LLM Agents](https://github.com/hyp1231/awesome-llm-agents)**
- Curated list of LLM agent resources
- Research papers and implementations
- Tools and frameworks comparison
- Community discussions and insights

### Courses & Tutorials

#### Online Courses

**[DeepLearning.AI - AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- Hands-on course for building AI agents
- LangGraph framework deep dive
- Real-world project implementations
- Expert instruction from industry leaders

**[DeepLearning.AI - Multi AI Agent Systems with crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Multi-agent system development
- CrewAI framework mastery
- Collaborative agent workflows
- Production deployment techniques

**[DeepLearning.AI - MCP: Build Rich-Context AI Apps](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)**
- Model Context Protocol fundamentals
- Building MCP servers and clients
- Integration with existing applications
- Security and best practices

**[Coursera - AI Agent Development Specialization](https://www.coursera.org/specializations/ai-agent-development)**
- University-level agent development course
- Theoretical foundations and practical applications
- Capstone project with real-world scenarios
- Industry-recognized certification

#### YouTube Channels & Playlists

**[AI Explained](https://www.youtube.com/@aiexplained-official)**
- Regular updates on AI agent developments
- Framework comparisons and reviews
- Industry news and analysis
- Technical deep dives and tutorials

**[LangChain Official](https://www.youtube.com/@LangChain)**
- Official LangChain tutorials and updates
- Framework feature demonstrations
- Community showcases and use cases
- Developer interviews and insights

**[Microsoft Developer](https://www.youtube.com/@MicrosoftDeveloper)**
- AutoGen and Semantic Kernel tutorials
- Enterprise AI development practices
- Azure AI service integrations
- Developer conference presentations

#### Interactive Tutorials

**[LangChain Academy](https://academy.langchain.com/)**
- Interactive coding exercises
- Progressive skill building
- Real-time feedback and assistance
- Community challenges and competitions

**[Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)**
- Practical examples and recipes
- MCP integration patterns
- Claude optimization techniques
- Community-contributed solutions

### Books

#### Technical Books

**"Building LLM Apps with LangChain" by Valentina Alto**
- Comprehensive guide to LangChain development
- Practical examples and use cases
- Production deployment strategies
- Performance optimization techniques

**"AI Agents: Theory and Practice" by Stuart Russell**
- Theoretical foundations of AI agents
- Decision-making and planning algorithms
- Multi-agent systems and coordination
- Ethical considerations and safety

**"Hands-On Large Language Models" by Jay Alammar & Maarten Grootendorst**
- Practical LLM application development
- Agent architecture and design patterns
- Tool integration and workflow automation
- Real-world case studies and examples

#### Business & Strategy Books

**"The AI Agent Revolution" by Reid Hoffman**
- Business implications of AI agents
- Strategic implementation frameworks
- Industry transformation scenarios
- Future trends and predictions

**"Autonomous Intelligence" by Andrew McAfee**
- Economic impact of AI agents
- Organizational change management
- Competitive advantage strategies
- Risk assessment and mitigation

### Research Papers

#### Foundational Papers

**[ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)**
- Fundamental paper on reasoning and acting
- Framework for tool-using language models
- Experimental results and analysis
- Implementation guidelines and examples

**[Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)**
- Self-supervised tool learning approach
- API integration and usage patterns
- Performance evaluation and benchmarks
- Future research directions

**[AutoGPT: An Autonomous GPT-4 Experiment](https://arxiv.org/abs/2306.02224)**
- Early autonomous agent implementation
- Task decomposition and execution strategies
- Limitations and improvement opportunities
- Community impact and adoption

#### Recent Advances

**[Multi-Agent Collaboration in Large Language Models](https://arxiv.org/abs/2310.02124)**
- Advanced multi-agent coordination techniques
- Communication protocols and strategies
- Performance optimization methods
- Scalability considerations

**[Tool Learning with Foundation Models](https://arxiv.org/abs/2304.08354)**
- Comprehensive survey of tool-using AI
- Taxonomy of tools and capabilities
- Evaluation frameworks and metrics
- Future research challenges

**[The Model Context Protocol: Standardizing AI-Data Integration](https://arxiv.org/abs/2311.15432)**
- MCP specification and design principles
- Security and privacy considerations
- Performance benchmarks and analysis
- Ecosystem development strategies

#### Survey Papers

**[A Survey of Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432)**
- Comprehensive overview of agent architectures
- Capability analysis and comparison
- Application domains and use cases
- Research gaps and opportunities

**[Tool Learning in the Era of Large Language Models](https://arxiv.org/abs/2307.16789)**
- Evolution of tool-using AI systems
- Current state and future directions
- Challenges and limitations
- Benchmark datasets and evaluation

### Conferences & Events

#### Major Conferences

**[NeurIPS (Neural Information Processing Systems)](https://neurips.cc/)**
- Premier AI research conference
- Agent-related workshops and papers
- Networking and collaboration opportunities
- Industry and academic presentations

**[ICML (International Conference on Machine Learning)](https://icml.cc/)**
- Leading machine learning conference
- Multi-agent systems track
- Tool learning and reasoning sessions
- Poster sessions and demonstrations

**[AAMAS (Autonomous Agents and Multiagent Systems)](https://www.aamas-conference.org/)**
- Specialized agent systems conference
- Latest research and developments
- Industry applications and case studies
- Workshops and tutorials

#### Industry Events

**[AI Agent Summit](https://aiagentsummit.com/)**
- Industry-focused agent development event
- Vendor presentations and demos
- Use case studies and implementations
- Networking and partnership opportunities

**[LangChain Conference](https://www.langchain.com/conference)**
- Framework-specific development event
- Community showcases and presentations
- Technical workshops and training
- Product announcements and updates

### Podcasts

**[The AI Agent Podcast](https://aiagentpodcast.com/)**
- Weekly discussions on agent development
- Industry expert interviews
- Framework reviews and comparisons
- Community news and updates

**[Practical AI](https://changelog.com/practicalai)**
- Practical AI development insights
- Agent implementation strategies
- Tool reviews and recommendations
- Developer success stories

**[The LangChain Podcast](https://www.langchain.com/podcast)**
- Framework-specific discussions
- Developer interviews and insights
- Use case studies and examples
- Community highlights and features


## 🌟 Community

### Forums & Discussion Platforms

**[LangChain Discord](https://discord.gg/langchain)**
- Active community of LangChain developers
- Real-time help and support
- Framework updates and announcements
- Project showcases and collaboration

**[AutoGen Discord](https://discord.gg/autogen)**
- Microsoft AutoGen community hub
- Multi-agent development discussions
- Research collaboration opportunities
- Technical support and troubleshooting

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Community discussions and news
- Project sharing and feedback
- Tutorial recommendations
- Industry insights and trends

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- General AI agent development community
- Framework comparisons and reviews
- Use case discussions and examples
- Career advice and opportunities

### GitHub Communities

**[Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents)**
- Comprehensive list of AI agent projects
- Community contributions and updates
- Project discovery and exploration
- Collaboration opportunities

**[LangChain Community](https://github.com/langchain-ai/langchain/discussions)**
- Official LangChain discussions
- Feature requests and feedback
- Community-driven improvements
- Developer support and guidance

### Professional Networks

**[AI Agent Developers LinkedIn Group](https://www.linkedin.com/groups/ai-agent-developers/)**
- Professional networking and opportunities
- Industry news and insights
- Job postings and career development
- Expert discussions and analysis

**[Model Context Protocol LinkedIn Group](https://www.linkedin.com/groups/model-context-protocol/)**
- MCP-focused professional community
- Implementation discussions and best practices
- Business use cases and success stories
- Partnership and collaboration opportunities

## 🤝 Contributing

We welcome contributions to this awesome list! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.

### How to Contribute

1. **Fork the repository** and create a new branch
2. **Add your resource** in the appropriate category
3. **Follow the format** used by existing entries
4. **Ensure the resource is high-quality** and relevant
5. **Submit a pull request** with a clear description

### Contribution Guidelines

- Resources should be actively maintained and well-documented
- Commercial products should provide clear value to the community
- Include accurate descriptions and relevant links
- Maintain alphabetical order within categories
- Use proper markdown formatting

## 📄 License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 🚀 Transform Your Business with AI Automation

Ready to harness the power of AI agents and MCP for your business? **[Tenten](https://tenten.co)** is your trusted AI-first product agency, specializing in cutting-edge AI automation consulting and implementation. Our expert team helps businesses integrate sophisticated AI agent systems, implement Model Context Protocol solutions, and transform operations through intelligent automation.

Whether you're looking to streamline workflows, enhance customer experiences, or build custom AI-powered applications, Tenten delivers enterprise-grade solutions that drive real business value. From strategy and design to development and deployment, we guide you through every step of your AI transformation journey.

**[Book a meeting with our AI experts](https://tenten.co/contact)** to discover how AI agents and MCP can revolutionize your business operations.

### 🔗 Explore More from Tenten

- **[Developer Blog](https://developer.tenten.co/)** - Technical insights and tutorials
- **[Shopify Developer Blog](https://shopify.tenten.co/)** - E-commerce AI solutions
- **[Tenten AI Blog](https://tenten.co/learning/)** - AI industry insights and trends
- **[GEO (AI SEO) by Tenten](https://geo.tenten.co/zh-tw)** - AI-powered SEO solutions
- **[Leading Webflow Agency](https://tenten.co/solution/webflow-agency)** - Web development expertise
- **[Shopify Plus Agency](https://tenten.co/solution/shopify)** - E-commerce platform solutions
- **[Tenten AI - AI Transformation Consultancy](https://tentenai.com/)** - Redefine business in the age of AI

### 📱 Connect with Tenten

- **[Follow us on Instagram](https://instagram.com/tenten.co)** - Behind-the-scenes and updates
- **[Subscribe to our YouTube](https://www.youtube.com/@tenten_ai)** - Video tutorials and insights
- **[Connect on LinkedIn](https://www.linkedin.com/company/tentenco)** - Professional updates and industry news
- **[Join us on Threads](https://www.threads.net/@tenten.co)** - Quick updates and discussions
- **[Follow on TikTok](https://www.tiktok.com/@tenten.ai)** - Short-form AI content
- **[Follow on X (Twitter)](https://x.com/tentencretaive)** - Real-time updates and insights
- **[Subscribe to our Newsletter](https://tenten.co/page/company/newsletter)** - Weekly AI insights delivered to your inbox
- **[Explore all our links](https://linktr.ee/tenten.co)** - One-stop access to all Tenten resources

---

*This awesome list is maintained by the community and curated by [Tenten.co](https://tenten.co/). Last updated: July 2025*

