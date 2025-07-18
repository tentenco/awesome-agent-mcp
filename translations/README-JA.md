# 🤖 Awesome Agent MCP

> AIエージェントとモデルコンテキストプロトコル（MCP）をマスターするための厳選されたリソース集

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**作成者：** [Tenten.co - AI ファーストプロダクトエージェンシー](https://tenten.co/)

## 📋 目次

- [はじめに](#はじめに)
- [AIエージェント](#aiエージェント)
- [モデルコンテキストプロトコル（MCP）](#モデルコンテキストプロトコルmcp)
- [学習リソース](#学習リソース)
- [コミュニティ](#コミュニティ)
- [貢献](#貢献)
- [ライセンス](#ライセンス)

## 🚀 はじめに

AIエージェントとモデルコンテキストプロトコル（MCP）をマスターするための最も包括的なリソースコレクションへようこそ。この厳選されたリストは、洗練されたAIエージェントシステムを構築し、標準化されたコンテキストプロトコルの力を活用するために必要な重要なツール、フレームワーク、チュートリアル、リソースをまとめています。

### AIエージェントとは？

AIエージェントは、環境を認識し、決定を下し、特定の目標を達成するために行動を取ることができる自律的なソフトウェアシステムです。これらのインテリジェントシステムは、大規模言語モデル（LLM）の力と、ツールの使用、外部データソースへのアクセス、複雑な多段階ワークフローの実行能力を組み合わせています。

### モデルコンテキストプロトコル（MCP）とは？

モデルコンテキストプロトコル（MCP）は、2024年11月にAnthropicによって導入されたオープンスタンダードで、AIアプリケーションがデータソースやツールに接続する方法を革命的に変えています。MCPを「AIアプリケーションのUSB-C」と考えてください。AIモデルが外部リソースにアクセスするための標準化された安全な方法を提供します。

## 🤖 AIエージェント

### フレームワーク＆ライブラリ

#### マルチエージェントフレームワーク

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- LLMアプリケーション開発のための包括的フレームワーク
- ツール、メモリ、エージェント機能を持つ広範なエコシステム
- 複数のLLMプロバイダーとベクターデータベースをサポート

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- ステートフルなマルチアクターアプリケーションを構築するためのグラフベースフレームワーク
- LangChain上に構築され、強化された制御フローを提供
- 複雑なエージェントワークフローと状態管理に最適

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Microsoftのマルチエージェント会話システムフレームワーク
- 複数のエージェントが複雑なタスクで協力することを可能にする
- コード実行と会話エージェントの両方をサポート

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- 協調AIのためのロールベースマルチエージェントフレームワーク
- エージェントが明確な役割と目標を持つクルーのように協力
- 内蔵のタスク委任と結果集約

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- MicrosoftのAIオーケストレーションフレームワーク
- 複数のプログラミング言語をサポート（C#、Python、Java）
- 機能を拡張するためのプラグインベースアーキテクチャ

#### シングルエージェントフレームワーク

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- メモリと知識を持つAIエージェントを構築するためのフレームワーク
- ツール、ストレージ、ベクターデータベースの内蔵サポート
- 人気のLLMプロバイダーとの簡単な統合

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Pydantic上に構築されたタイプセーフエージェントフレームワーク
- タイプセーフティを重視するPython開発者に最適
- 検証が組み込まれたクリーンなAPI設計

### オープンソースプロジェクト

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- 最初の自律AIエージェントの一つ
- 目標をサブタスクに分解して実行可能
- ウェブブラウジング、ファイル操作、コード実行機能

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- シンプルだが強力なタスク駆動型自律エージェント
- OpenAIとベクターデータベースを使用したタスク管理
- 目標達成のためにタスクを継続的に作成・実行

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- コード生成とソフトウェア開発に特化したAIエージェント
- 自然言語の説明から完全なアプリケーションを構築可能
- 人間のフィードバックを含む反復開発プロセス

### 商用プラットフォーム

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- カスタムコパイロットを構築するためのエンタープライズプラットフォーム
- Microsoft 365とAzureサービスとの統合
- ノーコード/ローコード開発環境

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- カスタマーサービスと営業のためのAIエージェントプラットフォーム
- 一般的なビジネスユースケース用の事前構築エージェント
- Salesforce CRMとエコシステムとの統合

## 🔌 モデルコンテキストプロトコル（MCP）

### 公式リソース

**[モデルコンテキストプロトコルウェブサイト](https://modelcontextprotocol.io/)**
- 公式ドキュメントと仕様
- 入門ガイドとチュートリアル
- アーキテクチャ概要とベストプラクティス

**[MCP GitHub組織](https://github.com/modelcontextprotocol)**
- 公式MCPリポジトリとツール
- リファレンス実装とSDK
- コミュニティ貢献と例

### MCPサーバー

#### データベース＆ストレージ

**[SQLite MCPサーバー](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- SQLiteデータベースへの接続
- クエリの実行とデータの取得
- スキーマ内省機能

**[PostgreSQL MCPサーバー](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- 完全なPostgreSQLデータベース統合
- 高度なクエリ機能
- 接続プールと最適化

#### ファイルシステム＆クラウドストレージ

**[ファイルシステムMCPサーバー](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- ローカルファイルシステムアクセス
- ファイルの読み取り、書き込み、操作
- ディレクトリトラバーサルと検索

**[AWS S3 MCPサーバー](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3バケット統合
- オブジェクトストレージと取得
- メタデータ管理

#### API＆ウェブサービス

**[GitHub MCPサーバー](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHubリポジトリ統合
- イシューとプルリクエスト管理
- コード検索と分析

**[Slack MCPサーバー](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slackワークスペース統合
- メッセージ送信と取得
- チャンネルとユーザー管理

### MCPクライアント

**[Claude Desktop](https://claude.ai/download)**
- Anthropic公式デスクトップクライアント
- ネイティブMCPサーバー統合
- 安全なローカルデータアクセス

**[Continue](https://continue.dev/)**
- VS CodeとJetBrains拡張機能
- 開発用MCPサーバーサポート
- コード補完とアシスタンス

## 📚 学習リソース

### ドキュメント

**[LangChainドキュメント](https://python.langchain.com/)**
- LangChainフレームワークの包括的ガイド
- APIリファレンスと例
- 統合チュートリアルとベストプラクティス

**[AutoGenドキュメント](https://microsoft.github.io/autogen/)**
- Microsoft AutoGenフレームワークガイド
- マルチエージェントシステムチュートリアル
- コード例とユースケース

### コース＆チュートリアル

**[DeepLearning.AI - LangGraphでのAIエージェント](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- AIエージェント構築のハンズオンコース
- LangGraphフレームワークの詳細
- 実世界プロジェクトの実装

**[DeepLearning.AI - crewAIでのマルチAIエージェントシステム](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- マルチエージェントシステム開発
- CrewAIフレームワークマスタリー
- 協調エージェントワークフロー

### 書籍

**"LangChainでLLMアプリを構築する" by Valentina Alto**
- LangChain開発の包括的ガイド
- 実用的な例とユースケース
- 本番デプロイメント戦略

**"AIエージェント：理論と実践" by Stuart Russell**
- AIエージェントの理論的基盤
- 意思決定と計画アルゴリズム
- マルチエージェントシステムと協調

## 🌟 コミュニティ

### フォーラム＆ディスカッションプラットフォーム

**[LangChain Discord](https://discord.gg/langchain)**
- アクティブなLangChain開発者コミュニティ
- リアルタイムヘルプとサポート
- フレームワークアップデートとアナウンス

**[AutoGen Discord](https://discord.gg/autogen)**
- Microsoft AutoGenコミュニティハブ
- マルチエージェント開発ディスカッション
- 研究協力の機会

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- コミュニティディスカッションとニュース
- プロジェクト共有とフィードバック
- チュートリアル推奨

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- 一般的なAIエージェント開発コミュニティ
- フレームワーク比較とレビュー
- ユースケースディスカッションと例

## 🤝 貢献

この素晴らしいリストへの貢献を歓迎します！プルリクエストを提出する前に、[貢献ガイドライン](CONTRIBUTING.md)をお読みください。

### 貢献方法

1. **リポジトリをフォーク**して新しいブランチを作成
2. **適切なカテゴリにリソースを追加**
3. **既存のエントリで使用されている形式に従う**
4. **リソースが高品質で関連性があることを確認**
5. **明確な説明でプルリクエストを提出**

## 📄 ライセンス

この作品は[クリエイティブ・コモンズ 表示-非営利-継承 4.0 国際ライセンス](https://creativecommons.org/licenses/by-nc-sa/4.0/)の下でライセンスされています。

---

## 🚀 AIオートメーションでビジネスを変革

AIエージェントとMCPの力をビジネスに活用する準備はできていますか？**[Tenten](https://tenten.co)** は、最先端のAIオートメーションコンサルティングと実装を専門とする、信頼できるAIファーストプロダクトエージェンシーです。私たちの専門チームは、企業が洗練されたAIエージェントシステムを統合し、モデルコンテキストプロトコルソリューションを実装し、インテリジェントオートメーションを通じて運営を変革することを支援します。

ワークフローの合理化、カスタマーエクスペリエンスの向上、カスタムAI駆動アプリケーションの構築など、Tentenは真のビジネス価値を推進するエンタープライズグレードのソリューションを提供します。戦略と設計から開発とデプロイメントまで、AIトランスフォーメーションジャーニーのあらゆるステップをガイドします。

**[AIエキスパートとのミーティングを予約](https://tenten.co/contact)**して、AIエージェントとMCPがビジネス運営をどのように革命化できるかを発見してください。

### 🔗 Tentenのその他のリソースを探索

- **[開発者ブログ](https://developer.tenten.co/)** - 技術的洞察とチュートリアル
- **[Shopify開発者ブログ](https://shopify.tenten.co/)** - eコマースAIソリューション
- **[Tenten AIブログ](https://tenten.co/learning/)** - AI業界の洞察とトレンド
- **[GEO (AI SEO) by Tenten](https://geo.tenten.co/zh-tw)** - AI駆動SEOソリューション
- **[リーディングWebflowエージェンシー](https://tenten.co/solution/webflow-agency)** - ウェブ開発の専門知識
- **[Shopify Plusエージェンシー](https://tenten.co/solution/shopify)** - eコマースプラットフォームソリューション
- **[Tenten AI - AIトランスフォーメーションコンサルタンシー](https://tentenai.com/)** - AI時代のビジネス再定義

### 📱 Tentenとつながる

- **[Instagramでフォロー](https://instagram.com/tenten.co)** - 舞台裏とアップデート
- **[YouTubeを購読](https://www.youtube.com/@tenten_ai)** - ビデオチュートリアルと洞察
- **[LinkedInで接続](https://www.linkedin.com/company/tentenco)** - プロフェッショナルアップデートと業界ニュース
- **[Threadsで参加](https://www.threads.net/@tenten.co)** - クイックアップデートとディスカッション
- **[TikTokでフォロー](https://www.tiktok.com/@tenten.ai)** - ショートフォームAIコンテンツ
- **[X (Twitter)でフォロー](https://x.com/tentencretaive)** - リアルタイムアップデートと洞察
- **[ニュースレターを購読](https://tenten.co/page/company/newsletter)** - 週刊AI洞察をメールボックスに配信
- **[すべてのリンクを探索](https://linktr.ee/tenten.co)** - すべてのTentenリソースへのワンストップアクセス

---

*この素晴らしいリストはコミュニティによって維持され、[Tenten.co](https://tenten.co/)によってキュレーションされています。最終更新：2025年7月*

