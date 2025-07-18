# 🤖 Awesome Agent MCP

> Eine kuratierte Liste großartiger Ressourcen zum Meistern von KI-Agenten und Model Context Protocol (MCP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Erstellt von:** [Tenten.co - Die KI-First Produktagentur](https://tenten.co/)

## 📋 Inhaltsverzeichnis

- [Einführung](#einführung)
- [KI-Agenten](#ki-agenten)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [Lernressourcen](#lernressourcen)
- [Community](#community)
- [Mitwirken](#mitwirken)
- [Lizenz](#lizenz)

## 🚀 Einführung

Willkommen zur umfassendsten Sammlung von Ressourcen zum Meistern von KI-Agenten und dem Model Context Protocol (MCP). Diese kuratierte Liste bringt die wesentlichen Tools, Frameworks, Tutorials und Ressourcen zusammen, die Sie benötigen, um ausgeklügelte KI-Agentensysteme zu erstellen und die Macht standardisierter Kontextprotokolle zu nutzen.

### Was sind KI-Agenten?

KI-Agenten sind autonome Softwaresysteme, die ihre Umgebung wahrnehmen, Entscheidungen treffen und Maßnahmen ergreifen können, um spezifische Ziele ohne ständige menschliche Intervention zu erreichen. Diese intelligenten Systeme kombinieren die Macht großer Sprachmodelle (LLMs) mit der Fähigkeit, Tools zu verwenden, auf externe Datenquellen zuzugreifen und komplexe mehrstufige Workflows auszuführen.

### Was ist das Model Context Protocol (MCP)?

Das Model Context Protocol (MCP) ist ein offener Standard, der im November 2024 von Anthropic eingeführt wurde und revolutioniert, wie KI-Anwendungen sich mit Datenquellen und Tools verbinden. Denken Sie an MCP wie "USB-C für KI-Anwendungen" - es bietet eine standardisierte, sichere Möglichkeit für KI-Modelle, auf externe Ressourcen zuzugreifen.

## 🤖 KI-Agenten

### Frameworks & Bibliotheken

#### Multi-Agent Frameworks

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- Umfassendes Framework für die Entwicklung von LLM-Anwendungen
- Umfangreiches Ökosystem mit Tools, Speicher und Agentenfähigkeiten
- Unterstützt mehrere LLM-Anbieter und Vektordatenbanken

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Graph-basiertes Framework für den Aufbau zustandsbehafteter Multi-Actor-Anwendungen
- Aufbauend auf LangChain mit verbessertem Kontrollfluss
- Perfekt für komplexe Agenten-Workflows und Zustandsverwaltung

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Microsofts Framework für Multi-Agent-Konversationssysteme
- Ermöglicht mehreren Agenten die Zusammenarbeit bei komplexen Aufgaben
- Unterstützt sowohl Code-Ausführung als auch Konversationsagenten

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- Rollenbasiertes Multi-Agent-Framework für kollaborative KI
- Agenten arbeiten wie eine Crew mit definierten Rollen und Zielen zusammen
- Eingebaute Aufgabendelegation und Ergebnisaggregation

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Microsofts KI-Orchestrierungs-Framework
- Unterstützt mehrere Programmiersprachen (C#, Python, Java)
- Plugin-basierte Architektur zur Erweiterung der Fähigkeiten

#### Single-Agent Frameworks

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Framework zum Aufbau von KI-Agenten mit Gedächtnis und Wissen
- Eingebaute Unterstützung für Tools, Speicher und Vektordatenbanken
- Einfache Integration mit beliebten LLM-Anbietern

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Typsicheres Agenten-Framework basierend auf Pydantic
- Ausgezeichnet für Python-Entwickler, die Typsicherheit schätzen
- Sauberes API-Design mit eingebauter Validierung

### Open-Source-Projekte

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- Einer der ersten autonomen KI-Agenten
- Kann Ziele in Unteraufgaben aufteilen und diese ausführen
- Web-Browsing, Dateioperationen und Code-Ausführungsfähigkeiten

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Einfacher aber mächtiger aufgabengesteuerter autonomer Agent
- Verwendet OpenAI und Vektordatenbanken für Aufgabenverwaltung
- Erstellt und führt kontinuierlich Aufgaben zur Zielerreichung aus

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- KI-Agent spezialisiert auf Code-Generierung und Softwareentwicklung
- Kann vollständige Anwendungen aus natürlichsprachlichen Beschreibungen erstellen
- Iterativer Entwicklungsprozess mit menschlichem Feedback

### Kommerzielle Plattformen

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Enterprise-Plattform zum Erstellen benutzerdefinierter Copilots
- Integration mit Microsoft 365 und Azure-Diensten
- No-Code/Low-Code-Entwicklungsumgebung

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- KI-Agenten-Plattform für Kundenservice und Vertrieb
- Vorgefertigte Agenten für häufige Geschäftsanwendungsfälle
- Integration mit Salesforce CRM und Ökosystem

## 🔌 Model Context Protocol (MCP)

### Offizielle Ressourcen

**[Model Context Protocol Website](https://modelcontextprotocol.io/)**
- Offizielle Dokumentation und Spezifikation
- Erste Schritte Anleitungen und Tutorials
- Architekturübersicht und bewährte Praktiken

**[MCP GitHub Organisation](https://github.com/modelcontextprotocol)**
- Offizielle MCP-Repositories und Tools
- Referenzimplementierungen und SDKs
- Community-Beiträge und Beispiele

### MCP-Server

#### Datenbanken & Speicher

**[SQLite MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- Verbindung zu SQLite-Datenbanken
- Abfragen ausführen und Daten abrufen
- Schema-Introspektionsfähigkeiten

**[PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Vollständige PostgreSQL-Datenbankintegration
- Erweiterte Abfragefähigkeiten
- Verbindungspooling und Optimierung

#### Dateisysteme & Cloud-Speicher

**[Dateisystem MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Lokaler Dateisystemzugriff
- Datei lesen, schreiben und manipulieren
- Verzeichnisdurchlauf und Suche

**[AWS S3 MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3 Bucket-Integration
- Objektspeicherung und -abruf
- Metadatenverwaltung

#### APIs & Webdienste

**[GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHub-Repository-Integration
- Issue- und Pull-Request-Verwaltung
- Code-Suche und -Analyse

**[Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slack-Workspace-Integration
- Nachrichten senden und abrufen
- Kanal- und Benutzerverwaltung

### MCP-Clients

**[Claude Desktop](https://claude.ai/download)**
- Anthropics offizieller Desktop-Client
- Native MCP-Server-Integration
- Sicherer lokaler Datenzugriff

**[Continue](https://continue.dev/)**
- VS Code und JetBrains Erweiterung
- MCP-Server-Unterstützung für Entwicklung
- Code-Vervollständigung und Unterstützung

## 📚 Lernressourcen

### Dokumentation

**[LangChain Dokumentation](https://python.langchain.com/)**
- Umfassender Leitfaden für das LangChain-Framework
- API-Referenz und Beispiele
- Integrations-Tutorials und bewährte Praktiken

**[AutoGen Dokumentation](https://microsoft.github.io/autogen/)**
- Microsoft AutoGen Framework-Leitfaden
- Multi-Agent-System-Tutorials
- Code-Beispiele und Anwendungsfälle

### Kurse & Tutorials

**[DeepLearning.AI - KI-Agenten in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- Praktischer Kurs zum Erstellen von KI-Agenten
- LangGraph Framework Vertiefung
- Implementierung realer Projekte

**[DeepLearning.AI - Multi-KI-Agentensysteme mit crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Multi-Agent-Systementwicklung
- CrewAI Framework Beherrschung
- Kollaborative Agenten-Workflows

### Bücher

**"LLM-Apps mit LangChain erstellen" von Valentina Alto**
- Umfassender Leitfaden zur LangChain-Entwicklung
- Praktische Beispiele und Anwendungsfälle
- Produktionsbereitstellungsstrategien

**"KI-Agenten: Theorie und Praxis" von Stuart Russell**
- Theoretische Grundlagen von KI-Agenten
- Entscheidungsfindungs- und Planungsalgorithmen
- Multi-Agent-Systeme und Koordination

## 🌟 Community

### Foren & Diskussionsplattformen

**[LangChain Discord](https://discord.gg/langchain)**
- Aktive LangChain-Entwicklergemeinschaft
- Echtzeithelfe und Unterstützung
- Framework-Updates und Ankündigungen

**[AutoGen Discord](https://discord.gg/autogen)**
- Microsoft AutoGen Community Hub
- Multi-Agent-Entwicklungsdiskussionen
- Forschungskooperationsmöglichkeiten

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Community-Diskussionen und Nachrichten
- Projektaustausch und Feedback
- Tutorial-Empfehlungen

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- Allgemeine KI-Agenten-Entwicklungsgemeinschaft
- Framework-Vergleiche und Bewertungen
- Anwendungsfall-Diskussionen und Beispiele

## 🤝 Mitwirken

Wir begrüßen Beiträge zu dieser großartigen Liste! Bitte lesen Sie unsere [Beitragsrichtlinien](CONTRIBUTING.md), bevor Sie einen Pull Request einreichen.

### Wie man beiträgt

1. **Repository forken** und neuen Branch erstellen
2. **Ressource in der entsprechenden Kategorie hinzufügen**
3. **Format der bestehenden Einträge befolgen**
4. **Sicherstellen, dass die Ressource hochwertig und relevant ist**
5. **Pull Request mit klarer Beschreibung einreichen**

## 📄 Lizenz

Dieses Werk ist unter einer [Creative Commons Namensnennung-Nicht-kommerziell-Weitergabe unter gleichen Bedingungen 4.0 International Lizenz](https://creativecommons.org/licenses/by-nc-sa/4.0/) lizenziert.

---

## 🚀 Transformieren Sie Ihr Unternehmen mit KI-Automatisierung

Bereit, die Macht von KI-Agenten und MCP für Ihr Unternehmen zu nutzen? **[Tenten](https://tenten.co)** ist Ihre vertrauenswürdige KI-First Produktagentur, spezialisiert auf modernste KI-Automatisierungsberatung und -implementierung. Unser Expertenteam hilft Unternehmen dabei, ausgeklügelte KI-Agentensysteme zu integrieren, Model Context Protocol-Lösungen zu implementieren und Abläufe durch intelligente Automatisierung zu transformieren.

**[Buchen Sie ein Meeting mit unseren KI-Experten](https://tenten.co/contact)**, um zu entdecken, wie KI-Agenten und MCP Ihre Geschäftsabläufe revolutionieren können.

### 🔗 Entdecken Sie mehr von Tenten

- **[Entwickler-Blog](https://developer.tenten.co/)** - Technische Einblicke und Tutorials
- **[Shopify Entwickler-Blog](https://shopify.tenten.co/)** - E-Commerce KI-Lösungen
- **[Tenten AI Blog](https://tenten.co/learning/)** - KI-Brancheneinblicke und Trends
- **[GEO (AI SEO) von Tenten](https://geo.tenten.co/zh-tw)** - KI-gestützte SEO-Lösungen
- **[Führende Webflow-Agentur](https://tenten.co/solution/webflow-agency)** - Webentwicklungsexpertise
- **[Shopify Plus Agentur](https://tenten.co/solution/shopify)** - E-Commerce-Plattformlösungen
- **[Tenten AI - KI-Transformationsberatung](https://tentenai.com/)** - Geschäft im KI-Zeitalter neu definieren

### 📱 Mit Tenten verbinden

- **[Folgen Sie uns auf Instagram](https://instagram.com/tenten.co)** - Hinter den Kulissen und Updates
- **[Abonnieren Sie unseren YouTube](https://www.youtube.com/@tenten_ai)** - Video-Tutorials und Einblicke
- **[Verbinden Sie sich auf LinkedIn](https://www.linkedin.com/company/tentenco)** - Professionelle Updates und Branchennachrichten
- **[Treten Sie uns auf Threads bei](https://www.threads.net/@tenten.co)** - Schnelle Updates und Diskussionen
- **[Folgen Sie auf TikTok](https://www.tiktok.com/@tenten.ai)** - Kurze KI-Inhalte
- **[Folgen Sie auf X (Twitter)](https://x.com/tentencretaive)** - Echtzeitaktualisierungen und Einblicke
- **[Abonnieren Sie unseren Newsletter](https://tenten.co/page/company/newsletter)** - Wöchentliche KI-Einblicke in Ihren Posteingang
- **[Erkunden Sie alle unsere Links](https://linktr.ee/tenten.co)** - One-Stop-Zugang zu allen Tenten-Ressourcen

---

*Diese großartige Liste wird von der Community gepflegt und von [Tenten.co](https://tenten.co/) kuratiert. Zuletzt aktualisiert: Juli 2025*

