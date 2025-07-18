# 🤖 Awesome Agent MCP

> AI 에이전트와 모델 컨텍스트 프로토콜(MCP) 마스터를 위한 엄선된 리소스 목록

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**제작자:** [Tenten.co - AI 우선 제품 에이전시](https://tenten.co/)

## 📋 목차

- [소개](#소개)
- [AI 에이전트](#ai-에이전트)
- [모델 컨텍스트 프로토콜 (MCP)](#모델-컨텍스트-프로토콜-mcp)
- [학습 리소스](#학습-리소스)
- [커뮤니티](#커뮤니티)
- [기여](#기여)
- [라이선스](#라이선스)

## 🚀 소개

AI 에이전트와 모델 컨텍스트 프로토콜(MCP) 마스터를 위한 가장 포괄적인 리소스 컬렉션에 오신 것을 환영합니다. 이 엄선된 목록은 정교한 AI 에이전트 시스템을 구축하고 표준화된 컨텍스트 프로토콜의 힘을 활용하는 데 필요한 필수 도구, 프레임워크, 튜토리얼 및 리소스를 모았습니다.

### AI 에이전트란?

AI 에이전트는 환경을 인식하고, 결정을 내리며, 특정 목표를 달성하기 위해 행동을 취할 수 있는 자율적인 소프트웨어 시스템입니다. 이러한 지능형 시스템은 대규모 언어 모델(LLM)의 힘과 도구 사용, 외부 데이터 소스 액세스, 복잡한 다단계 워크플로우 실행 능력을 결합합니다.

### 모델 컨텍스트 프로토콜(MCP)이란?

모델 컨텍스트 프로토콜(MCP)은 2024년 11월 Anthropic에서 도입한 오픈 표준으로, AI 애플리케이션이 데이터 소스와 도구에 연결하는 방식을 혁신적으로 변화시켰습니다. MCP를 "AI 애플리케이션의 USB-C"로 생각하세요. AI 모델이 외부 리소스에 액세스할 수 있는 표준화되고 안전한 방법을 제공합니다.

## 🤖 AI 에이전트

### 프레임워크 & 라이브러리

#### 멀티 에이전트 프레임워크

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- LLM 애플리케이션 개발을 위한 포괄적인 프레임워크
- 도구, 메모리, 에이전트 기능을 갖춘 광범위한 생태계
- 여러 LLM 제공업체 및 벡터 데이터베이스 지원

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- 상태 저장 멀티 액터 애플리케이션 구축을 위한 그래프 기반 프레임워크
- LangChain 위에 구축되어 향상된 제어 흐름 제공
- 복잡한 에이전트 워크플로우와 상태 관리에 완벽

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Microsoft의 멀티 에이전트 대화 시스템 프레임워크
- 여러 에이전트가 복잡한 작업에서 협력할 수 있게 함
- 코드 실행 및 대화 에이전트 모두 지원

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- 협업 AI를 위한 역할 기반 멀티 에이전트 프레임워크
- 에이전트가 명확한 역할과 목표를 가진 크루처럼 협력
- 내장된 작업 위임 및 결과 집계

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Microsoft의 AI 오케스트레이션 프레임워크
- 여러 프로그래밍 언어 지원 (C#, Python, Java)
- 기능 확장을 위한 플러그인 기반 아키텍처

#### 단일 에이전트 프레임워크

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- 메모리와 지식을 갖춘 AI 에이전트 구축 프레임워크
- 도구, 스토리지, 벡터 데이터베이스에 대한 내장 지원
- 인기 있는 LLM 제공업체와의 쉬운 통합

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Pydantic 위에 구축된 타입 안전 에이전트 프레임워크
- 타입 안전성을 중시하는 Python 개발자에게 탁월
- 검증이 내장된 깔끔한 API 설계

### 오픈소스 프로젝트

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- 최초의 자율 AI 에이전트 중 하나
- 목표를 하위 작업으로 분해하고 실행 가능
- 웹 브라우징, 파일 작업, 코드 실행 기능

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- 간단하지만 강력한 작업 주도 자율 에이전트
- OpenAI와 벡터 데이터베이스를 사용한 작업 관리
- 목표 달성을 위해 지속적으로 작업 생성 및 실행

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- 코드 생성 및 소프트웨어 개발에 특화된 AI 에이전트
- 자연어 설명에서 완전한 애플리케이션 구축 가능
- 인간 피드백을 포함한 반복적 개발 프로세스

### 상용 플랫폼

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- 사용자 정의 코파일럿 구축을 위한 엔터프라이즈 플랫폼
- Microsoft 365 및 Azure 서비스와의 통합
- 노코드/로우코드 개발 환경

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- 고객 서비스 및 영업을 위한 AI 에이전트 플랫폼
- 일반적인 비즈니스 사용 사례를 위한 사전 구축 에이전트
- Salesforce CRM 및 생태계와의 통합

## 🔌 모델 컨텍스트 프로토콜 (MCP)

### 공식 리소스

**[모델 컨텍스트 프로토콜 웹사이트](https://modelcontextprotocol.io/)**
- 공식 문서 및 사양
- 시작 가이드 및 튜토리얼
- 아키텍처 개요 및 모범 사례

**[MCP GitHub 조직](https://github.com/modelcontextprotocol)**
- 공식 MCP 저장소 및 도구
- 참조 구현 및 SDK
- 커뮤니티 기여 및 예제

### MCP 서버

#### 데이터베이스 & 스토리지

**[SQLite MCP 서버](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- SQLite 데이터베이스 연결
- 쿼리 실행 및 데이터 검색
- 스키마 내성 기능

**[PostgreSQL MCP 서버](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- 완전한 PostgreSQL 데이터베이스 통합
- 고급 쿼리 기능
- 연결 풀링 및 최적화

#### 파일 시스템 & 클라우드 스토리지

**[파일시스템 MCP 서버](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- 로컬 파일 시스템 액세스
- 파일 읽기, 쓰기, 조작
- 디렉토리 탐색 및 검색

**[AWS S3 MCP 서버](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3 버킷 통합
- 객체 저장 및 검색
- 메타데이터 관리

#### API & 웹 서비스

**[GitHub MCP 서버](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHub 저장소 통합
- 이슈 및 풀 리퀘스트 관리
- 코드 검색 및 분석

**[Slack MCP 서버](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slack 워크스페이스 통합
- 메시지 전송 및 검색
- 채널 및 사용자 관리

### MCP 클라이언트

**[Claude Desktop](https://claude.ai/download)**
- Anthropic 공식 데스크톱 클라이언트
- 네이티브 MCP 서버 통합
- 안전한 로컬 데이터 액세스

**[Continue](https://continue.dev/)**
- VS Code 및 JetBrains 확장
- 개발용 MCP 서버 지원
- 코드 완성 및 지원

## 📚 학습 리소스

### 문서

**[LangChain 문서](https://python.langchain.com/)**
- LangChain 프레임워크의 포괄적인 가이드
- API 참조 및 예제
- 통합 튜토리얼 및 모범 사례

**[AutoGen 문서](https://microsoft.github.io/autogen/)**
- Microsoft AutoGen 프레임워크 가이드
- 멀티 에이전트 시스템 튜토리얼
- 코드 예제 및 사용 사례

### 코스 & 튜토리얼

**[DeepLearning.AI - LangGraph의 AI 에이전트](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- AI 에이전트 구축 실습 코스
- LangGraph 프레임워크 심화 학습
- 실제 프로젝트 구현

**[DeepLearning.AI - crewAI를 사용한 멀티 AI 에이전트 시스템](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- 멀티 에이전트 시스템 개발
- CrewAI 프레임워크 마스터리
- 협업 에이전트 워크플로우

### 도서

**"LangChain으로 LLM 앱 구축하기" by Valentina Alto**
- LangChain 개발의 포괄적인 가이드
- 실용적인 예제 및 사용 사례
- 프로덕션 배포 전략

**"AI 에이전트: 이론과 실제" by Stuart Russell**
- AI 에이전트의 이론적 기초
- 의사결정 및 계획 알고리즘
- 멀티 에이전트 시스템 및 조정

## 🌟 커뮤니티

### 포럼 & 토론 플랫폼

**[LangChain Discord](https://discord.gg/langchain)**
- 활발한 LangChain 개발자 커뮤니티
- 실시간 도움말 및 지원
- 프레임워크 업데이트 및 공지

**[AutoGen Discord](https://discord.gg/autogen)**
- Microsoft AutoGen 커뮤니티 허브
- 멀티 에이전트 개발 토론
- 연구 협력 기회

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- 커뮤니티 토론 및 뉴스
- 프로젝트 공유 및 피드백
- 튜토리얼 추천

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- 일반 AI 에이전트 개발 커뮤니티
- 프레임워크 비교 및 리뷰
- 사용 사례 토론 및 예제

## 🤝 기여

이 멋진 목록에 대한 기여를 환영합니다! 풀 리퀘스트를 제출하기 전에 [기여 가이드라인](CONTRIBUTING.md)을 읽어주세요.

### 기여 방법

1. **저장소를 포크**하고 새 브랜치 생성
2. **적절한 카테고리에 리소스 추가**
3. **기존 항목에서 사용된 형식 따르기**
4. **리소스가 고품질이고 관련성이 있는지 확인**
5. **명확한 설명과 함께 풀 리퀘스트 제출**

## 📄 라이선스

이 작품은 [크리에이티브 커먼즈 저작자표시-비영리-동일조건변경허락 4.0 국제 라이선스](https://creativecommons.org/licenses/by-nc-sa/4.0/) 하에 라이선스됩니다.

---

## 🚀 AI 자동화로 비즈니스 혁신

비즈니스에 AI 에이전트와 MCP의 힘을 활용할 준비가 되셨나요? **[Tenten](https://tenten.co)**은 최첨단 AI 자동화 컨설팅 및 구현을 전문으로 하는 신뢰할 수 있는 AI 우선 제품 에이전시입니다. 우리의 전문가 팀은 기업이 정교한 AI 에이전트 시스템을 통합하고, 모델 컨텍스트 프로토콜 솔루션을 구현하며, 지능형 자동화를 통해 운영을 혁신하도록 돕습니다.

워크플로우 간소화, 고객 경험 향상, 맞춤형 AI 기반 애플리케이션 구축 등 무엇을 원하든, Tenten은 진정한 비즈니스 가치를 창출하는 엔터프라이즈급 솔루션을 제공합니다. 전략과 설계부터 개발과 배포까지, AI 혁신 여정의 모든 단계를 안내합니다.

**[AI 전문가와 미팅 예약](https://tenten.co/contact)**하여 AI 에이전트와 MCP가 비즈니스 운영을 어떻게 혁신할 수 있는지 알아보세요.

### 🔗 Tenten의 더 많은 리소스 탐색

- **[개발자 블로그](https://developer.tenten.co/)** - 기술적 통찰과 튜토리얼
- **[Shopify 개발자 블로그](https://shopify.tenten.co/)** - 이커머스 AI 솔루션
- **[Tenten AI 블로그](https://tenten.co/learning/)** - AI 업계 통찰과 트렌드
- **[GEO (AI SEO) by Tenten](https://geo.tenten.co/zh-tw)** - AI 기반 SEO 솔루션
- **[선도적인 Webflow 에이전시](https://tenten.co/solution/webflow-agency)** - 웹 개발 전문성
- **[Shopify Plus 에이전시](https://tenten.co/solution/shopify)** - 이커머스 플랫폼 솔루션
- **[Tenten AI - AI 혁신 컨설팅](https://tentenai.com/)** - AI 시대의 비즈니스 재정의

### 📱 Tenten과 연결

- **[Instagram 팔로우](https://instagram.com/tenten.co)** - 비하인드 스토리와 업데이트
- **[YouTube 구독](https://www.youtube.com/@tenten_ai)** - 비디오 튜토리얼과 통찰
- **[LinkedIn 연결](https://www.linkedin.com/company/tentenco)** - 전문적 업데이트와 업계 뉴스
- **[Threads 참여](https://www.threads.net/@tenten.co)** - 빠른 업데이트와 토론
- **[TikTok 팔로우](https://www.tiktok.com/@tenten.ai)** - 짧은 형식의 AI 콘텐츠
- **[X (Twitter) 팔로우](https://x.com/tentencretaive)** - 실시간 업데이트와 통찰
- **[뉴스레터 구독](https://tenten.co/page/company/newsletter)** - 주간 AI 통찰을 받은편지함으로
- **[모든 링크 탐색](https://linktr.ee/tenten.co)** - 모든 Tenten 리소스에 원스톱 액세스

---

*이 멋진 목록은 커뮤니티에 의해 유지되고 [Tenten.co](https://tenten.co/)에 의해 큐레이션됩니다. 마지막 업데이트: 2025년 7월*

