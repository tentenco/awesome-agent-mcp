# 🤖 Awesome Agent MCP

> Una lista curada de recursos increíbles para dominar Agentes de IA y el Protocolo de Contexto de Modelo (MCP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Creado por:** [Tenten.co - La Agencia de Productos AI-First](https://tenten.co/)

## 📋 Tabla de Contenidos

- [Introducción](#introducción)
- [Agentes de IA](#agentes-de-ia)
- [Protocolo de Contexto de Modelo (MCP)](#protocolo-de-contexto-de-modelo-mcp)
- [Recursos de Aprendizaje](#recursos-de-aprendizaje)
- [Comunidad](#comunidad)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## 🚀 Introducción

Bienvenido a la colección más completa de recursos para dominar Agentes de IA y el Protocolo de Contexto de Modelo (MCP). Esta lista curada reúne las herramientas esenciales, frameworks, tutoriales y recursos que necesitas para construir sistemas sofisticados de agentes de IA y aprovechar el poder de los protocolos de contexto estandarizados.

### ¿Qué son los Agentes de IA?

Los agentes de IA son sistemas de software autónomos que pueden percibir su entorno, tomar decisiones y realizar acciones para lograr objetivos específicos sin intervención humana constante. Estos sistemas inteligentes combinan el poder de los Modelos de Lenguaje Grande (LLMs) con la capacidad de usar herramientas, acceder a fuentes de datos externas y ejecutar flujos de trabajo complejos de múltiples pasos.

### ¿Qué es el Protocolo de Contexto de Modelo (MCP)?

El Protocolo de Contexto de Modelo (MCP) es un estándar abierto introducido por Anthropic en noviembre de 2024 que revoluciona cómo las aplicaciones de IA se conectan a fuentes de datos y herramientas. Piensa en MCP como "USB-C para aplicaciones de IA": proporciona una forma estandarizada y segura para que los modelos de IA accedan a recursos externos.

## 🤖 Agentes de IA

### Frameworks y Librerías

#### Frameworks Multi-Agente

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- Framework integral para desarrollar aplicaciones LLM
- Ecosistema extenso con herramientas, memoria y capacidades de agentes
- Soporta múltiples proveedores de LLM y bases de datos vectoriales

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Framework basado en grafos para construir aplicaciones multi-actor con estado
- Construido sobre LangChain con flujo de control mejorado
- Perfecto para flujos de trabajo de agentes complejos y gestión de estado

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Framework de Microsoft para sistemas de conversación multi-agente
- Permite que múltiples agentes colaboren en tareas complejas
- Soporta tanto ejecución de código como agentes conversacionales

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- Framework multi-agente basado en roles para IA colaborativa
- Los agentes trabajan juntos como una tripulación con roles y objetivos definidos
- Delegación de tareas y agregación de resultados incorporadas

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Framework de orquestación de IA de Microsoft
- Soporta múltiples lenguajes de programación (C#, Python, Java)
- Arquitectura basada en plugins para extender capacidades

#### Frameworks de Agente Único

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Framework para construir agentes de IA con memoria y conocimiento
- Soporte incorporado para herramientas, almacenamiento y bases de datos vectoriales
- Integración fácil con proveedores populares de LLM

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Framework de agentes type-safe construido sobre Pydantic
- Excelente para desarrolladores de Python que valoran la seguridad de tipos
- Diseño de API limpio con validación incorporada

### Proyectos de Código Abierto

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- Uno de los primeros agentes de IA autónomos
- Puede descomponer objetivos en sub-tareas y ejecutarlas
- Capacidades de navegación web, operaciones de archivos y ejecución de código

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Agente autónomo simple pero poderoso impulsado por tareas
- Usa OpenAI y bases de datos vectoriales para gestión de tareas
- Crea y ejecuta tareas continuamente para alcanzar objetivos

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- Agente de IA especializado en generación de código y desarrollo de software
- Puede construir aplicaciones completas a partir de descripciones en lenguaje natural
- Proceso de desarrollo iterativo con retroalimentación humana

### Plataformas Comerciales

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Plataforma empresarial para construir copilotos personalizados
- Integración con servicios de Microsoft 365 y Azure
- Entorno de desarrollo sin código/bajo código

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- Plataforma de agentes de IA para servicio al cliente y ventas
- Agentes pre-construidos para casos de uso empresariales comunes
- Integración con CRM de Salesforce y ecosistema

## 🔌 Protocolo de Contexto de Modelo (MCP)

### Recursos Oficiales

**[Sitio Web del Protocolo de Contexto de Modelo](https://modelcontextprotocol.io/)**
- Documentación oficial y especificación
- Guías de inicio y tutoriales
- Visión general de arquitectura y mejores prácticas

**[Organización GitHub de MCP](https://github.com/modelcontextprotocol)**
- Repositorios y herramientas oficiales de MCP
- Implementaciones de referencia y SDKs
- Contribuciones de la comunidad y ejemplos

### Servidores MCP

#### Bases de Datos y Almacenamiento

**[Servidor MCP SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- Conectar a bases de datos SQLite
- Ejecutar consultas y recuperar datos
- Capacidades de introspección de esquemas

**[Servidor MCP PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Integración completa de base de datos PostgreSQL
- Capacidades de consulta avanzadas
- Pooling de conexiones y optimización

#### Sistemas de Archivos y Almacenamiento en la Nube

**[Servidor MCP de Sistema de Archivos](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Acceso al sistema de archivos local
- Lectura, escritura y manipulación de archivos
- Recorrido de directorios y búsqueda

**[Servidor MCP AWS S3](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Integración de bucket de Amazon S3
- Almacenamiento y recuperación de objetos
- Gestión de metadatos

#### APIs y Servicios Web

**[Servidor MCP GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- Integración de repositorio GitHub
- Gestión de issues y pull requests
- Búsqueda y análisis de código

**[Servidor MCP Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Integración de workspace de Slack
- Envío y recuperación de mensajes
- Gestión de canales y usuarios

### Clientes MCP

**[Claude Desktop](https://claude.ai/download)**
- Cliente de escritorio oficial de Anthropic
- Integración nativa de servidor MCP
- Acceso seguro a datos locales

**[Continue](https://continue.dev/)**
- Extensión de VS Code y JetBrains
- Soporte de servidor MCP para desarrollo
- Completado de código y asistencia

## 📚 Recursos de Aprendizaje

### Documentación

**[Documentación de LangChain](https://python.langchain.com/)**
- Guía completa para el framework LangChain
- Referencia de API y ejemplos
- Tutoriales de integración y mejores prácticas

**[Documentación de AutoGen](https://microsoft.github.io/autogen/)**
- Guía del framework AutoGen de Microsoft
- Tutoriales de sistemas multi-agente
- Ejemplos de código y casos de uso

### Cursos y Tutoriales

**[DeepLearning.AI - Agentes de IA en LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- Curso práctico para construir agentes de IA
- Inmersión profunda en el framework LangGraph
- Implementación de proyectos del mundo real

**[DeepLearning.AI - Sistemas Multi-Agente de IA con crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Desarrollo de sistemas multi-agente
- Dominio del framework CrewAI
- Flujos de trabajo de agentes colaborativos

### Libros

**"Construyendo Apps LLM con LangChain" por Valentina Alto**
- Guía completa para el desarrollo con LangChain
- Ejemplos prácticos y casos de uso
- Estrategias de despliegue en producción

**"Agentes de IA: Teoría y Práctica" por Stuart Russell**
- Fundamentos teóricos de agentes de IA
- Algoritmos de toma de decisiones y planificación
- Sistemas multi-agente y coordinación

## 🌟 Comunidad

### Foros y Plataformas de Discusión

**[Discord de LangChain](https://discord.gg/langchain)**
- Comunidad activa de desarrolladores de LangChain
- Ayuda y soporte en tiempo real
- Actualizaciones del framework y anuncios

**[Discord de AutoGen](https://discord.gg/autogen)**
- Hub de la comunidad AutoGen de Microsoft
- Discusiones de desarrollo multi-agente
- Oportunidades de colaboración en investigación

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Discusiones de la comunidad y noticias
- Compartir proyectos y retroalimentación
- Recomendaciones de tutoriales

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- Comunidad general de desarrollo de agentes de IA
- Comparaciones y reseñas de frameworks
- Discusiones de casos de uso y ejemplos

## 🤝 Contribuir

¡Damos la bienvenida a contribuciones a esta lista increíble! Por favor lee nuestras [Pautas de Contribución](CONTRIBUTING.md) antes de enviar un pull request.

### Cómo Contribuir

1. **Hacer fork del repositorio** y crear una nueva rama
2. **Agregar tu recurso** en la categoría apropiada
3. **Seguir el formato** usado por las entradas existentes
4. **Asegurar que el recurso sea de alta calidad** y relevante
5. **Enviar un pull request** con una descripción clara

## 📄 Licencia

Este trabajo está licenciado bajo una [Licencia Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 🚀 Transforma Tu Negocio con Automatización de IA

¿Listo para aprovechar el poder de los agentes de IA y MCP para tu negocio? **[Tenten](https://tenten.co)** es tu agencia de productos AI-first de confianza, especializada en consultoría e implementación de automatización de IA de vanguardia. Nuestro equipo experto ayuda a las empresas a integrar sistemas sofisticados de agentes de IA, implementar soluciones de Protocolo de Contexto de Modelo y transformar operaciones a través de automatización inteligente.

**[Reserva una reunión con nuestros expertos en IA](https://tenten.co/contact)** para descubrir cómo los agentes de IA y MCP pueden revolucionar las operaciones de tu negocio.

### 🔗 Explora Más de Tenten

- **[Blog de Desarrolladores](https://developer.tenten.co/)** - Perspectivas técnicas y tutoriales
- **[Blog de Desarrolladores Shopify](https://shopify.tenten.co/)** - Soluciones de IA para e-commerce
- **[Blog de Tenten AI](https://tenten.co/learning/)** - Perspectivas y tendencias de la industria de IA
- **[GEO (AI SEO) por Tenten](https://geo.tenten.co/zh-tw)** - Soluciones SEO impulsadas por IA
- **[Agencia Webflow Líder](https://tenten.co/solution/webflow-agency)** - Experiencia en desarrollo web
- **[Agencia Shopify Plus](https://tenten.co/solution/shopify)** - Soluciones de plataforma e-commerce
- **[Tenten AI - Consultoría de Transformación de IA](https://tentenai.com/)** - Redefinir negocios en la era de la IA

### 📱 Conecta con Tenten

- **[Síguenos en Instagram](https://instagram.com/tenten.co)** - Detrás de escenas y actualizaciones
- **[Suscríbete a nuestro YouTube](https://www.youtube.com/@tenten_ai)** - Tutoriales en video y perspectivas
- **[Conéctate en LinkedIn](https://www.linkedin.com/company/tentenco)** - Actualizaciones profesionales y noticias de la industria
- **[Únete en Threads](https://www.threads.net/@tenten.co)** - Actualizaciones rápidas y discusiones
- **[Síguenos en TikTok](https://www.tiktok.com/@tenten.ai)** - Contenido de IA en formato corto
- **[Síguenos en X (Twitter)](https://x.com/tentencretaive)** - Actualizaciones en tiempo real y perspectivas
- **[Suscríbete a nuestro Newsletter](https://tenten.co/page/company/newsletter)** - Perspectivas semanales de IA en tu bandeja de entrada
- **[Explora todos nuestros enlaces](https://linktr.ee/tenten.co)** - Acceso único a todos los recursos de Tenten

---

*Esta lista increíble es mantenida por la comunidad y curada por [Tenten.co](https://tenten.co/). Última actualización: Julio 2025*

