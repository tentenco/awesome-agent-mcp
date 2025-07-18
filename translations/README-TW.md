# 🤖 Awesome Agent MCP

> 精選的 AI 代理和模型上下文協議 (MCP) 學習資源清單

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**創建者：** [Tenten.co - AI 優先產品代理商](https://tenten.co/)

## 📋 目錄

- [介紹](#介紹)
- [AI 代理](#ai-代理)
  - [框架與函式庫](#框架與函式庫)
  - [開源專案](#開源專案)
  - [商業平台](#商業平台)
  - [開發工具](#開發工具)
- [模型上下文協議 (MCP)](#模型上下文協議-mcp)
  - [官方資源](#官方資源)
  - [MCP 伺服器](#mcp-伺服器)
  - [MCP 客戶端](#mcp-客戶端)
  - [教學與指南](#教學與指南)
- [學習資源](#學習資源)
  - [文件](#文件)
  - [課程與教學](#課程與教學)
  - [書籍](#書籍)
  - [研究論文](#研究論文)
- [社群](#社群)
- [貢獻](#貢獻)
- [授權](#授權)

## 🚀 介紹

歡迎來到最全面的 AI 代理和模型上下文協議 (MCP) 學習資源集合。這個精選清單匯集了建構複雜 AI 代理系統和利用標準化上下文協議所需的基本工具、框架、教學和資源。

### 什麼是 AI 代理？

AI 代理是能夠感知環境、做出決策並採取行動以實現特定目標的自主軟體系統，無需持續的人工干預。這些智慧系統結合了大型語言模型 (LLM) 的力量與使用工具、存取外部資料來源和執行複雜多步驟工作流程的能力。

現代 AI 代理通常具有以下特徵：
- **自主決策**：分析情況並選擇適當行動的能力
- **工具整合**：與 API、資料庫和外部服務的無縫互動
- **記憶與上下文**：維護對話歷史並從過去的互動中學習
- **規劃與推理**：將複雜任務分解為可管理的步驟
- **多模態能力**：處理文字、圖像、音訊和其他資料類型

### 什麼是模型上下文協議 (MCP)？

模型上下文協議 (MCP) 是 Anthropic 於 2024 年 11 月推出的開放標準，革命性地改變了 AI 應用程式連接資料來源和工具的方式。將 MCP 視為「AI 應用程式的 USB-C」——它為 AI 模型存取外部資源提供了標準化、安全的方式。

MCP 的主要優勢包括：
- **標準化**：連接 AI 模型到各種資料來源的統一介面
- **安全性**：保護敏感資料的內建最佳實踐
- **靈活性**：輕鬆切換不同的 LLM 提供商和供應商
- **可擴展性**：不斷增長的預建整合生態系統
- **簡單性**：降低建構 AI 應用程式的複雜性

## 🤖 AI 代理

### 框架與函式庫

#### 多代理框架

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- 開發 LLM 應用程式的綜合框架
- 具有工具、記憶和代理能力的廣泛生態系統
- 支援多個 LLM 提供商和向量資料庫
- 豐富的文件和社群支援

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- 建構有狀態、多角色應用程式的圖形框架
- 建立在 LangChain 之上，具有增強的控制流程
- 適合複雜的代理工作流程和狀態管理
- 支援人機互動

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- 微軟的多代理對話系統框架
- 使多個代理能夠協作完成複雜任務
- 支援程式碼執行和對話代理
- 在自動程式碼生成和除錯方面表現出色

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- 基於角色的協作 AI 多代理框架
- 代理像團隊一樣協作，具有明確的角色和目標
- 內建任務委派和結果聚合
- 簡單而強大的代理編排 API

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- 微軟的 AI 編排框架
- 支援多種程式語言（C#、Python、Java）
- 基於外掛的架構，可擴展功能
- 具有強大安全功能的企業級解決方案

**[OpenAI Swarm](https://github.com/openai/swarm)** ⭐ 13k+
- 輕量級多代理編排框架
- 專注於代理交接和協調
- 最小依賴且易於理解
- OpenAI 的實驗性框架

#### 單代理框架

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- 建構具有記憶和知識的 AI 代理框架
- 內建對工具、儲存和向量資料庫的支援
- 與流行的 LLM 提供商輕鬆整合
- 專注於生產就緒的應用程式

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- 建立在 Pydantic 上的類型安全代理框架
- 適合重視類型安全的 Python 開發者
- 內建驗證的乾淨 API 設計
- 不斷增長的生態系統和社群

**[Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents)** ⭐ 1k+
- 建構可組合 AI 代理的模組化框架
- 專注於可重用元件和乾淨架構
- 支援各種 LLM 提供商和工具
- 適合建構可擴展的代理系統

### 開源專案

#### 通用代理

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- 首批自主 AI 代理之一
- 能夠將目標分解為子任務並執行
- 網頁瀏覽、檔案操作和程式碼執行能力
- 龐大的社群和外掛生態系統

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- 簡單但強大的任務驅動自主代理
- 使用 OpenAI 和向量資料庫進行任務管理
- 持續創建和執行任務以達成目標
- 易於理解和修改的極簡設計

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- 專門從事程式碼生成和軟體開發的 AI 代理
- 能夠從自然語言描述建構完整應用程式
- 具有人工回饋的迭代開發過程
- 支援多種程式語言和框架

**[MetaGPT](https://github.com/geekan/MetaGPT)** ⭐ 44k+
- 模擬軟體公司的多代理框架
- 代理扮演產品經理、架構師、工程師等角色
- 能夠生成包含文件的完整軟體專案
- 協作 AI 開發的創新方法

#### 專業代理

**[SWE-agent](https://github.com/princeton-nlp/SWE-agent)** ⭐ 13k+
- 專門解決 GitHub 問題的 AI 代理
- 能夠理解程式碼庫並實施修復
- 專為軟體工程任務設計
- 基於研究的程式碼理解方法

**[Aider](https://github.com/paul-gauthier/aider)** ⭐ 20k+
- 終端中的 AI 配對程式設計工具
- 與現有程式碼庫和 git 儲存庫協作
- 支援多個 LLM 提供商
- 在程式碼編輯和重構方面表現出色

**[Devon](https://github.com/entropy-research/Devon)** ⭐ 3k+
- 開源軟體工程代理
- 能夠自主處理複雜的軟體專案
- 與流行的開發工具整合
- 專注於真實世界的軟體開發任務

**[OpenDevin](https://github.com/OpenDevin/OpenDevin)** ⭐ 32k+
- 自主軟體工程師平台
- 能夠執行複雜的軟體開發任務
- 支援多種程式語言
- 活躍的開發和研究社群

### 商業平台

#### 企業解決方案

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- 建構自訂副駕駛的企業平台
- 與 Microsoft 365 和 Azure 服務整合
- 無程式碼/低程式碼開發環境
- 企業安全和合規功能

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- 客戶服務和銷售的 AI 代理平台
- 常見商業用例的預建代理
- 與 Salesforce CRM 和生態系統整合
- 自主客戶互動能力

**[Google Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder)**
- Google Cloud 建構 AI 代理的平台
- 與 Google 的 AI 模型和服務整合
- 企業級安全性和可擴展性
- 支援多模態代理體驗

#### 開發平台

**[Botpress](https://botpress.com/)**
- 開源對話 AI 平台
- 代理對話的視覺化流程建構器
- 廣泛的整合能力
- 雲端和本地部署選項

**[Rasa](https://rasa.com/)**
- 開源對話 AI 框架
- 先進的自然語言理解
- 可自訂的對話管理
- 強調資料隱私和控制

**[Voiceflow](https://www.voiceflow.com/)**
- 建構對話代理的視覺化平台
- 支援語音和聊天介面
- 協作設計環境
- 與流行的訊息平台整合

### 開發工具

#### 測試與除錯

**[AgentOps](https://github.com/AgentOps-AI/agentops)** ⭐ 2k+
- AI 代理的可觀察性平台
- 效能監控和除錯工具
- 成本追蹤和最佳化洞察
- 與流行代理框架整合

**[LangSmith](https://smith.langchain.com/)**
- LLM 應用程式開發平台
- 除錯、測試和監控能力
- 代理效能評估框架
- 開發團隊協作工具

**[Weights & Biases](https://wandb.ai/)**
- 具有代理實驗追蹤的 MLOps 平台
- 效能監控和視覺化
- 代理訓練的超參數最佳化
- 協作和分享能力

#### 部署與基礎設施

**[E2B](https://e2b.dev/)**
- AI 代理的雲端執行環境
- 安全的程式碼執行環境
- 代理部署和擴展的 API
- 與流行代理框架整合

**[Modal](https://modal.com/)**
- 執行 AI 工作負載的雲端平台
- 代理應用程式的無伺服器部署
- 密集 AI 任務的 GPU 支援
- 基於 Python 的簡單部署工作流程

**[Replicate](https://replicate.com/)**
- 執行機器學習模型的平台
- AI 代理和模型的簡易部署
- 數千個預訓練模型的 API 存取
- 生產使用的可擴展基礎設施

## 🔌 模型上下文協議 (MCP)

### 官方資源

**[模型上下文協議網站](https://modelcontextprotocol.io/)**
- 官方文件和規範
- 入門指南和教學
- 架構概述和最佳實踐
- 社群資源和範例

**[MCP GitHub 組織](https://github.com/modelcontextprotocol)**
- 官方 MCP 儲存庫和工具
- 參考實作和 SDK
- 社群貢獻和範例
- 問題追蹤和功能請求

**[Anthropic MCP 文件](https://docs.anthropic.com/en/docs/mcp)**
- Claude 特定的 MCP 整合指南
- API 文件和範例
- 安全最佳實踐
- 故障排除和支援

### MCP 伺服器

#### 資料庫與儲存

**[SQLite MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- 連接到 SQLite 資料庫
- 執行查詢和檢索資料
- 架構內省能力
- 內建安全性和驗證

**[PostgreSQL MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- 完整的 PostgreSQL 資料庫整合
- 先進的查詢能力
- 連接池和最佳化
- 企業級安全功能

**[MongoDB MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/mongodb)**
- NoSQL 資料庫連接
- 基於文件的資料操作
- 聚合管道支援
- 靈活的架構處理

**[Redis MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/redis)**
- 記憶體內資料結構儲存
- 快取和會話管理
- 發布/訂閱訊息能力
- 高效能資料操作

#### 檔案系統與雲端儲存

**[檔案系統 MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- 本地檔案系統存取
- 檔案讀取、寫入和操作
- 目錄遍歷和搜尋
- 安全的檔案操作

**[AWS S3 MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3 儲存桶整合
- 物件儲存和檢索
- 元資料管理
- 基於 IAM 的安全性

**[Google Drive MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)**
- Google Drive 檔案存取
- 文件協作功能
- 分享和權限管理
- 即時同步

#### API 與網路服務

**[GitHub MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHub 儲存庫整合
- 問題和拉取請求管理
- 程式碼搜尋和分析
- 工作流程自動化

**[Slack MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slack 工作區整合
- 訊息發送和檢索
- 頻道和使用者管理
- 機器人和應用程式互動

**[Notion MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/notion)**
- Notion 工作區連接
- 頁面和資料庫操作
- 內容創建和編輯
- 團隊協作功能

**[Jira MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/jira)**
- Atlassian Jira 整合
- 問題追蹤和管理
- 專案和工作流程操作
- 報告和分析

#### 開發工具

**[Docker MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/docker)**
- Docker 容器管理
- 映像建構和部署
- 容器編排
- 開發環境設定

**[Kubernetes MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/kubernetes)**
- Kubernetes 叢集管理
- Pod 和服務操作
- 部署和擴展
- 資源監控

**[Git MCP 伺服器](https://github.com/modelcontextprotocol/servers/tree/main/src/git)**
- Git 儲存庫操作
- 版本控制管理
- 分支和合併操作
- 提交歷史分析

### MCP 客戶端

#### 桌面應用程式

**[Claude Desktop](https://claude.ai/download)**
- Anthropic 官方桌面客戶端
- 原生 MCP 伺服器整合
- 安全的本地資料存取
- 跨平台相容性

**[Continue](https://continue.dev/)**
- VS Code 和 JetBrains 擴充功能
- 開發的 MCP 伺服器支援
- 程式碼完成和協助
- 本地和雲端模型支援

#### 網路應用程式

**[Claude Web](https://claude.ai/)**
- 基於瀏覽器的 Claude 介面
- 有限的 MCP 伺服器支援
- 基於雲端的處理
- 協作功能

#### 行動應用程式

**[Claude Mobile](https://claude.ai/download)**
- iOS 和 Android 應用程式
- 基本 MCP 功能
- 與桌面同步
- 隨時隨地的 AI 協助

### 教學與指南

#### 入門

**[MCP 快速入門指南](https://modelcontextprotocol.io/quickstart)**
- 逐步設定說明
- 第一個 MCP 伺服器創建
- 基本客戶端整合
- 常見故障排除提示

**[建構您的第一個 MCP 伺服器](https://modelcontextprotocol.io/tutorials/first-server)**
- 伺服器開發演練
- TypeScript 和 Python 範例
- 測試和除錯技術
- 部署最佳實踐

#### 進階主題

**[MCP 安全最佳實踐](https://modelcontextprotocol.io/security)**
- 身份驗證和授權
- 資料加密和隱私
- 網路安全考量
- 合規和治理

**[擴展 MCP 應用程式](https://modelcontextprotocol.io/scaling)**
- 效能最佳化技術
- 負載平衡和叢集
- 監控和可觀察性
- 成本最佳化策略

#### 整合範例

**[MCP 與 LangChain](https://python.langchain.com/docs/integrations/tools/mcp)**
- LangChain MCP 整合指南
- 工具創建和使用
- 代理工作流程範例
- 最佳實踐和模式

**[MCP 與 AutoGen](https://microsoft.github.io/autogen/docs/topics/mcp)**
- AutoGen MCP 伺服器整合
- 多代理 MCP 工作流程
- 代理間資料共享
- 協作任務執行

## 📚 學習資源

### 文件

#### 官方文件

**[LangChain 文件](https://python.langchain.com/)**
- LangChain 框架的綜合指南
- API 參考和範例
- 整合教學和最佳實踐
- 社群貢獻和更新

**[AutoGen 文件](https://microsoft.github.io/autogen/)**
- 微軟 AutoGen 框架指南
- 多代理系統教學
- 程式碼範例和用例
- 研究論文和出版物

**[OpenAI API 文件](https://platform.openai.com/docs)**
- OpenAI API 參考和指南
- 函數呼叫和工具使用
- 代理開發最佳實踐
- 速率限制和最佳化提示

**[Anthropic Claude 文件](https://docs.anthropic.com/)**
- Claude API 和 MCP 整合
- 提示工程技術
- 安全和對齊指南
- 企業功能和能力

#### 社群文件

**[AI 代理開發指南](https://github.com/microsoft/AI-Agent-Development-Guide)**
- 微軟的綜合代理開發資源
- 架構模式和設計原則
- 實作範例和案例研究
- 測試和部署策略

**[Awesome LLM Agents](https://github.com/hyp1231/awesome-llm-agents)**
- LLM 代理資源的精選清單
- 研究論文和實作
- 工具和框架比較
- 社群討論和洞察

### 課程與教學

#### 線上課程

**[DeepLearning.AI - LangGraph 中的 AI 代理](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- 建構 AI 代理的實作課程
- LangGraph 框架深度探討
- 真實世界專案實作
- 業界領袖的專家指導

**[DeepLearning.AI - 使用 crewAI 的多 AI 代理系統](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- 多代理系統開發
- CrewAI 框架精通
- 協作代理工作流程
- 生產部署技術

**[DeepLearning.AI - MCP：建構豐富上下文的 AI 應用程式](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)**
- 模型上下文協議基礎
- 建構 MCP 伺服器和客戶端
- 與現有應用程式整合
- 安全和最佳實踐

**[Coursera - AI 代理開發專業化](https://www.coursera.org/specializations/ai-agent-development)**
- 大學級代理開發課程
- 理論基礎和實際應用
- 真實世界場景的頂點專案
- 業界認可的認證

#### YouTube 頻道與播放清單

**[AI Explained](https://www.youtube.com/@aiexplained-official)**
- AI 代理發展的定期更新
- 框架比較和評論
- 業界新聞和分析
- 技術深度探討和教學

**[LangChain Official](https://www.youtube.com/@LangChain)**
- 官方 LangChain 教學和更新
- 框架功能演示
- 社群展示和用例
- 開發者訪談和洞察

**[Microsoft Developer](https://www.youtube.com/@MicrosoftDeveloper)**
- AutoGen 和 Semantic Kernel 教學
- 企業 AI 開發實踐
- Azure AI 服務整合
- 開發者會議演講

#### 互動教學

**[LangChain Academy](https://academy.langchain.com/)**
- 互動編程練習
- 漸進式技能建構
- 即時回饋和協助
- 社群挑戰和競賽

**[Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)**
- 實用範例和配方
- MCP 整合模式
- Claude 最佳化技術
- 社群貢獻的解決方案

### 書籍

#### 技術書籍

**"使用 LangChain 建構 LLM 應用程式" by Valentina Alto**
- LangChain 開發的綜合指南
- 實用範例和用例
- 生產部署策略
- 效能最佳化技術

**"AI 代理：理論與實踐" by Stuart Russell**
- AI 代理的理論基礎
- 決策制定和規劃演算法
- 多代理系統和協調
- 倫理考量和安全

**"大型語言模型實作" by Jay Alammar & Maarten Grootendorst**
- 實用的 LLM 應用程式開發
- 代理架構和設計模式
- 工具整合和工作流程自動化
- 真實世界案例研究和範例

#### 商業與策略書籍

**"AI 代理革命" by Reid Hoffman**
- AI 代理的商業影響
- 策略實施框架
- 產業轉型場景
- 未來趨勢和預測

**"自主智慧" by Andrew McAfee**
- AI 代理的經濟影響
- 組織變革管理
- 競爭優勢策略
- 風險評估和緩解

### 研究論文

#### 基礎論文

**[ReAct：在語言模型中協同推理和行動](https://arxiv.org/abs/2210.03629)**
- 推理和行動的基礎論文
- 使用工具的語言模型框架
- 實驗結果和分析
- 實作指南和範例

**[Toolformer：語言模型可以自學使用工具](https://arxiv.org/abs/2302.04761)**
- 自監督工具學習方法
- API 整合和使用模式
- 效能評估和基準
- 未來研究方向

**[AutoGPT：自主 GPT-4 實驗](https://arxiv.org/abs/2306.02224)**
- 早期自主代理實作
- 任務分解和執行策略
- 限制和改進機會
- 社群影響和採用

#### 最新進展

**[大型語言模型中的多代理協作](https://arxiv.org/abs/2310.02124)**
- 先進的多代理協調技術
- 通訊協議和策略
- 效能最佳化方法
- 可擴展性考量

**[基礎模型的工具學習](https://arxiv.org/abs/2304.08354)**
- 使用工具的 AI 綜合調查
- 工具和能力的分類
- 評估框架和指標
- 未來研究挑戰

**[模型上下文協議：標準化 AI-資料整合](https://arxiv.org/abs/2311.15432)**
- MCP 規範和設計原則
- 安全和隱私考量
- 效能基準和分析
- 生態系統發展策略

#### 調查論文

**[基於大型語言模型的自主代理調查](https://arxiv.org/abs/2308.11432)**
- 代理架構的綜合概述
- 能力分析和比較
- 應用領域和用例
- 研究差距和機會

**[大型語言模型時代的工具學習](https://arxiv.org/abs/2307.16789)**
- 使用工具的 AI 系統演進
- 現狀和未來方向
- 挑戰和限制
- 基準資料集和評估

### 會議與活動

#### 主要會議

**[NeurIPS（神經資訊處理系統）](https://neurips.cc/)**
- 頂級 AI 研究會議
- 代理相關工作坊和論文
- 網路和協作機會
- 業界和學術演講

**[ICML（國際機器學習會議）](https://icml.cc/)**
- 領先的機器學習會議
- 多代理系統軌道
- 工具學習和推理會議
- 海報會議和演示

**[AAMAS（自主代理和多代理系統）](https://www.aamas-conference.org/)**
- 專業代理系統會議
- 最新研究和發展
- 業界應用和案例研究
- 工作坊和教學

#### 業界活動

**[AI 代理峰會](https://aiagentsummit.com/)**
- 專注於業界的代理開發活動
- 供應商演講和演示
- 用例研究和實作
- 網路和合作機會

**[LangChain 會議](https://www.langchain.com/conference)**
- 框架特定的開發活動
- 社群展示和演講
- 技術工作坊和培訓
- 產品公告和更新

### 播客

**[AI 代理播客](https://aiagentpodcast.com/)**
- 每週代理開發討論
- 業界專家訪談
- 框架評論和比較
- 社群新聞和更新

**[實用 AI](https://changelog.com/practicalai)**
- 實用 AI 開發洞察
- 代理實作策略
- 工具評論和建議
- 開發者成功故事

**[LangChain 播客](https://www.langchain.com/podcast)**
- 框架特定討論
- 開發者訪談和洞察
- 用例研究和範例
- 社群亮點和特色

## 🌟 社群

### 論壇與討論平台

**[LangChain Discord](https://discord.gg/langchain)**
- 活躍的 LangChain 開發者社群
- 即時幫助和支援
- 框架更新和公告
- 專案展示和協作

**[AutoGen Discord](https://discord.gg/autogen)**
- 微軟 AutoGen 社群中心
- 多代理開發討論
- 研究協作機會
- 技術支援和故障排除

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- 社群討論和新聞
- 專案分享和回饋
- 教學推薦
- 業界洞察和趨勢

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- 一般 AI 代理開發社群
- 框架比較和評論
- 用例討論和範例
- 職涯建議和機會

### GitHub 社群

**[Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents)**
- AI 代理專案的綜合清單
- 社群貢獻和更新
- 專案發現和探索
- 協作機會

**[LangChain 社群](https://github.com/langchain-ai/langchain/discussions)**
- 官方 LangChain 討論
- 功能請求和回饋
- 社群驅動的改進
- 開發者支援和指導

### 專業網路

**[AI 代理開發者 LinkedIn 群組](https://www.linkedin.com/groups/ai-agent-developers/)**
- 專業網路和機會
- 業界新聞和洞察
- 職位發布和職涯發展
- 專家討論和分析

**[模型上下文協議 LinkedIn 群組](https://www.linkedin.com/groups/model-context-protocol/)**
- 專注於 MCP 的專業社群
- 實作討論和最佳實踐
- 商業用例和成功故事
- 合作和協作機會

## 🤝 貢獻

我們歡迎對這個精選清單的貢獻！請在提交拉取請求之前閱讀我們的[貢獻指南](CONTRIBUTING.md)。

### 如何貢獻

1. **分叉儲存庫**並創建新分支
2. **在適當的類別中添加您的資源**
3. **遵循現有條目使用的格式**
4. **確保資源是高品質且相關的**
5. **提交拉取請求**並提供清晰的描述

### 貢獻指南

- 資源應該是積極維護且有良好文件的
- 商業產品應該為社群提供明確價值
- 包含準確的描述和相關連結
- 在類別內保持字母順序
- 使用適當的 markdown 格式

## 📄 授權

本作品採用[創用 CC 姓名標示-非商業性-相同方式分享 4.0 國際授權條款](https://creativecommons.org/licenses/by-nc-sa/4.0/)授權。

---

## 🚀 透過 AI 自動化轉型您的業務

準備好為您的業務利用 AI 代理和 MCP 的力量了嗎？**[Tenten](https://tenten.co)** 是您值得信賴的 AI 優先產品代理商，專精於尖端 AI 自動化諮詢和實施。我們的專家團隊幫助企業整合複雜的 AI 代理系統、實施模型上下文協議解決方案，並透過智慧自動化轉型營運。

無論您是希望簡化工作流程、增強客戶體驗，還是建構自訂的 AI 驅動應用程式，Tenten 都能提供推動真正商業價值的企業級解決方案。從策略和設計到開發和部署，我們引導您完成 AI 轉型旅程的每一步。

**[與我們的 AI 專家預約會議](https://tenten.co/contact)**，了解 AI 代理和 MCP 如何革命化您的業務營運。

### 🔗 探索更多 Tenten 資源

- **[開發者部落格](https://developer.tenten.co/)** - 技術洞察和教學
- **[Shopify 開發者部落格](https://shopify.tenten.co/)** - 電商 AI 解決方案
- **[Tenten AI 部落格](https://tenten.co/learning/)** - AI 業界洞察和趨勢
- **[GEO (AI SEO) by Tenten](https://geo.tenten.co/zh-tw)** - AI 驅動的 SEO 解決方案
- **[領先的 Webflow 代理商](https://tenten.co/solution/webflow-agency)** - 網頁開發專業知識
- **[Shopify Plus 代理商](https://tenten.co/solution/shopify)** - 電商平台解決方案
- **[Tenten AI - AI 轉型諮詢](https://tentenai.com/)** - 在 AI 時代重新定義業務

### 📱 與 Tenten 連結

- **[在 Instagram 上關注我們](https://instagram.com/tenten.co)** - 幕後花絮和更新
- **[訂閱我們的 YouTube](https://www.youtube.com/@tenten_ai)** - 影片教學和洞察
- **[在 LinkedIn 上連結](https://www.linkedin.com/company/tentenco)** - 專業更新和業界新聞
- **[在 Threads 上加入我們](https://www.threads.net/@tenten.co)** - 快速更新和討論
- **[在 TikTok 上關注](https://www.tiktok.com/@tenten.ai)** - 短影音 AI 內容
- **[在 X (Twitter) 上關注](https://x.com/tentencretaive)** - 即時更新和洞察
- **[訂閱我們的電子報](https://tenten.co/page/company/newsletter)** - 每週 AI 洞察直送您的信箱
- **[探索我們所有的連結](https://linktr.ee/tenten.co)** - 一站式存取所有 Tenten 資源

---

*這個精選清單由社群維護，並由 [Tenten.co](https://tenten.co/) 策劃。最後更新：2025 年 7 月*

