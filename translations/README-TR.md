# 🤖 Awesome Agent MCP

> AI Ajanları ve Model Bağlam Protokolü (MCP) konusunda ustalaşmak için seçilmiş harika kaynaklar listesi

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Oluşturan:** [Tenten.co - AI-İlk Ürün Ajansı](https://tenten.co/)

## 📋 İçindekiler

- [Giriş](#giriş)
- [AI Ajanları](#ai-ajanları)
- [Model Bağlam Protokolü (MCP)](#model-bağlam-protokolü-mcp)
- [Öğrenme Kaynakları](#öğrenme-kaynakları)
- [Topluluk](#topluluk)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## 🚀 Giriş

AI Ajanları ve Model Bağlam Protokolü (MCP) konusunda ustalaşmak için en kapsamlı kaynak koleksiyonuna hoş geldiniz. Bu seçilmiş liste, sofistike AI ajan sistemleri oluşturmak ve standartlaştırılmış bağlam protokollerinin gücünden yararlanmak için ihtiyacınız olan temel araçları, çerçeveleri, öğreticileri ve kaynakları bir araya getiriyor.

### AI Ajanları Nedir?

AI ajanları, çevrelerini algılayabilen, kararlar alabilen ve sürekli insan müdahalesi olmadan belirli hedeflere ulaşmak için eylemler gerçekleştirebilen otonom yazılım sistemleridir. Bu akıllı sistemler, Büyük Dil Modellerinin (LLM'ler) gücünü araçları kullanma, harici veri kaynaklarına erişme ve karmaşık çok adımlı iş akışları yürütme yeteneği ile birleştirir.

### Model Bağlam Protokolü (MCP) Nedir?

Model Bağlam Protokolü (MCP), Anthropic tarafından Kasım 2024'te tanıtılan ve AI uygulamalarının veri kaynaklarına ve araçlara nasıl bağlandığını devrimleştiren açık bir standarttır. MCP'yi "AI uygulamaları için USB-C" olarak düşünün - AI modellerinin harici kaynaklara erişmesi için standartlaştırılmış, güvenli bir yol sağlar.

## 🤖 AI Ajanları

### Çerçeveler ve Kütüphaneler

#### Çoklu Ajan Çerçeveleri

**[LangChain](https://github.com/langchain-ai/langchain)** ⭐ 94k+
- LLM uygulamaları geliştirmek için kapsamlı çerçeve
- Araçlar, bellek ve ajan yetenekleri ile geniş ekosistem
- Birden fazla LLM sağlayıcısı ve vektör veritabanını destekler

**[LangGraph](https://github.com/langchain-ai/langgraph)** ⭐ 6k+
- Durumlu çok aktörlü uygulamalar oluşturmak için graf tabanlı çerçeve
- LangChain üzerine inşa edilmiş, gelişmiş kontrol akışı ile
- Karmaşık ajan iş akışları ve durum yönetimi için mükemmel

**[AutoGen](https://github.com/microsoft/autogen)** ⭐ 32k+
- Microsoft'un çoklu ajan konuşma sistemleri çerçevesi
- Birden fazla ajanın karmaşık görevlerde işbirliği yapmasını sağlar
- Hem kod yürütme hem de konuşma ajanlarını destekler

**[CrewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 20k+
- İşbirlikçi AI için rol tabanlı çoklu ajan çerçevesi
- Ajanlar tanımlanmış roller ve hedeflerle bir ekip gibi birlikte çalışır
- Yerleşik görev delegasyonu ve sonuç toplama

**[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 22k+
- Microsoft'un AI orkestrasyon çerçevesi
- Birden fazla programlama dilini destekler (C#, Python, Java)
- Yetenekleri genişletmek için eklenti tabanlı mimari

#### Tekli Ajan Çerçeveleri

**[Phidata](https://github.com/phidatahq/phidata)** ⭐ 12k+
- Bellek ve bilgi ile AI ajanları oluşturmak için çerçeve
- Araçlar, depolama ve vektör veritabanları için yerleşik destek
- Popüler LLM sağlayıcıları ile kolay entegrasyon

**[PydanticAI](https://github.com/pydantic/pydantic-ai)** ⭐ 8k+
- Pydantic üzerine inşa edilmiş tip güvenli ajan çerçevesi
- Tip güvenliğini değer veren Python geliştiricileri için mükemmel
- Yerleşik doğrulama ile temiz API tasarımı

### Açık Kaynak Projeler

**[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 167k+
- İlk otonom AI ajanlarından biri
- Hedefleri alt görevlere bölebilir ve bunları yürütebilir
- Web tarama, dosya işlemleri ve kod yürütme yetenekleri

**[BabyAGI](https://github.com/yoheinakajima/babyagi)** ⭐ 20k+
- Basit ama güçlü görev odaklı otonom ajan
- Görev yönetimi için OpenAI ve vektör veritabanlarını kullanır
- Hedeflere ulaşmak için sürekli görevler oluşturur ve yürütür

**[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 52k+
- Kod üretimi ve yazılım geliştirme konusunda uzmanlaşmış AI ajanı
- Doğal dil açıklamalarından tam uygulamalar oluşturabilir
- İnsan geri bildirimi ile yinelemeli geliştirme süreci

### Ticari Platformlar

**[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**
- Özel copilotlar oluşturmak için kurumsal platform
- Microsoft 365 ve Azure hizmetleri ile entegrasyon
- Kod yazmadan/az kod ile geliştirme ortamı

**[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**
- Müşteri hizmetleri ve satış için AI ajan platformu
- Yaygın iş kullanım durumları için önceden oluşturulmuş ajanlar
- Salesforce CRM ve ekosistemi ile entegrasyon

## 🔌 Model Bağlam Protokolü (MCP)

### Resmi Kaynaklar

**[Model Bağlam Protokolü Web Sitesi](https://modelcontextprotocol.io/)**
- Resmi dokümantasyon ve spesifikasyon
- Başlangıç kılavuzları ve öğreticiler
- Mimari genel bakış ve en iyi uygulamalar

**[MCP GitHub Organizasyonu](https://github.com/modelcontextprotocol)**
- Resmi MCP depoları ve araçları
- Referans uygulamaları ve SDK'lar
- Topluluk katkıları ve örnekler

### MCP Sunucuları

#### Veritabanları ve Depolama

**[SQLite MCP Sunucusu](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)**
- SQLite veritabanlarına bağlanma
- Sorguları yürütme ve veri alma
- Şema iç gözlem yetenekleri

**[PostgreSQL MCP Sunucusu](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)**
- Tam PostgreSQL veritabanı entegrasyonu
- Gelişmiş sorgu yetenekleri
- Bağlantı havuzlama ve optimizasyon

#### Dosya Sistemleri ve Bulut Depolama

**[Dosya Sistemi MCP Sunucusu](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)**
- Yerel dosya sistemi erişimi
- Dosya okuma, yazma ve manipülasyon
- Dizin gezinme ve arama

**[AWS S3 MCP Sunucusu](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-s3)**
- Amazon S3 bucket entegrasyonu
- Nesne depolama ve alma
- Meta veri yönetimi

#### API'ler ve Web Hizmetleri

**[GitHub MCP Sunucusu](https://github.com/modelcontextprotocol/servers/tree/main/src/github)**
- GitHub deposu entegrasyonu
- Issue ve pull request yönetimi
- Kod arama ve analiz

**[Slack MCP Sunucusu](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)**
- Slack çalışma alanı entegrasyonu
- Mesaj gönderme ve alma
- Kanal ve kullanıcı yönetimi

### MCP İstemcileri

**[Claude Desktop](https://claude.ai/download)**
- Anthropic'in resmi masaüstü istemcisi
- Yerel MCP sunucu entegrasyonu
- Güvenli yerel veri erişimi

**[Continue](https://continue.dev/)**
- VS Code ve JetBrains uzantısı
- Geliştirme için MCP sunucu desteği
- Kod tamamlama ve yardım

## 📚 Öğrenme Kaynakları

### Dokümantasyon

**[LangChain Dokümantasyonu](https://python.langchain.com/)**
- LangChain çerçevesi için kapsamlı kılavuz
- API referansı ve örnekler
- Entegrasyon öğreticileri ve en iyi uygulamalar

**[AutoGen Dokümantasyonu](https://microsoft.github.io/autogen/)**
- Microsoft AutoGen çerçeve kılavuzu
- Çoklu ajan sistem öğreticileri
- Kod örnekleri ve kullanım durumları

### Kurslar ve Öğreticiler

**[DeepLearning.AI - LangGraph'ta AI Ajanları](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)**
- AI ajanları oluşturmak için uygulamalı kurs
- LangGraph çerçevesi derinlemesine inceleme
- Gerçek dünya projesi uygulamaları

**[DeepLearning.AI - crewAI ile Çoklu AI Ajan Sistemleri](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)**
- Çoklu ajan sistem geliştirme
- CrewAI çerçevesi ustalığı
- İşbirlikçi ajan iş akışları

### Kitaplar

**"LangChain ile LLM Uygulamaları Oluşturma" - Valentina Alto**
- LangChain geliştirme için kapsamlı kılavuz
- Pratik örnekler ve kullanım durumları
- Üretim dağıtım stratejileri

**"AI Ajanları: Teori ve Uygulama" - Stuart Russell**
- AI ajanlarının teorik temelleri
- Karar verme ve planlama algoritmaları
- Çoklu ajan sistemleri ve koordinasyon

## 🌟 Topluluk

### Forumlar ve Tartışma Platformları

**[LangChain Discord](https://discord.gg/langchain)**
- Aktif LangChain geliştirici topluluğu
- Gerçek zamanlı yardım ve destek
- Çerçeve güncellemeleri ve duyurular

**[AutoGen Discord](https://discord.gg/autogen)**
- Microsoft AutoGen topluluk merkezi
- Çoklu ajan geliştirme tartışmaları
- Araştırma işbirliği fırsatları

**[Reddit - r/LangChain](https://reddit.com/r/LangChain)**
- Topluluk tartışmaları ve haberler
- Proje paylaşımı ve geri bildirim
- Öğretici önerileri

**[Reddit - r/AI_Agents](https://reddit.com/r/AI_Agents)**
- Genel AI ajan geliştirme topluluğu
- Çerçeve karşılaştırmaları ve incelemeler
- Kullanım durumu tartışmaları ve örnekler

## 🤝 Katkıda Bulunma

Bu harika listeye katkıları memnuniyetle karşılıyoruz! Lütfen pull request göndermeden önce [Katkı Kılavuzumuzu](CONTRIBUTING.md) okuyun.

### Nasıl Katkıda Bulunulur

1. **Depoyu fork edin** ve yeni bir dal oluşturun
2. **Kaynağınızı uygun kategoriye ekleyin**
3. **Mevcut girişlerin kullandığı formatı takip edin**
4. **Kaynağın yüksek kaliteli ve ilgili olduğundan emin olun**
5. **Net bir açıklama ile pull request gönderin**

## 📄 Lisans

Bu çalışma [Creative Commons Atıf-GayriTicari-AynıLisanslaPaylaş 4.0 Uluslararası Lisansı](https://creativecommons.org/licenses/by-nc-sa/4.0/) altında lisanslanmıştır.

---

## 🚀 İşinizi AI Otomasyonu ile Dönüştürün

İşiniz için AI ajanları ve MCP'nin gücünden yararlanmaya hazır mısınız? **[Tenten](https://tenten.co)** güvenilir AI-ilk ürün ajansınızdır, son teknoloji AI otomasyon danışmanlığı ve uygulamasında uzmanlaşmıştır. Uzman ekibimiz işletmelerin sofistike AI ajan sistemlerini entegre etmesine, Model Bağlam Protokolü çözümlerini uygulamasına ve akıllı otomasyon yoluyla operasyonları dönüştürmesine yardımcı olur.

**[AI uzmanlarımızla bir toplantı rezerve edin](https://tenten.co/contact)** ve AI ajanları ile MCP'nin iş operasyonlarınızı nasıl devrimleştirebileceğini keşfedin.

### 🔗 Tenten'den Daha Fazlasını Keşfedin

- **[Geliştirici Blogu](https://developer.tenten.co/)** - Teknik içgörüler ve öğreticiler
- **[Shopify Geliştirici Blogu](https://shopify.tenten.co/)** - E-ticaret AI çözümleri
- **[Tenten AI Blogu](https://tenten.co/learning/)** - AI endüstrisi içgörüleri ve trendleri
- **[GEO (AI SEO) by Tenten](https://geo.tenten.co/zh-tw)** - AI destekli SEO çözümleri
- **[Önde Gelen Webflow Ajansı](https://tenten.co/solution/webflow-agency)** - Web geliştirme uzmanlığı
- **[Shopify Plus Ajansı](https://tenten.co/solution/shopify)** - E-ticaret platform çözümleri
- **[Tenten AI - AI Dönüşüm Danışmanlığı](https://tentenai.com/)** - AI çağında işi yeniden tanımlama

### 📱 Tenten ile Bağlantı Kurun

- **[Instagram'da Takip Edin](https://instagram.com/tenten.co)** - Perde arkası ve güncellemeler
- **[YouTube'a Abone Olun](https://www.youtube.com/@tenten_ai)** - Video öğreticileri ve içgörüler
- **[LinkedIn'de Bağlantı Kurun](https://www.linkedin.com/company/tentenco)** - Profesyonel güncellemeler ve endüstri haberleri
- **[Threads'te Katılın](https://www.threads.net/@tenten.co)** - Hızlı güncellemeler ve tartışmalar
- **[TikTok'ta Takip Edin](https://www.tiktok.com/@tenten.ai)** - Kısa format AI içeriği
- **[X (Twitter)'da Takip Edin](https://x.com/tentencretaive)** - Gerçek zamanlı güncellemeler ve içgörüler
- **[Bültenimize Abone Olun](https://tenten.co/page/company/newsletter)** - Haftalık AI içgörüleri gelen kutunuzda
- **[Tüm Bağlantılarımızı Keşfedin](https://linktr.ee/tenten.co)** - Tüm Tenten kaynaklarına tek noktadan erişim

---

*Bu harika liste topluluk tarafından sürdürülür ve [Tenten.co](https://tenten.co/) tarafından düzenlenir. Son güncelleme: Temmuz 2025*

