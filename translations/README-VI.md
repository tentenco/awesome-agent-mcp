# 🤖 Awesome Agent MCP

> Danh sách tuyển chọn các tài nguyên tuyệt vời để thành thạo AI Agents và Model Context Protocol (MCP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Được tạo bởi:** [Tenten.co - Công ty Sản phẩm AI-First](https://tenten.co/)

## 📋 Mục lục

- [Giới thiệu](#giới-thiệu)
- [AI Agents](#ai-agents)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [Tài nguyên học tập](#tài-nguyên-học-tập)
- [Cộng đồng](#cộng-đồng)
- [Đóng góp](#đóng-góp)
- [Giấy phép](#giấy-phép)

## 🚀 Giới thiệu

Chào mừng đến với bộ sưu tập tài nguyên toàn diện nhất để thành thạo AI Agents và Model Context Protocol (MCP). Danh sách tuyển chọn này tập hợp các công cụ thiết yếu, framework, hướng dẫn và tài nguyên bạn cần để xây dựng các hệ thống AI agent tinh vi và tận dụng sức mạnh của các giao thức ngữ cảnh được chuẩn hóa.

### AI Agents là gì?

AI Agents là các hệ thống phần mềm tự động có thể cảm nhận môi trường, đưa ra quyết định và thực hiện hành động để đạt được các mục tiêu cụ thể mà không cần sự can thiệp liên tục của con người. Các hệ thống thông minh này kết hợp sức mạnh của các Mô hình Ngôn ngữ Lớn (LLMs) với khả năng sử dụng công cụ, truy cập các nguồn dữ liệu bên ngoài và thực thi các quy trình làm việc phức tạp nhiều bước.

### Model Context Protocol (MCP) là gì?

Model Context Protocol (MCP) là một tiêu chuẩn mở được Anthropic giới thiệu vào tháng 11 năm 2024, cách mạng hóa cách các ứng dụng AI kết nối với các nguồn dữ liệu và công cụ. Hãy nghĩ về MCP như "USB-C cho các ứng dụng AI" - nó cung cấp một cách được chuẩn hóa và an toàn để các mô hình AI truy cập các tài nguyên bên ngoài.

## 🤖 AI Agents

### Frameworks và Thư viện

#### Multi-Agent Frameworks

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- Framework toàn diện để phát triển ứng dụng LLM
- Hệ sinh thái rộng lớn với công cụ, bộ nhớ và khả năng agent
- Hỗ trợ nhiều nhà cung cấp LLM và cơ sở dữ liệu vector

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Framework dựa trên đồ thị để xây dựng ứng dụng đa tác nhân có trạng thái
- Được xây dựng trên LangChain với luồng điều khiển nâng cao
- Hoàn hảo cho quy trình làm việc agent phức tạp và quản lý trạng thái

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Framework của Microsoft cho hệ thống hội thoại đa agent
- Cho phép nhiều agent cộng tác trong các tác vụ phức tạp
- Hỗ trợ cả thực thi mã và agent hội thoại

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- Framework đa agent dựa trên vai trò cho AI cộng tác
- Các agent làm việc cùng nhau như một đội với vai trò và mục tiêu được xác định
- Ủy quyền tác vụ và tổng hợp kết quả tích hợp sẵn

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Framework điều phối AI của Microsoft
- Hỗ trợ nhiều ngôn ngữ lập trình (C#, Python, Java)
- Kiến trúc dựa trên plugin để mở rộng khả năng

#### Single-Agent Frameworks

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Framework để xây dựng AI agents với bộ nhớ và kiến thức
- Hỗ trợ tích hợp sẵn cho công cụ, lưu trữ và cơ sở dữ liệu vector
- Tích hợp dễ dàng với các nhà cung cấp LLM phổ biến

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Framework agent an toàn kiểu được xây dựng trên Pydantic
- Tuyệt vời cho các nhà phát triển Python coi trọng an toàn kiểu
- Thiết kế API sạch với xác thực tích hợp sẵn

### Dự án Mã nguồn Mở

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- Một trong những AI agent tự động đầu tiên
- Có thể chia nhỏ mục tiêu thành các tác vụ con và thực thi chúng
- Khả năng duyệt web, thao tác tệp và thực thi mã

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Agent tự động đơn giản nhưng mạnh mẽ được điều khiển bởi tác vụ
- Sử dụng OpenAI và cơ sở dữ liệu vector để quản lý tác vụ
- Liên tục tạo và thực thi các tác vụ để đạt được mục tiêu

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- AI agent chuyên về tạo mã và phát triển phần mềm
- Có thể xây dựng ứng dụng hoàn chỉnh từ mô tả ngôn ngữ tự nhiên
- Quy trình phát triển lặp đi lặp lại với phản hồi của con người

### Nền tảng Thương mại

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Nền tảng doanh nghiệp để xây dựng copilot tùy chỉnh
- Tích hợp với các dịch vụ Microsoft 365 và Azure
- Môi trường phát triển không mã/ít mã

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- Nền tảng AI agent cho dịch vụ khách hàng và bán hàng
- Các agent được xây dựng sẵn cho các trường hợp sử dụng kinh doanh phổ biến
- Tích hợp với CRM Salesforce và hệ sinh thái

## 🔌 Model Context Protocol (MCP)

### Tài nguyên Chính thức

**[Trang web Model Context Protocol](https://modelcontextprotocol.io/)**
- Tài liệu chính thức và đặc tả
- Hướng dẫn bắt đầu và hướng dẫn
- Tổng quan kiến trúc và thực hành tốt nhất

**[Tổ chức GitHub MCP](https://github.com/modelcontextprotocol)**
- Kho lưu trữ và công cụ MCP chính thức
- Triển khai tham chiếu và SDK
- Đóng góp cộng đồng và ví dụ

### MCP Servers

#### Cơ sở dữ liệu & Lưu trữ

**[SQLite MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- Kết nối với cơ sở dữ liệu SQLite
- Thực thi truy vấn và truy xuất dữ liệu
- Khả năng nội quan schema

**[PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Tích hợp cơ sở dữ liệu PostgreSQL đầy đủ
- Khả năng truy vấn nâng cao
- Gộp kết nối và tối ưu hóa

#### Hệ thống Tệp & Lưu trữ Đám mây

**[Filesystem MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Truy cập hệ thống tệp cục bộ
- Đọc, ghi và thao tác tệp
- Duyệt thư mục và tìm kiếm

**[AWS S3 MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Tích hợp bucket Amazon S3
- Lưu trữ và truy xuất đối tượng
- Quản lý metadata

#### APIs & Dịch vụ Web

**[GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- Tích hợp kho lưu trữ GitHub
- Quản lý issue và pull request
- Tìm kiếm và phân tích mã

**[Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Tích hợp không gian làm việc Slack
- Gửi và nhận tin nhắn
- Quản lý kênh và người dùng

### MCP Clients

**[Claude Desktop](https://claude.ai/download)**
- Client desktop chính thức của Anthropic
- Tích hợp MCP server gốc
- Truy cập dữ liệu cục bộ an toàn

**[Continue](https://continue.dev/)**
- Tiện ích mở rộng VS Code và JetBrains
- Hỗ trợ MCP server cho phát triển
- Hoàn thành mã và hỗ trợ

## 📚 Tài nguyên Học tập

### Tài liệu

**[Tài liệu LangChain](https://python.langchain.com/)**
- Hướng dẫn toàn diện cho framework LangChain
- Tham chiếu API và ví dụ
- Hướng dẫn tích hợp và thực hành tốt nhất

**[Tài liệu AutoGen](https://microsoft.github.io/autogen/)**
- Hướng dẫn framework AutoGen của Microsoft
- Hướng dẫn hệ thống đa agent
- Ví dụ mã và trường hợp sử dụng

### Khóa học & Hướng dẫn

**[DeepLearning.AI - AI Agents trong LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- Khóa học thực hành để xây dựng AI agents
- Tìm hiểu sâu framework LangGraph
- Triển khai dự án thực tế

**[DeepLearning.AI - Hệ thống Multi AI Agent với crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Phát triển hệ thống đa agent
- Thành thạo framework CrewAI
- Quy trình làm việc agent cộng tác

### Sách

**"Xây dựng Ứng dụng LLM với LangChain" bởi Valentina Alto**
- Hướng dẫn toàn diện cho phát triển LangChain
- Ví dụ thực tế và trường hợp sử dụng
- Chiến lược triển khai sản xuất

**"AI Agents: Lý thuyết và Thực hành" bởi Stuart Russell**
- Nền tảng lý thuyết của AI agents
- Thuật toán ra quyết định và lập kế hoạch
- Hệ thống đa agent và phối hợp

## 🌟 Cộng đồng

### Diễn đàn & Nền tảng Thảo luận

**[LangChain Discord](https://discord.gg/langchain)**
- Cộng đồng nhà phát triển LangChain tích cực
- Trợ giúp và hỗ trợ thời gian thực
- Cập nhật framework và thông báo

**[AutoGen Discord](https://discord.gg/autogen)**
- Trung tâm cộng đồng AutoGen của Microsoft
- Thảo luận phát triển đa agent
- Cơ hội hợp tác nghiên cứu

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Thảo luận cộng đồng và tin tức
- Chia sẻ dự án và phản hồi
- Đề xuất hướng dẫn

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- Cộng đồng phát triển AI agent chung
- So sánh và đánh giá framework
- Thảo luận trường hợp sử dụng và ví dụ

## 🤝 Đóng góp

Chúng tôi hoan nghênh các đóng góp cho danh sách tuyệt vời này! Vui lòng đọc [Hướng dẫn Đóng góp](CONTRIBUTING.md) của chúng tôi trước khi gửi pull request.

### Cách Đóng góp

1. **Fork repository** và tạo nhánh mới
2. **Thêm tài nguyên của bạn** vào danh mục phù hợp
3. **Tuân theo định dạng** được sử dụng bởi các mục hiện có
4. **Đảm bảo tài nguyên chất lượng cao** và có liên quan
5. **Gửi pull request** với mô tả rõ ràng

## 📄 Giấy phép

Tác phẩm này được cấp phép theo [Giấy phép Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 🚀 Chuyển đổi Doanh nghiệp của Bạn với Tự động hóa AI

Sẵn sàng tận dụng sức mạnh của AI agents và MCP cho doanh nghiệp của bạn? **[Tenten](https://tenten.co)** là công ty sản phẩm AI-first đáng tin cậy của bạn, chuyên về tư vấn và triển khai tự động hóa AI tiên tiến. Đội ngũ chuyên gia của chúng tôi giúp các doanh nghiệp tích hợp hệ thống AI agent tinh vi, triển khai giải pháp Model Context Protocol và chuyển đổi hoạt động thông qua tự động hóa thông minh.

**[Đặt lịch họp với các chuyên gia AI của chúng tôi](https://tenten.co/contact)** để khám phá cách AI agents và MCP có thể cách mạng hóa hoạt động kinh doanh của bạn.

### 🔗 Khám phá Thêm từ Tenten

- **[Blog Nhà phát triển](https://developer.tenten.co/)** - Thông tin kỹ thuật và hướng dẫn
- **[Blog Nhà phát triển Shopify](https://shopify.tenten.co/)** - Giải pháp AI thương mại điện tử
- **[Blog Tenten AI](https://tenten.co/learning/)** - Thông tin và xu hướng ngành AI
- **[GEO (AI SEO) bởi Tenten](https://geo.tenten.co/zh-tw)** - Giải pháp SEO được hỗ trợ bởi AI
- **[Công ty Webflow Hàng đầu](https://tenten.co/solution/webflow-agency)** - Chuyên môn phát triển web
- **[Công ty Shopify Plus](https://tenten.co/solution/shopify)** - Giải pháp nền tảng thương mại điện tử
- **[Tenten AI - Tư vấn Chuyển đổi AI](https://tentenai.com/)** - Định nghĩa lại doanh nghiệp trong kỷ nguyên AI

### 📱 Kết nối với Tenten

- **[Theo dõi chúng tôi trên Instagram](https://instagram.com/tenten.co)** - Hậu trường và cập nhật
- **[Đăng ký YouTube của chúng tôi](https://www.youtube.com/@tenten_ai)** - Hướng dẫn video và thông tin
- **[Kết nối trên LinkedIn](https://www.linkedin.com/company/tentenco)** - Cập nhật chuyên nghiệp và tin tức ngành
- **[Tham gia trên Threads](https://www.threads.net/@tenten.co)** - Cập nhật nhanh và thảo luận
- **[Theo dõi trên TikTok](https://www.tiktok.com/@tenten.ai)** - Nội dung AI định dạng ngắn
- **[Theo dõi trên X (Twitter)](https://x.com/tentencretaive)** - Cập nhật thời gian thực và thông tin
- **[Đăng ký bản tin của chúng tôi](https://tenten.co/page/company/newsletter)** - Thông tin AI hàng tuần đến hộp thư của bạn
- **[Khám phá tất cả liên kết của chúng tôi](https://linktr.ee/tenten.co)** - Truy cập một điểm đến tất cả tài nguyên Tenten

---

*Danh sách tuyệt vời này được duy trì bởi cộng đồng và được tuyển chọn bởi [Tenten.co](https://tenten.co/). Cập nhật lần cuối: Tháng 7 năm 2025*

