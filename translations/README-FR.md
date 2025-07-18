# 🤖 Awesome Agent MCP

> Une liste curatée de ressources exceptionnelles pour maîtriser les Agents IA et le Protocole de Contexte de Modèle (MCP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Créé par :** [Tenten.co - L'Agence Produit AI-First](https://tenten.co/)

## 📋 Table des Matières

- [Introduction](#introduction)
- [Agents IA](#agents-ia)
- [Protocole de Contexte de Modèle (MCP)](#protocole-de-contexte-de-modèle-mcp)
- [Ressources d'Apprentissage](#ressources-dapprentissage)
- [Communauté](#communauté)
- [Contribuer](#contribuer)
- [Licence](#licence)

## 🚀 Introduction

Bienvenue dans la collection la plus complète de ressources pour maîtriser les Agents IA et le Protocole de Contexte de Modèle (MCP). Cette liste curatée rassemble les outils essentiels, frameworks, tutoriels et ressources dont vous avez besoin pour construire des systèmes d'agents IA sophistiqués et exploiter la puissance des protocoles de contexte standardisés.

### Que sont les Agents IA ?

Les agents IA sont des systèmes logiciels autonomes qui peuvent percevoir leur environnement, prendre des décisions et effectuer des actions pour atteindre des objectifs spécifiques sans intervention humaine constante. Ces systèmes intelligents combinent la puissance des Grands Modèles de Langage (LLMs) avec la capacité d'utiliser des outils, d'accéder à des sources de données externes et d'exécuter des flux de travail complexes multi-étapes.

### Qu'est-ce que le Protocole de Contexte de Modèle (MCP) ?

Le Protocole de Contexte de Modèle (MCP) est un standard ouvert introduit par Anthropic en novembre 2024 qui révolutionne la façon dont les applications IA se connectent aux sources de données et aux outils. Pensez au MCP comme "l'USB-C pour les applications IA" - il fournit une méthode standardisée et sécurisée pour que les modèles IA accèdent aux ressources externes.

## 🤖 Agents IA

### Frameworks et Bibliothèques

#### Frameworks Multi-Agents

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- Framework complet pour développer des applications LLM
- Écosystème étendu avec outils, mémoire et capacités d'agents
- Supporte plusieurs fournisseurs LLM et bases de données vectorielles

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Framework basé sur des graphes pour construire des applications multi-acteurs avec état
- Construit sur LangChain avec un flux de contrôle amélioré
- Parfait pour les flux de travail d'agents complexes et la gestion d'état

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Framework de Microsoft pour les systèmes de conversation multi-agents
- Permet à plusieurs agents de collaborer sur des tâches complexes
- Supporte à la fois l'exécution de code et les agents conversationnels

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- Framework multi-agents basé sur les rôles pour l'IA collaborative
- Les agents travaillent ensemble comme une équipe avec des rôles et objectifs définis
- Délégation de tâches et agrégation de résultats intégrées

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Framework d'orchestration IA de Microsoft
- Supporte plusieurs langages de programmation (C#, Python, Java)
- Architecture basée sur des plugins pour étendre les capacités

#### Frameworks d'Agent Unique

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Framework pour construire des agents IA avec mémoire et connaissance
- Support intégré pour outils, stockage et bases de données vectorielles
- Intégration facile avec les fournisseurs LLM populaires

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Framework d'agents type-safe construit sur Pydantic
- Excellent pour les développeurs Python qui valorisent la sécurité des types
- Design d'API propre avec validation intégrée

### Projets Open Source

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- L'un des premiers agents IA autonomes
- Peut décomposer les objectifs en sous-tâches et les exécuter
- Capacités de navigation web, opérations de fichiers et exécution de code

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Agent autonome simple mais puissant piloté par les tâches
- Utilise OpenAI et des bases de données vectorielles pour la gestion des tâches
- Crée et exécute continuellement des tâches pour atteindre les objectifs

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- Agent IA spécialisé dans la génération de code et le développement logiciel
- Peut construire des applications complètes à partir de descriptions en langage naturel
- Processus de développement itératif avec retour humain

### Plateformes Commerciales

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Plateforme d'entreprise pour construire des copilotes personnalisés
- Intégration avec les services Microsoft 365 et Azure
- Environnement de développement no-code/low-code

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- Plateforme d'agents IA pour le service client et les ventes
- Agents pré-construits pour les cas d'usage business courants
- Intégration avec le CRM Salesforce et l'écosystème

## 🔌 Protocole de Contexte de Modèle (MCP)

### Ressources Officielles

**[Site Web du Protocole de Contexte de Modèle](https://modelcontextprotocol.io/)**
- Documentation officielle et spécification
- Guides de démarrage et tutoriels
- Aperçu de l'architecture et meilleures pratiques

**[Organisation GitHub MCP](https://github.com/modelcontextprotocol)**
- Dépôts et outils officiels MCP
- Implémentations de référence et SDKs
- Contributions communautaires et exemples

### Serveurs MCP

#### Bases de Données et Stockage

**[Serveur MCP SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- Connexion aux bases de données SQLite
- Exécution de requêtes et récupération de données
- Capacités d'introspection de schéma

**[Serveur MCP PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Intégration complète de base de données PostgreSQL
- Capacités de requête avancées
- Pooling de connexions et optimisation

#### Systèmes de Fichiers et Stockage Cloud

**[Serveur MCP Système de Fichiers](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Accès au système de fichiers local
- Lecture, écriture et manipulation de fichiers
- Parcours de répertoires et recherche

**[Serveur MCP AWS S3](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Intégration de bucket Amazon S3
- Stockage et récupération d'objets
- Gestion des métadonnées

#### APIs et Services Web

**[Serveur MCP GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- Intégration de dépôt GitHub
- Gestion des issues et pull requests
- Recherche et analyse de code

**[Serveur MCP Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Intégration d'espace de travail Slack
- Envoi et récupération de messages
- Gestion des canaux et utilisateurs

### Clients MCP

**[Claude Desktop](https://claude.ai/download)**
- Client desktop officiel d'Anthropic
- Intégration native de serveur MCP
- Accès sécurisé aux données locales

**[Continue](https://continue.dev/)**
- Extension VS Code et JetBrains
- Support de serveur MCP pour le développement
- Complétion de code et assistance

## 📚 Ressources d'Apprentissage

### Documentation

**[Documentation LangChain](https://python.langchain.com/)**
- Guide complet pour le framework LangChain
- Référence API et exemples
- Tutoriels d'intégration et meilleures pratiques

**[Documentation AutoGen](https://microsoft.github.io/autogen/)**
- Guide du framework AutoGen de Microsoft
- Tutoriels de systèmes multi-agents
- Exemples de code et cas d'usage

### Cours et Tutoriels

**[DeepLearning.AI - Agents IA dans LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- Cours pratique pour construire des agents IA
- Plongée profonde dans le framework LangGraph
- Implémentation de projets du monde réel

**[DeepLearning.AI - Systèmes Multi-Agents IA avec crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Développement de systèmes multi-agents
- Maîtrise du framework CrewAI
- Flux de travail d'agents collaboratifs

### Livres

**"Construire des Apps LLM avec LangChain" par Valentina Alto**
- Guide complet pour le développement LangChain
- Exemples pratiques et cas d'usage
- Stratégies de déploiement en production

**"Agents IA : Théorie et Pratique" par Stuart Russell**
- Fondements théoriques des agents IA
- Algorithmes de prise de décision et de planification
- Systèmes multi-agents et coordination

## 🌟 Communauté

### Forums et Plateformes de Discussion

**[Discord LangChain](https://discord.gg/langchain)**
- Communauté active de développeurs LangChain
- Aide et support en temps réel
- Mises à jour du framework et annonces

**[Discord AutoGen](https://discord.gg/autogen)**
- Hub communautaire AutoGen de Microsoft
- Discussions de développement multi-agents
- Opportunités de collaboration de recherche

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Discussions communautaires et actualités
- Partage de projets et retours
- Recommandations de tutoriels

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- Communauté générale de développement d'agents IA
- Comparaisons et critiques de frameworks
- Discussions de cas d'usage et exemples

## 🤝 Contribuer

Nous accueillons les contributions à cette liste géniale ! Veuillez lire nos [Directives de Contribution](CONTRIBUTING.md) avant de soumettre une pull request.

### Comment Contribuer

1. **Forker le dépôt** et créer une nouvelle branche
2. **Ajouter votre ressource** dans la catégorie appropriée
3. **Suivre le format** utilisé par les entrées existantes
4. **S'assurer que la ressource est de haute qualité** et pertinente
5. **Soumettre une pull request** avec une description claire

## 📄 Licence

Ce travail est sous licence [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 🚀 Transformez Votre Entreprise avec l'Automatisation IA

Prêt à exploiter la puissance des agents IA et MCP pour votre entreprise ? **[Tenten](https://tenten.co)** est votre agence produit AI-first de confiance, spécialisée dans le conseil et l'implémentation d'automatisation IA de pointe. Notre équipe d'experts aide les entreprises à intégrer des systèmes d'agents IA sophistiqués, implémenter des solutions de Protocole de Contexte de Modèle et transformer les opérations grâce à l'automatisation intelligente.

**[Réservez une réunion avec nos experts IA](https://tenten.co/contact)** pour découvrir comment les agents IA et MCP peuvent révolutionner les opérations de votre entreprise.

### 🔗 Explorez Plus de Tenten

- **[Blog Développeurs](https://developer.tenten.co/)** - Insights techniques et tutoriels
- **[Blog Développeurs Shopify](https://shopify.tenten.co/)** - Solutions IA e-commerce
- **[Blog Tenten AI](https://tenten.co/learning/)** - Insights et tendances de l'industrie IA
- **[GEO (AI SEO) par Tenten](https://geo.tenten.co/zh-tw)** - Solutions SEO alimentées par IA
- **[Agence Webflow Leader](https://tenten.co/solution/webflow-agency)** - Expertise en développement web
- **[Agence Shopify Plus](https://tenten.co/solution/shopify)** - Solutions de plateforme e-commerce
- **[Tenten AI - Conseil en Transformation IA](https://tentenai.com/)** - Redéfinir les entreprises à l'ère de l'IA

### 📱 Connectez-vous avec Tenten

- **[Suivez-nous sur Instagram](https://instagram.com/tenten.co)** - Coulisses et mises à jour
- **[Abonnez-vous à notre YouTube](https://www.youtube.com/@tenten_ai)** - Tutoriels vidéo et insights
- **[Connectez-vous sur LinkedIn](https://www.linkedin.com/company/tentenco)** - Mises à jour professionnelles et actualités de l'industrie
- **[Rejoignez-nous sur Threads](https://www.threads.net/@tenten.co)** - Mises à jour rapides et discussions
- **[Suivez sur TikTok](https://www.tiktok.com/@tenten.ai)** - Contenu IA format court
- **[Suivez sur X (Twitter)](https://x.com/tentencretaive)** - Mises à jour en temps réel et insights
- **[Abonnez-vous à notre Newsletter](https://tenten.co/page/company/newsletter)** - Insights IA hebdomadaires dans votre boîte mail
- **[Explorez tous nos liens](https://linktr.ee/tenten.co)** - Accès unique à toutes les ressources Tenten

---

*Cette liste géniale est maintenue par la communauté et curatée par [Tenten.co](https://tenten.co/). Dernière mise à jour : Juillet 2025*

