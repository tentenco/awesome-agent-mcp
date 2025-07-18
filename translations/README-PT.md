# 🤖 Awesome Agent MCP

> Uma lista curada de recursos incríveis para dominar Agentes de IA e Protocolo de Contexto de Modelo (MCP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Criado por:** [Tenten.co - A Agência de Produtos AI-First](https://tenten.co/)

## 📋 Índice

- [Introdução](#introdução)
- [Agentes de IA](#agentes-de-ia)
- [Protocolo de Contexto de Modelo (MCP)](#protocolo-de-contexto-de-modelo-mcp)
- [Recursos de Aprendizagem](#recursos-de-aprendizagem)
- [Comunidade](#comunidade)
- [Contribuir](#contribuir)
- [Licença](#licença)

## 🚀 Introdução

Bem-vindo à coleção mais abrangente de recursos para dominar Agentes de IA e o Protocolo de Contexto de Modelo (MCP). Esta lista curada reúne as ferramentas essenciais, frameworks, tutoriais e recursos que você precisa para construir sistemas sofisticados de agentes de IA e aproveitar o poder dos protocolos de contexto padronizados.

### O que são Agentes de IA?

Agentes de IA são sistemas de software autônomos que podem perceber seu ambiente, tomar decisões e realizar ações para alcançar objetivos específicos sem intervenção humana constante. Esses sistemas inteligentes combinam o poder dos Modelos de Linguagem Grande (LLMs) com a capacidade de usar ferramentas, acessar fontes de dados externas e executar fluxos de trabalho complexos de múltiplas etapas.

### O que é o Protocolo de Contexto de Modelo (MCP)?

O Protocolo de Contexto de Modelo (MCP) é um padrão aberto introduzido pela Anthropic em novembro de 2024 que revoluciona como aplicações de IA se conectam a fontes de dados e ferramentas. Pense no MCP como "USB-C para aplicações de IA" - ele fornece uma maneira padronizada e segura para modelos de IA acessarem recursos externos.

## 🤖 Agentes de IA

### Frameworks e Bibliotecas

#### Frameworks Multi-Agente

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- Framework abrangente para desenvolver aplicações LLM
- Ecossistema extenso com ferramentas, memória e capacidades de agentes
- Suporta múltiplos provedores de LLM e bancos de dados vetoriais

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Framework baseado em grafos para construir aplicações multi-ator com estado
- Construído sobre LangChain com fluxo de controle aprimorado
- Perfeito para fluxos de trabalho de agentes complexos e gerenciamento de estado

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Framework da Microsoft para sistemas de conversação multi-agente
- Permite que múltiplos agentes colaborem em tarefas complexas
- Suporta tanto execução de código quanto agentes conversacionais

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- Framework multi-agente baseado em papéis para IA colaborativa
- Agentes trabalham juntos como uma equipe com papéis e objetivos definidos
- Delegação de tarefas e agregação de resultados incorporadas

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Framework de orquestração de IA da Microsoft
- Suporta múltiplas linguagens de programação (C#, Python, Java)
- Arquitetura baseada em plugins para estender capacidades

#### Frameworks de Agente Único

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Framework para construir agentes de IA com memória e conhecimento
- Suporte integrado para ferramentas, armazenamento e bancos de dados vetoriais
- Integração fácil com provedores populares de LLM

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Framework de agentes type-safe construído sobre Pydantic
- Excelente para desenvolvedores Python que valorizam segurança de tipos
- Design de API limpo com validação incorporada

### Projetos Open Source

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- Um dos primeiros agentes de IA autônomos
- Pode quebrar objetivos em sub-tarefas e executá-las
- Capacidades de navegação web, operações de arquivo e execução de código

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Agente autônomo simples mas poderoso orientado por tarefas
- Usa OpenAI e bancos de dados vetoriais para gerenciamento de tarefas
- Cria e executa tarefas continuamente para alcançar objetivos

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- Agente de IA especializado em geração de código e desenvolvimento de software
- Pode construir aplicações completas a partir de descrições em linguagem natural
- Processo de desenvolvimento iterativo com feedback humano

### Plataformas Comerciais

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Plataforma empresarial para construir copilotos personalizados
- Integração com serviços Microsoft 365 e Azure
- Ambiente de desenvolvimento no-code/low-code

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- Plataforma de agentes de IA para atendimento ao cliente e vendas
- Agentes pré-construídos para casos de uso empresariais comuns
- Integração com CRM Salesforce e ecossistema

## 🔌 Protocolo de Contexto de Modelo (MCP)

### Recursos Oficiais

**[Site do Protocolo de Contexto de Modelo](https://modelcontextprotocol.io/)**
- Documentação oficial e especificação
- Guias de início e tutoriais
- Visão geral da arquitetura e melhores práticas

**[Organização GitHub MCP](https://github.com/modelcontextprotocol)**
- Repositórios e ferramentas oficiais MCP
- Implementações de referência e SDKs
- Contribuições da comunidade e exemplos

### Servidores MCP

#### Bancos de Dados e Armazenamento

**[Servidor MCP SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- Conectar a bancos de dados SQLite
- Executar consultas e recuperar dados
- Capacidades de introspecção de esquema

**[Servidor MCP PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Integração completa de banco de dados PostgreSQL
- Capacidades de consulta avançadas
- Pooling de conexões e otimização

#### Sistemas de Arquivos e Armazenamento em Nuvem

**[Servidor MCP Sistema de Arquivos](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Acesso ao sistema de arquivos local
- Leitura, escrita e manipulação de arquivos
- Travessia de diretórios e busca

**[Servidor MCP AWS S3](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Integração de bucket Amazon S3
- Armazenamento e recuperação de objetos
- Gerenciamento de metadados

#### APIs e Serviços Web

**[Servidor MCP GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- Integração de repositório GitHub
- Gerenciamento de issues e pull requests
- Busca e análise de código

**[Servidor MCP Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Integração de workspace Slack
- Envio e recuperação de mensagens
- Gerenciamento de canais e usuários

### Clientes MCP

**[Claude Desktop](https://claude.ai/download)**
- Cliente desktop oficial da Anthropic
- Integração nativa de servidor MCP
- Acesso seguro a dados locais

**[Continue](https://continue.dev/)**
- Extensão VS Code e JetBrains
- Suporte de servidor MCP para desenvolvimento
- Completação de código e assistência

## 📚 Recursos de Aprendizagem

### Documentação

**[Documentação LangChain](https://python.langchain.com/)**
- Guia abrangente para o framework LangChain
- Referência de API e exemplos
- Tutoriais de integração e melhores práticas

**[Documentação AutoGen](https://microsoft.github.io/autogen/)**
- Guia do framework AutoGen da Microsoft
- Tutoriais de sistemas multi-agente
- Exemplos de código e casos de uso

### Cursos e Tutoriais

**[DeepLearning.AI - Agentes de IA no LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- Curso prático para construir agentes de IA
- Mergulho profundo no framework LangGraph
- Implementação de projetos do mundo real

**[DeepLearning.AI - Sistemas Multi-Agente de IA com crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Desenvolvimento de sistemas multi-agente
- Domínio do framework CrewAI
- Fluxos de trabalho de agentes colaborativos

### Livros

**"Construindo Apps LLM com LangChain" por Valentina Alto**
- Guia abrangente para desenvolvimento LangChain
- Exemplos práticos e casos de uso
- Estratégias de implantação em produção

**"Agentes de IA: Teoria e Prática" por Stuart Russell**
- Fundamentos teóricos de agentes de IA
- Algoritmos de tomada de decisão e planejamento
- Sistemas multi-agente e coordenação

## 🌟 Comunidade

### Fóruns e Plataformas de Discussão

**[Discord LangChain](https://discord.gg/langchain)**
- Comunidade ativa de desenvolvedores LangChain
- Ajuda e suporte em tempo real
- Atualizações do framework e anúncios

**[Discord AutoGen](https://discord.gg/autogen)**
- Hub da comunidade AutoGen da Microsoft
- Discussões de desenvolvimento multi-agente
- Oportunidades de colaboração em pesquisa

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Discussões da comunidade e notícias
- Compartilhamento de projetos e feedback
- Recomendações de tutoriais

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- Comunidade geral de desenvolvimento de agentes de IA
- Comparações e avaliações de frameworks
- Discussões de casos de uso e exemplos

## 🤝 Contribuir

Damos as boas-vindas a contribuições para esta lista incrível! Por favor, leia nossas [Diretrizes de Contribuição](CONTRIBUTING.md) antes de enviar um pull request.

### Como Contribuir

1. **Fazer fork do repositório** e criar um novo branch
2. **Adicionar seu recurso** na categoria apropriada
3. **Seguir o formato** usado pelas entradas existentes
4. **Garantir que o recurso seja de alta qualidade** e relevante
5. **Enviar um pull request** com uma descrição clara

## 📄 Licença

Este trabalho está licenciado sob uma [Licença Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 🚀 Transforme Seu Negócio com Automação de IA

Pronto para aproveitar o poder dos agentes de IA e MCP para seu negócio? **[Tenten](https://tenten.co)** é sua agência de produtos AI-first confiável, especializada em consultoria e implementação de automação de IA de ponta. Nossa equipe de especialistas ajuda empresas a integrar sistemas sofisticados de agentes de IA, implementar soluções de Protocolo de Contexto de Modelo e transformar operações através de automação inteligente.

**[Agende uma reunião com nossos especialistas em IA](https://tenten.co/contact)** para descobrir como agentes de IA e MCP podem revolucionar as operações do seu negócio.

### 🔗 Explore Mais da Tenten

- **[Blog de Desenvolvedores](https://developer.tenten.co/)** - Insights técnicos e tutoriais
- **[Blog de Desenvolvedores Shopify](https://shopify.tenten.co/)** - Soluções de IA para e-commerce
- **[Blog Tenten AI](https://tenten.co/learning/)** - Insights e tendências da indústria de IA
- **[GEO (AI SEO) pela Tenten](https://geo.tenten.co/zh-tw)** - Soluções SEO alimentadas por IA
- **[Agência Webflow Líder](https://tenten.co/solution/webflow-agency)** - Expertise em desenvolvimento web
- **[Agência Shopify Plus](https://tenten.co/solution/shopify)** - Soluções de plataforma e-commerce
- **[Tenten AI - Consultoria de Transformação de IA](https://tentenai.com/)** - Redefinir negócios na era da IA

### 📱 Conecte-se com a Tenten

- **[Siga-nos no Instagram](https://instagram.com/tenten.co)** - Bastidores e atualizações
- **[Inscreva-se no nosso YouTube](https://www.youtube.com/@tenten_ai)** - Tutoriais em vídeo e insights
- **[Conecte-se no LinkedIn](https://www.linkedin.com/company/tentenco)** - Atualizações profissionais e notícias da indústria
- **[Junte-se no Threads](https://www.threads.net/@tenten.co)** - Atualizações rápidas e discussões
- **[Siga no TikTok](https://www.tiktok.com/@tenten.ai)** - Conteúdo de IA em formato curto
- **[Siga no X (Twitter)](https://x.com/tentencretaive)** - Atualizações em tempo real e insights
- **[Inscreva-se na nossa Newsletter](https://tenten.co/page/company/newsletter)** - Insights semanais de IA na sua caixa de entrada
- **[Explore todos os nossos links](https://linktr.ee/tenten.co)** - Acesso único a todos os recursos da Tenten

---

*Esta lista incrível é mantida pela comunidade e curada pela [Tenten.co](https://tenten.co/). Última atualização: Julho 2025*

