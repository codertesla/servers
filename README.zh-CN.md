<!-- 顶部添加英文切换提示 -->
<div align="center">
  <a href="./README.md">View in English</a>
</div>

# Model Context Protocol 服务器合集

[English Version](README.md) | [中文版本](README.zh-CN.md)

<div align="center">
  <img src="https://img.shields.io/badge/翻译版本-2025.1.17-blue?style=flat-square" alt="翻译版本">
  <img src="https://img.shields.io/badge/同步状态-已同步-green?style=flat-square" alt="同步状态">
</div>

### 关于本翻译
本项目是 [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) 的非官方中文译本，由社区驱动维护。我们致力于：
- ✅ 准确传达技术细节
- 🌍 使用符合中文开发者习惯的表述
- ⏱️ 定期同步上游更新

**如何参与**  
- 报告翻译问题：[创建Issue](https://github.com/codertesla/servers/issues)
- 贡献翻译改进：[提交PR](https://github.com/codertesla/servers/pulls)
- 查看更新日志：[CHANGELOG_ZH.md](CHANGELOG_ZH.md)

## 🌟 参考服务器

这些服务器旨在展示MCP功能和TypeScript/Python SDK的应用：

- **[AWS KB Retrieval](src/aws-kb-retrieval-server)** - 通过Bedrock Agent Runtime从AWS知识库检索信息
- **[Brave Search](src/brave-search)** - 使用Brave搜索API进行网页和本地搜索
- **[EverArt](src/everart)** - 支持多种模型的AI图像生成
- **[Everything](src/everything)** - 包含提示、资源和工具的参考/测试服务器
- **[Fetch](src/fetch)** - 网页内容抓取与转换，优化LLM使用效率
- **[Filesystem](src/filesystem)** - 具备可配置访问控制的安全文件操作
- **[Git](src/git)** - Git仓库的读取、搜索和操作工具
- **[GitHub](src/github)** - 仓库管理、文件操作和GitHub API集成
- **[GitLab](src/gitlab)** - GitLab API支持的项目管理
- **[Google Drive](src/gdrive)** - Google Drive文件访问与搜索能力
- **[Google Maps](src/google-maps)** - 位置服务、路线规划和地点详情
- **[Memory](src/memory)** - 基于知识图谱的持久化记忆系统
- **[PostgreSQL](src/postgres)** - 支持模式检查的只读数据库访问
- **[Puppeteer](src/puppeteer)** - 浏览器自动化与网页抓取
- **[Redis](src/redis)** - Redis键值存储交互
- **[Sentry](src/sentry)** - 从Sentry.io获取和分析问题
- **[Sequential Thinking](src/sequentialthinking)** - 通过思维序列实现动态反思式问题解决
- **[Slack](src/slack)** - 频道管理与消息功能
- **[Sqlite](src/sqlite)** - 数据库交互与商业智能能力
- **[Time](src/time)** - 时间和时区转换功能

## 🤝 第三方服务器

### 🎖️ 官方集成

由企业维护的生产级MCP服务器实现：

- <img height="12" width="12" src="https://www.21st.dev/favicon.ico" alt="21st.dev Logo" /> **[21st.dev Magic](https://github.com/21st-dev/magic-mcp)** -  创建由 21st.dev 顶尖设计工程师启发的精美 UI 组件。
- <img height="12" width="12" src="https://invoxx-public-bucket.s3.eu-central-1.amazonaws.com/frontend-resources/adfin-logo-small.svg" alt="Adfin Logo" /> **[Adfin](https://github.com/Adfin-Engineering/mcp-server-adfin)** -  您只需这一个平台即可获得报酬 - 所有支付集中在一处，通过 [Adfin](https://www.adfin.com/) 实现发票和会计核对。
- <img height="12" width="12" src="https://www.agentql.com/favicon/favicon.png" alt="AgentQL Logo" /> **[AgentQL](https://github.com/tinyfish-io/agentql-mcp)** -  使 AI 代理能够使用 [AgentQL](https://www.agentql.com/) 从非结构化网络中获取结构化数据。
- <img height="12" width="12" src="https://agentrpc.com/favicon.ico" alt="AgentRPC Logo" /> **[AgentRPC](https://github.com/agentrpc/agentrpc)** -  使用 [AgentRPC](https://www.agentrpc.com/) 跨越网络边界连接到任何功能、任何语言。
- <img height="12" width="12" src="https://apify.com/favicon.ico" alt="Apify Logo" /> **[Apify](https://github.com/apify/actors-mcp-server)** -  [Actors MCP Server](https://apify.com/apify/actors-mcp-server): 使用 3,000 多个预构建的云工具从网站、电子商务、社交媒体、搜索引擎、地图等提取数据
- <img height="12" width="12" src="https://resources.audiense.com/hubfs/favicon-1.png" alt="Audiense Logo" /> **[Audiense Insights](https://github.com/AudienseCo/mcp-audiense-insights)** -  来自 [Audiense](https://www.audiense.com/products/audiense-insights) 报告的市场洞察和受众分析，涵盖人口统计、文化、影响者和内容参与度分析。
- <img height="12" width="12" src="https://axiom.co/favicon.ico" alt="Axiom Logo" /> **[Axiom](https://github.com/axiomhq/mcp-server-axiom)** -  以自然语言查询和分析您的 Axiom 日志、追踪和所有其他事件数据
- <img height="12" width="12" src="https://www.bankless.com/favicon.ico" alt="Bankless Logo" /> **[Bankless Onchain](https://github.com/bankless/onchain-mcp)** -  查询链上数据，如 ERC20 代币、交易历史、智能合约状态。
- <img height="12" width="12" src="https://www.box.com/favicon.ico" alt="Box Logo" /> **[Box](https://github.com/box-community/mcp-server-box)** -  通过 Box AI 与智能内容管理平台互动。
- <img height="12" width="12" src="https://browserbase.com/favicon.ico" alt="Browserbase Logo" /> **[Browserbase](https://github.com/browserbase/mcp-server-browserbase)** -  自动化云端浏览器互动（例如，网页导航、数据提取、表格填写等）
- <img height="12" width="12" src="https://trychroma.com/_next/static/media/chroma-logo.ae2d6e4b.svg" /> **[Chroma](https://github.com/chroma-core/chroma-mcp)** -  使用开源 AI 应用数据库进行嵌入、向量搜索、文档存储和全文搜索
- <img height="12" width="12" src="https://www.chronulus.com/favicon/chronulus-logo-blue-on-alpha-square-128x128.ico" alt="Chronulus AI Logo" /> **[Chronulus AI](https://github.com/ChronulusAI/chronulus-mcp)** -  使用 Chronulus AI 预测和预测代理预测任何事物。
- <img height="12" width="12" src="https://clickhouse.com/favicon.ico" alt="ClickHouse Logo" /> **[ClickHouse](https://github.com/ClickHouse/mcp-clickhouse)** -  查询您的 [ClickHouse](https://clickhouse.com/) 数据库服务器。
- <img height="12" width="12" src="https://cdn.simpleicons.org/cloudflare" /> **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** -  在 Cloudflare 开发者平台（例如 Workers/KV/R2/D1）上部署、配置和查询您的资源
- <img height="12" width="12" src="https://www.comet.com/favicon.ico" alt="Comet Logo" /> **[Comet Opik](https://github.com/comet-ml/opik-mcp)** -  以自然语言查询和分析您的 [Opik](https://github.com/comet-ml/opik) 日志、追踪、提示和来自 LLM 的所有其他遥测数据。
- <img height="12" width="12" src="https://www.convex.dev/favicon.ico" /> **[Convex](https://stack.convex.dev/convex-mcp-server)** -  内省和查询您部署到 Convex 的应用。
- <img height="12" width="12" src="http://app.itsdart.com/static/img/favicon.png" alt="Dart Logo" /> **[Dart](https://github.com/its-dart/dart-mcp-server)** -  与 [Dart](https://itsdart.com)（一款 AI 原生项目管理工具）中的任务、文档和项目数据互动
- <img height="12" width="12" src="https://www.devhub.com/img/upload/favicon-196x196-dh.png" alt="DevHub Logo" /> **[DevHub](https://github.com/devhub/devhub-cms-mcp)** -  在 [DevHub](https://www.devhub.com) CMS 平台内管理和利用网站内容
- <img height="12" width="12" src="https://e2b.dev/favicon.ico" alt="E2B Logo" /> **[E2B](https://github.com/e2b-dev/mcp-server)** -  在 [E2B](https://e2b.dev) 托管的安全沙箱中运行代码
- <img height="12" width="12" src="https://static.edubase.net/media/brand/favicon/favicon-32x32.png" alt="EduBase Logo" /> **[EduBase](https://github.com/EduBase/MCP)** -  与 [EduBase](https://www.edubase.net) 互动，这是一个综合性电子学习平台，具有高级测验、考试管理和内容组织功能
- <img height="12" width="12" src="https://esignatures.com/favicon.ico" alt="eSignatures Logo" /> **[eSignatures](https://github.com/esignaturescom/mcp-server-esignatures)** -  合同和模板管理，用于起草、审查和发送具有约束力的合同。
- <img height="12" width="12" src="https://exa.ai/images/favicon-32x32.png" alt="Exa Logo" /> **[Exa](https://github.com/exa-labs/exa-mcp-server)** -  由 [Exa](https://exa.ai) 为 AI 打造的搜索引擎
- <img height="12" width="12" src="https://fewsats.com/favicon.svg" alt="Fewsats Logo" /> **[Fewsats](https://github.com/Fewsats/fewsats-mcp)** -  使 AI 代理能够使用 [Fewsats](https://fewsats.com) 以安全方式购买任何物品
- <img height="12" width="12" src="https://fibery.io/favicon.svg" alt="Fibery Logo" /> **[Fibery](https://github.com/Fibery-inc/fibery-mcp-server)** -  在您的 [Fibery](https://fibery.io) 工作区中执行查询和实体操作。
- <img height="12" width="12" src="https://financialdatasets.ai/favicon.ico" alt="Financial Datasets Logo" /> **[Financial Datasets](https://github.com/financial-datasets/mcp-server)** -  为 AI 代理打造的股票市场 API
- <img height="12" width="12" src="https://firecrawl.dev/favicon.ico" alt="Firecrawl Logo" /> **[Firecrawl](https://github.com/mendableai/firecrawl-mcp-server)** -  使用 [Firecrawl](https://firecrawl.dev) 提取网络数据
- <img height="12" width="12" src="https://fireproof.storage/favicon.ico" alt="Fireproof Logo" /> **[Fireproof](https://github.com/fireproof-storage/mcp-database-server)** -  具有实时同步功能的不可变账本数据库
- <img height="12" width="12" src="https://gitee.com/favicon.ico" alt="Gitee Logo" /> **[Gitee](https://github.com/oschina/mcp-gitee)** -  Gitee API 集成、仓库、问题和拉取请求管理等。
- <img height="12" width="12" src="https://grafana.com/favicon.ico" alt="Grafana Logo" /> **[Grafana](https://github.com/grafana/mcp-grafana)** -  在您的 Grafana 实例中搜索仪表板、调查事件和查询数据源
- <img height="12" width="12" src="https://framerusercontent.com/images/KCOWBYLKunDff1Dr452y6EfjiU.png" alt="Graphlit Logo" /> **[Graphlit](https://github.com/graphlit/graphlit-mcp-server)** -  除了网络爬取之外，还将 Slack、Gmail 甚至播客提要中的任何内容摄取到可搜索的 [Graphlit](https://www.graphlit.com) 项目中。
- <img height="12" width="12" src="https://img.alicdn.com/imgextra/i3/O1CN01d9qrry1i6lTNa2BRa_!!6000000004364-2-tps-218-200.png" alt="Hologres Logo" /> **[Hologres](https://github.com/aliyun/alibabacloud-hologres-mcp-server)** -  连接到 [Hologres](https://www.alibabacloud.com/en/product/hologres) 实例，获取表元数据，查询和分析数据。
- <img height="12" width="12" src="https://hyperbrowser-assets-bucket.s3.us-east-1.amazonaws.com/Hyperbrowser-logo.png" alt="Hyperbrowsers23 Logo" /> **[Hyperbrowser](https://github.com/hyperbrowserai/mcp)** -  [Hyperbrowser](https://www.hyperbrowser.ai/) 是下一代平台，可增强 AI 代理的功能并实现轻松、可扩展的浏览器自动化。
- **[IBM wxflows](https://github.com/IBM/wxflows/tree/main/examples/mcp/javascript)** -  IBM 的工具平台，用于构建、测试和部署任何数据源的工具
- <img height="12" width="12" src="https://forevervm.com/icon.png" alt="ForeverVM Logo" /> **[ForeverVM](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server)** -  在代码沙箱中运行 Python。
- <img height="12" width="12" src="https://www.getinboxzero.com/icon.png" alt="Inbox Zero Logo" /> **[Inbox Zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server)** -  电子邮件 AI 个人助理 [Inbox Zero](https://www.getinboxzero.com)
- <img height="12" width="12" src="https://inkeep.com/favicon.ico" alt="Inkeep Logo" /> **[Inkeep](https://github.com/inkeep/mcp-server-python)** -  由 [Inkeep](https://inkeep.com) 提供支持的对您的内容进行 RAG 搜索
- <img height="12" width="12" src="https://integration.app/favicon.ico" alt="Integration App Icon" /> **[Integration App](https://github.com/integration-app/mcp-server)** -  代表您的客户与其他任何 SaaS 应用程序互动。
- <img height="12" width="12" src="https://cdn.simpleicons.org/jetbrains" /> **[JetBrains](https://github.com/JetBrains/mcp-jetbrains)** –  使用 JetBrains IDE 处理您的代码
- <img height="12" width="12" src="https://kagi.com/favicon.ico" alt="Kagi Logo" /> **[Kagi Search](https://github.com/kagisearch/kagimcp)** -  使用 Kagi 的搜索 API 搜索网络
- <img height="12" width="12" src="https://logfire.pydantic.dev/favicon.ico" alt="Logfire Logo" /> **[Logfire](https://github.com/pydantic/logfire-mcp)** -  通过 Logfire 提供对 OpenTelemetry 追踪和指标的访问。
- <img height="12" width="12" src="https://langfuse.com/favicon.ico" alt="Langfuse Logo" /> **[Langfuse Prompt Management](https://github.com/langfuse/mcp-server-langfuse)** -  用于协作编辑、版本控制、评估和发布提示的开源工具。
- <img height="12" width="12" src="https://lingo.dev/favicon.ico" alt="Lingo.dev Logo" /> **[Lingo.dev](https://github.com/lingodotdev/lingo.dev/blob/main/mcp.md)** -  使用 [Lingo.dev](https://lingo.dev) 本地化引擎，让您的 AI 代理说地球上的每一种语言。
- <img height="12" width="12" src="https://www.make.com/favicon.ico" alt="Make Logo" /> **[Make](https://github.com/integromat/make-mcp-server)** -  将您的 [Make](https://www.make.com/) 场景变成 AI 助手的可调用工具。
- <img height="12" width="12" src="https://www.meilisearch.com/favicon.ico" alt="Meilisearch Logo" /> **[Meilisearch](https://github.com/meilisearch/meilisearch-mcp)** -  与 Meilisearch（全文和语义搜索 API）互动和查询
- <img height="12" width="12" src="https://metoro.io/static/images/logos/Metoro.svg" /> **[Metoro](https://github.com/metoro-io/metoro-mcp-server)** -  查询和互动 Metoro 监控的 kubernetes 环境
- <img height="12" width="12" src="https://milvus.io/favicon-32x32.png" /> **[Milvus](https://github.com/zilliztech/mcp-server-milvus)** -  在您的 Milvus 向量数据库中搜索、查询和互动数据。
- <img height="12" width="12" src="https://www.motherduck.com/favicon.ico" alt="MotherDuck Logo" /> **[MotherDuck](https://github.com/motherduckdb/mcp-server-motherduck)** -  使用 MotherDuck 和本地 DuckDB 查询和分析数据
- <img height="12" width="12" src="https://needle-ai.com/images/needle-logo-orange-2-rounded.png" alt="Needle AI Logo" /> **[Needle](https://github.com/needle-ai/needle-mcp)** -  开箱即用的生产就绪 RAG，用于搜索和检索您自己的文档中的数据。
- <img height="12" width="12" src="https://neo4j.com/favicon.ico" alt="Neo4j Logo" /> **[Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)** -  Neo4j 图数据库服务器（模式 + 读/写-cypher）和单独的图数据库支持的内存
- <img height="12" width="12" src="https://avatars.githubusercontent.com/u/183852044?s=48&v=4" alt="Neon Logo" /> **[Neon](https://github.com/neondatabase/mcp-server-neon)** -  与 Neon 无服务器 Postgres 平台互动
- <img height="12" width="12" src="https://docs.octagonagents.com/logo.svg" alt="Octagon Logo" /> **[Octagon](https://github.com/OctagonAI/octagon-mcp-server)** -  提供具有广泛的私人和公共市场数据的实时投资研究。
- <img height="12" width="12" src="https://oxylabs.io/favicon.ico" alt="Oxylabs Logo" /> **[Oxylabs](https://github.com/oxylabs/oxylabs-mcp)** -  使用 Oxylabs Web API 抓取网站，支持动态渲染和解析以进行结构化数据提取。
- <img height="12" width="12" src="https://www.perplexity.ai/favicon.ico" alt="Perplexity Logo" /> **[Perplexity](https://github.com/ppl-ai/modelcontextprotocol)** -  一个连接到 Perplexity 的 Sonar API 的 MCP 服务器，可在对话式 AI 中实现实时全网研究。
- <img height="12" width="12" src="https://qdrant.tech/img/brand-resources-logos/logomark.svg" /> **[Qdrant](https://github.com/qdrant/mcp-server-qdrant/)** -  在 Qdrant 向量搜索引擎之上实施语义记忆层
- <img height="12" width="12" src="https://www.ramp.com/favicon.ico" /> **[Ramp](https://github.com/ramp-public/ramp-mcp)** -  与 [Ramp](https://ramp.com) 的开发者 API 互动，以运行支出分析并获得利用 LLM 的洞察力
- **[Raygun](https://github.com/MindscapeHQ/mcp-server-raygun)** -  与您的 Raygun 帐户上的崩溃报告和真实用户监控数据互动
- <img height="12" width="12" src="https://www.rember.com/favicon.ico" alt="Rember Logo" /> **[Rember](https://github.com/rember/rember-mcp)** -  在 [Rember](https://rember.com) 中创建间隔重复闪卡，以记住您在聊天中学到的任何内容
- <img height="12" width="12" src="https://riza.io/favicon.ico" alt="Riza logo" /> **[Riza](https://github.com/riza-io/riza-mcp)** -  由 [Riza](https://riza.io) 提供的 LLM 的任意代码执行和工具使用平台
- <img height="12" width="12" src="https://pics.fatwang2.com/56912e614b35093426c515860f9f2234.svg" /> [Search1API](https://github.com/fatwang2/search1api-mcp) -  用于搜索、爬取和站点地图的 API
- <img height="12" width="12" src="https://screenshotone.com/favicon.ico" alt="ScreenshotOne Logo" /> **[ScreenshotOne](https://github.com/screenshotone/mcp/)** -  使用 [ScreenshotOne](https://screenshotone.com/) 渲染网站屏幕截图
- <img height="12" width="12" src="https://www.starrocks.io/favicon.ico" alt="StarRocks Logo" /> **[StarRocks](https://github.com/StarRocks/mcp-server-starrocks)** -  与 [StarRocks](https://www.starrocks.io/) 互动
- <img height="12" width="12" src="https://stripe.com/favicon.ico" alt="Stripe Logo" /> **[Stripe](https://github.com/stripe/agent-toolkit)** -  与 Stripe API 互动
- <img height="12" width="12" src="https://tavily.com/favicon.ico" alt="Tavily Logo" /> **[Tavily](https://github.com/tavily-ai/tavily-mcp)** -  由 [Tavily](https://tavily.com/) 提供支持的 AI 代理搜索引擎（搜索 + 提取）
- <img height="12" width="12" src="https://www.tinybird.co/favicon.ico" alt="Tinybird Logo" /> **[Tinybird](https://github.com/tinybirdco/mcp-tinybird)** -  与 Tinybird 无服务器 ClickHouse 平台互动
- <img height="12" width="12" src="https://unifai.network/favicon.ico" alt="UnifAI Logo" /> **[UnifAI](https://github.com/unifai-network/unifai-mcp-server)** -  使用 [UnifAI Network](https://unifai.network) 动态搜索和调用工具
- **[Vectorize](https://github.com/vectorize-io/vectorize-mcp-server/)** -  [Vectorize](https://vectorize.io) MCP 服务器，用于高级检索、私有深度研究、Anything-to-Markdown 文件提取和文本分块。
- <img height="12" width="12" src="https://verodat.io/assets/favicon-16x16.png" alt="Verodat Logo" /> **[Verodat](https://github.com/Verodat/verodat-mcp-server)** -  与 Verodat AI Ready Data 平台互动
- <img height="12" width="12" src="https://www.veyrax.com/favicon.ico" alt="VeyraX Logo" /> **[VeyraX](https://github.com/VeyraX/veyrax-mcp)** -  用于控制所有 100 多个 API 集成和 UI 组件的单一工具
- **[ZenML](https://github.com/zenml-io/mcp-zenml)** -  通过您的 [ZenML](https://www.zenml.io) MCP 服务器与您的 MLOps 和 LLMOps 管道互动

### 🌎 社区服务器

不断增长的社区开发服务器展示了MCP在不同领域的应用：

> **注意：** 社区服务器未经测试，使用需谨慎。它们与Anthropic无关联且不受其认可。
- **[Ableton Live](https://github.com/Simon-Kansara/ableton-live-mcp-server)** - 用于控制 Ableton Live 的 MCP 服务器。
- **[Airbnb](https://github.com/openbnb-org/mcp-server-airbnb)** - 提供搜索 Airbnb 和获取房源详细信息的工具。
- **[Algorand](https://github.com/GoPlausible/algorand-mcp)** - 一个全面的 MCP 服务器，用于工具交互 (40+) 和资源可访问性 (60+) 以及许多用于与 Algorand 区块链交互的有用提示。
- **[Airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow)** - 一个使用官方 python 客户端连接到 [Apache Airflow](https://airflow.apache.org/) 的 MCP 服务器。
- **[Airtable](https://github.com/domdomegg/airtable-mcp-server)** - 对 [Airtable](https://airtable.com/) 数据库的读写访问，具有模式检查功能。
- **[Airtable](https://github.com/felores/airtable-mcp)** - Airtable Model Context Protocol Server。
- **[AlphaVantage](https://github.com/calvernaz/alphavantage)** - 股票市场数据 API [AlphaVantage](https://www.alphavantage.co) 的 MCP 服务器
- **[Anki](https://github.com/scorzeth/anki-mcp-server)** - 用于与您的 [Anki](https://apps.ankiweb.net) 卡组和卡片互动的 MCP 服务器。
- **[Any Chat Completions](https://github.com/pyroprompts/any-chat-completions-mcp)** - 与任何 OpenAI SDK 兼容的聊天完成 API 互动，如 OpenAI、Perplexity、Groq、xAI 等。
- **[ArangoDB](https://github.com/ravenwits/mcp-server-arangodb)** - 通过 [ArangoDB](https://arangodb.com/) 提供数据库互动功能的 MCP 服务器。
- **[Atlassian](https://github.com/sooperset/mcp-atlassian)** - 与 Atlassian Cloud 产品（Confluence 和 Jira）互动，包括搜索/阅读 Confluence 空间/页面、访问 Jira 问题和项目元数据。
- **[AWS](https://github.com/rishikavikondala/mcp-server-aws)** - 使用 LLM 对您的 AWS 资源执行操作。
- **[AWS Athena](https://github.com/lishenxydlgzs/aws-athena-mcp)** - 用于 AWS Athena 在 Glue Catalog 上运行 SQL 查询的 MCP 服务器。
- **[AWS Cost Explorer](https://github.com/aarora79/aws-cost-explorer-mcp-server)** - 通过检查跨区域、服务、实例类型和基础模型的支出（包括 Amazon Bedrock 支出），使用此 MCP 服务器优化您的 AWS 支出 ([演示视频](https://www.youtube.com/watch?v=WuVOmYLRFmI&feature=youtu.be))。
- **[AWS S3](https://github.com/aws-samples/sample-mcp-server-s3)** - 一个用于 AWS S3 的示例 MCP 服务器，可以灵活地从 S3 获取对象，例如 PDF 文档。
- **[Azure ADX](https://github.com/pab1it0/adx-mcp-server)** - 查询和分析 Azure 数据资源管理器数据库。
- **[Base Free USDC Transfer](https://github.com/magnetai/mcp-free-usdc-transfer)** - 使用 Claude AI 在 [Base](https://base.org) 上免费发送 USDC！使用 [Coinbase CDP](https://docs.cdp.coinbase.com/mpc-wallet/docs/welcome) 构建。
* **[Basic Memory](https://github.com/basicmachines-co/basic-memory)** - 本地优先知识管理系统，可从 Markdown 文件构建语义图，从而在与 LLM 的对话中实现持久记忆。
- **[BigQuery](https://github.com/LucasHild/mcp-server-bigquery)** (by LucasHild) - 此服务器使 LLM 能够检查数据库模式并在 BigQuery 上执行查询。
- **[BigQuery](https://github.com/ergut/mcp-bigquery-server)** (by ergut) - 用于 Google BigQuery 集成的服务器实现，可实现直接 BigQuery 数据库访问和查询功能
- **[Bing Web Search API](https://github.com/leehanchung/bing-search-mcp)** (by hanchunglee) - 用于 Microsoft Bing Web Search API 的服务器实现。
- **[Bitable MCP](https://github.com/lloydzhou/bitable-mcp)** (by lloydzhou) - MCP 服务器通过 Model Context Protocol 提供对 Lark Bitable 的访问。它允许用户使用预定义的工具与 Bitable 表格互动。
- **[Blender](https://github.com/ahujasid/blender-mcp)** (by ahujasid) - Blender 集成允许提示启用 3D 场景创建、建模和操作。
- **[CFBD API](https://github.com/lenwood/cfbd-mcp-server)** - [大学橄榄球数据 API](https://collegefootballdata.com/) 的 MCP 服务器。
- **[ChatMCP](https://github.com/AI-QL/chat-mcp)** – 由 **[AIQL](https://github.com/AI-QL)** 提供的开源跨平台 GUI 桌面应用程序，兼容 Linux、macOS 和 Windows，支持跨动态可选 LLM 与 MCP 服务器无缝互动
- **[ChatSum](https://github.com/mcpso/mcp-server-chatsum)** - 使用 LLM 查询和总结聊天消息。由 [mcpso](https://mcp.so) 提供
- **[Chroma](https://github.com/privetin/chroma)** - 基于 Chroma 构建的用于语义文档搜索和元数据过滤的向量数据库服务器
- **[ClaudePost](https://github.com/ZilongXue/claude-post)** - ClaudePost 为 Gmail 提供无缝电子邮件管理，提供电子邮件搜索、阅读和发送等安全功能。
- **[Cloudinary](https://github.com/felores/cloudinary-mcp-server)** - Cloudinary Model Context Protocol Server，用于将媒体上传到 Cloudinary 并取回媒体链接和详细信息。
- **[code-assistant](https://github.com/stippi/code-assistant)** - 一个编码助手 MCP 服务器，允许探索代码库并对代码进行更改。应仅与受信任的仓库一起使用（针对提示注入的保护不足）。
- **[code-executor](https://github.com/bazinga012/mcp_code_executor)** - 一个 MCP 服务器，允许 LLM 在指定的 Conda 环境中执行 Python 代码。
- **[code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp)** - 一个 MCP 服务器，用于创建安全的代码沙箱环境，以在 Docker 容器中执行代码。
- **[cognee-mcp](https://github.com/topoteretes/cognee/tree/main/cognee-mcp)** - 具有可自定义的摄取、数据处理和搜索功能的 GraphRAG 内存服务器
- **[coin_api_mcp](https://github.com/longmans/coin_api_mcp)** - 提供对 [coinmarketcap](https://coinmarketcap.com/) 加密货币数据的访问。
- **[Contentful-mcp](https://github.com/ivo-toby/contentful-mcp)** - 从此 MCP 服务器读取、更新、删除、发布您的 [Contentful](https://contentful.com) 空间中的内容。
- **[Dappier](https://github.com/DappierAI/dappier-mcp)** - 将 LLM 连接到来自受信任来源的实时、版权许可的专有数据。访问用于实时网络搜索、新闻、体育、金融数据、加密货币和高级发布商内容的专用模型。在 [marketplace.dappier.com](https://marketplace.dappier.com/marketplace) 探索数据模型。
- **[Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration)** - 用于在基于 .csv 的数据集上进行自主数据探索的 MCP 服务器，以最少的精力提供智能洞察。注意：将在您的机器上执行任意 Python 代码，请谨慎使用！
- **[Dataset Viewer](https://github.com/privetin/dataset-viewer)** - 浏览和分析 Hugging Face 数据集，具有搜索、过滤、统计和数据导出等功能
- **[DBHub](https://github.com/bytebase/dbhub/)** - 连接到 MySQL、PostgreSQL、SQLite、DuckDB 等的通用数据库 MCP 服务器。
- **[DeepSeek MCP Server](https://github.com/DMontgomery40/deepseek-mcp-server)** - 集成 DeepSeek 高级语言模型的 Model Context Protocol 服务器，以及[其他有用的 API 端点](https://github.com/DMontgomery40/deepseek-mcp-server?tab=readme-ov-file#features)
- **[Deepseek_R1](https://github.com/66julienmartin/MCP-server-Deepseek_R1)** - 连接 Claude Desktop 和 DeepSeek 语言模型 (R1/V3) 的 Model Context Protocol (MCP) 服务器实现
- **[deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp)** - 一个 MCP（Model Context Protocol）提供程序 Deepseek 推理内容到支持 MCP 的 AI 客户端，如 Claude Desktop。支持从 Deepseek API 服务或本地 Ollama 服务器访问 Deepseek 的思考过程。
- **[Descope](https://github.com/descope-sample-apps/descope-mcp-server)** - 一个与 [Descope](https://descope.com) 集成的 MCP 服务器，用于搜索审计日志、管理用户等。
- **[DevRev](https://github.com/kpsunil97/devrev-mcp-server)** - 一个与 DevRev API 集成的 MCP 服务器，用于搜索 DevRev 知识图谱，其中的对象可以从[此处](https://devrev.ai/docs/import#available-sources)列出的不同来源导入。
- **[Dicom](https://github.com/ChristianHinge/dicom-mcp)** - 一个 MCP 服务器，用于查询和检索医学图像，以及用于解析和读取 dicom 封装的文档（pdf 等）。
- **[Dify](https://github.com/YanxingLiu/dify-mcp-server)** - 一个用于 dify 工作流程的 MCP 服务器的简单实现。
- **[Discord](https://github.com/v-3/discordmcp)** - 一个 MCP 服务器，用于通过机器人连接到 Discord 公会，并在频道中读取和写入消息
- **[Discourse](https://github.com/AshDevFr/discourse-mcp-server)** - 一个 MCP 服务器，用于在 Discourse 论坛上搜索 Discourse 帖子。
- **[Docker](https://github.com/ckreiling/mcp-server-docker)** - 与 Docker 集成以管理容器、镜像、卷和网络。
- **[Drupal](https://github.com/Omedia/mcp-server-drupal)** - 使用 STDIO 传输层与 [Drupal](https://www.drupal.org/project/mcp) 互动的服务器。
- **[Elasticsearch](https://github.com/cr7258/elasticsearch-mcp-server)** - 提供 Elasticsearch 互动的 MCP 服务器实现。
- **[ElevenLabs](https://github.com/mamertofabian/elevenlabs-mcp-server)** - 一个与 ElevenLabs 文本到语音 API 集成的服务器，能够生成具有多种声音的完整配音。
- **[Ergo Blockchain MCP](https://github.com/marctheshark3/ergo-mcp)** - 一个 MCP 服务器，用于集成 Ergo 区块链节点和浏览器 API，以检查地址余额、分析交易、查看交易历史记录、对地址执行取证分析、搜索代币和监控网络状态。
- **[Eunomia](https://github.com/whataboutyou-ai/eunomia-MCP-server)** - Eunomia 框架的扩展，将 Eunomia 仪器与 MCP 服务器连接起来
- **[EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server)** - 适用于 30 多个 EVM 网络的综合区块链服务，支持原生代币、ERC20、NFT、智能合约、交易和 ENS 解析。
- **[Everything Search](https://github.com/mamertofabian/mcp-everything-search)** - 跨 Windows（使用 [Everything SDK](https://www.voidtools.com/support/everything/sdk/)）、macOS（使用 mdfind 命令）和 Linux（使用 locate/plocate 命令）的快速文件搜索功能。
- **[Fantasy PL](https://github.com/rishijatia/fantasy-pl-mcp)** - 让您的编码代理直接访问最新的 Fantasy Premier League 数据
- **[Fetch](https://github.com/zcaceres/fetch-mcp)** - 一个可以灵活获取 HTML、JSON、Markdown 或纯文本的服务器。
- **[Fingertip](https://github.com/fingertip-com/fingertip-mcp)** - Fingertip.com 的 MCP 服务器，用于搜索和创建新站点。
- **[Figma](https://github.com/GLips/Figma-Context-MCP)** - 让您的编码代理直接访问 Figma 文件数据，帮助其一次性完成设计实现。
- **[Firebase](https://github.com/gannonh/firebase-mcp)** - 与 Firebase 服务（包括 Firebase Authentication、Firestore 和 Firebase Storage）互动的服务器。
- **[FireCrawl](https://github.com/vrknetha/mcp-server-firecrawl)** - 具有 JavaScript 渲染、PDF 支持和智能速率限制的高级网络抓取
- **[FlightRadar24](https://github.com/sunsetcoder/flightradar24-mcp-server)** - 一个 Claude Desktop MCP 服务器，可帮助您使用 Flightradar24 数据实时跟踪航班。
- **[Ghost](https://github.com/MFYDev/ghost-mcp)** - 一个 Model Context Protocol (MCP) 服务器，用于通过 Claude 等 LLM 界面与 Ghost CMS 互动。
- **[Github Actions](https://github.com/ko1ynnky/github-actions-mcp-server)** - 一个用于与 Github Actions 互动的 Model Context Protocol (MCP) 服务器。
- **[Glean](https://github.com/longyi1207/glean-mcp-server)** - 一个使用 Glean API 进行搜索和聊天的服务器。
- **[Gmail](https://github.com/GongRzhe/Gmail-MCP-Server)** - 一个用于 Claude Desktop 中 Gmail 集成的 Model Context Protocol (MCP) 服务器，具有自动身份验证支持。
- **[Gmail Headless](https://github.com/baryhuang/mcp-headless-gmail)** - 远程可托管的 MCP 服务器，无需本地凭据或文件系统设置即可获取和发送 Gmail 消息。
- **[Goal Story](https://github.com/hichana/goalstory-mcp)** - 一个用于个人和职业发展的目标跟踪器和可视化工具。
- **[GOAT](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol)** - 在任何区块链（包括 Ethereum、Solana 和 Base）上运行超过 200 个链上操作。
- **[Godot](https://github.com/Coding-Solo/godot-mcp)** - 一个 MCP 服务器，提供全面的 Godot 引擎集成，用于项目编辑、调试和场景管理。
- **[Golang Filesystem Server](https://github.com/mark3labs/mcp-filesystem-server)** - 使用 Go 构建的具有可配置访问控制的安全文件操作！
- **[Google Calendar](https://github.com/v-3/google-calendar)** - 与 Google 日历集成以检查日程安排、查找时间以及添加/删除事件
- **[Google Calendar](https://github.com/nspady/google-calendar-mcp)** - 用于管理 Google 日历事件的 Google 日历 MCP 服务器。还支持按标题和位置等属性搜索事件。
- **[Google Custom Search](https://github.com/adenot/mcp-google-search)** - 通过 Google Custom Search API 提供 Google 搜索结果
- **[Google Tasks](https://github.com/zcaceres/gtasks-mcp)** - Google Tasks API Model Context Protocol Server。
- **[GraphQL Schema](https://github.com/hannesj/mcp-graphql-schema)** - 允许 LLM 探索大型 GraphQL 模式，而不会使上下文膨胀。
- **[HDW LinkedIn](https://github.com/horizondatawave/hdw-mcp-server)** - 访问 [HorizonDataWave.ai](https://horizondatawave.ai/) 的个人资料数据和用户帐户管理。
- **[Heurist Mesh Agent](https://github.com/heurist-network/heurist-mesh-mcp-server)** - 通过 [Heurist Mesh 网络](https://github.com/heurist-network/heurist-agent-framework/tree/main/mesh) 访问用于区块链分析、智能合约安全、代币指标和区块链互动的专用 web3 AI 代理。
- **[Holaspirit](https://github.com/syucream/holaspirit-mcp-server)** - 与 [Holaspirit](https://www.holaspirit.com/) 互动。
- **[Home Assistant](https://github.com/tevonsb/homeassistant-mcp)** - 与 [Home Assistant](https://www.home-assistant.io/) 互动，包括查看和控制灯光、开关、传感器和所有其他 Home Assistant 实体。
- **[Home Assistant](https://github.com/voska/hass-mcp)** - 用于 Home Assistant 的 Docker 就绪 MCP 服务器，具有实体管理、域摘要、自动化支持和引导式对话。包括预构建的容器镜像，便于安装。
- **[HubSpot](https://github.com/buryhuang/mcp-hubspot)** - HubSpot CRM 集成，用于管理联系人和公司。直接通过 Claude 聊天创建和检索 CRM 数据。
- **[HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace)** - 用于使用 HuggingFace Spaces 的服务器，支持开源图像、音频、文本模型等。Claude Desktop 模式，便于集成。
- **[Hyperliquid](https://github.com/mektigboy/server-hyperliquid)** - 一个 MCP 服务器实现，集成了 Hyperliquid SDK 以获取交易所数据。
- **[Image Generation](https://github.com/GongRzhe/Image-Generation-MCP-Server)** - 此 MCP 服务器使用 Replicate Flux 模型提供图像生成功能。
- **[InfluxDB](https://github.com/idoru/influxdb-mcp-server)** - 对 InfluxDB OSS API v2 运行查询。
- **[Inoyu](https://github.com/sergehuber/inoyu-mcp-unomi-server)** - 与 Apache Unomi CDP 客户数据平台互动，以检索和更新客户资料
- **[Intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom)** - 一个符合 MCP 标准的服务器，用于从 Intercom 检索客户支持票证。此工具使 Claude Desktop 和 Cline 等 AI 助手能够访问和分析您的 Intercom 支持票证。
- **[iTerm MCP](https://github.com/ferrislucas/iterm-mcp)** - 与 macOS 的 iTerm2 终端模拟器集成，使 LLM 能够执行和监控终端命令。
- **[JavaFX](https://github.com/mcpso/mcp-server-javafx)** - 使用 JavaFX 画布进行绘图
- **[JDBC](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc)** - 连接到任何 JDBC 兼容的数据库并进行查询、插入、更新、删除等操作。支持 MySQL、PostgreSQL、Oracle、SQL Server、sqllite 和[更多](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc#supported-jdbc-variants)。
- **[JSON](https://github.com/GongRzhe/JSON-MCP-Server)** - JSON 处理服务器，具有使用 JSONPath 语法的高级查询功能，并支持数组、字符串、数字和日期操作。
- **[Keycloak MCP](https://github.com/ChristophEnglisch/keycloak-model-context-protocol)** - 此 MCP 服务器支持与 Keycloak 进行自然语言互动，以进行用户和领域管理，包括创建、删除和列出用户和领域。
- **[Kibela](https://github.com/kiwamizamurai/mcp-kibela-server)** (by kiwamizamurai) - 与 Kibela API 互动。
- **[kintone](https://github.com/macrat/mcp-server-kintone)** - 通过 LLM 工具管理 [kintone](https://kintone.com) 中的记录和应用程序。
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** - 连接到 Kubernetes 集群并管理 pod、部署和服务。
- **[Kubernetes and OpenShift](https://github.com/manusa/kubernetes-mcp-server)** - 一个强大的 Kubernetes MCP 服务器，额外支持 OpenShift。除了为任何 Kubernetes 资源提供 CRUD 操作外，此服务器还提供用于与您的集群互动的专用工具。
- **[Langflow-DOC-QA-SERVER](https://github.com/GongRzhe/Langflow-DOC-QA-SERVER)** - 一个由 Langflow 提供支持的文档问答 Model Context Protocol 服务器。它通过提供一个简单的界面来查询通过 Langflow 后端的文档，从而演示了核心 MCP 概念。
- **[Lightdash](https://github.com/syucream/lightdash-mcp-server)** - 与 [Lightdash](https://www.lightdash.com/)（一种 BI 工具）互动。
- **[Linear](https://github.com/jerhadf/linear-mcp-server)** - 允许 LLM 与 Linear 的 API 互动以进行项目管理，包括搜索、创建和更新问题。
- **[Linear (Go)](https://github.com/geropl/linear-mcp-go)** - 允许 LLM 通过单个静态二进制文件与 Linear 的 API 互动。
- **[LINE](https://github.com/amornpan/py-mcp-line)** (by amornpan) - 用于 LINE Bot 集成的实现，使语言模型能够通过标准化界面读取和分析 LINE 对话。具有异步操作、全面的日志记录、webhook 事件处理以及对各种消息类型的支持。
- **[LlamaCloud](https://github.com/run-llama/mcp-server-llamacloud)** (by marcusschiesser) - 集成存储在 [LlamaCloud](https://cloud.llamaindex.ai/) 上的托管索引中的数据
- **[llm-context](https://github.com/cyberchitta/llm-context.py)** - 提供一个 repo-packing MCP 工具，该工具具有可配置的配置文件，这些配置文件指定文件包含/排除模式和可选提示。
- **[mac-messages-mcp](https://github.com/carterlasalle/mac_messages_mcp)** - 一个 MCP 服务器，通过 Model Context Protocol (MCP) 安全地与您的 iMessage 数据库连接，允许 LLM 查询和分析 iMessage 对话。它包括强大的电话号码验证、附件处理、联系人管理、群聊处理以及对发送和接收消息的完全支持。
- **[MariaDB](https://github.com/abel9851/mcp-server-mariadb)** - MariaDB 数据库集成，在 Python 中具有可配置的访问控制。
- **[MCP Compass](https://github.com/liuyoshio/mcp-compass)** - 为您推荐合适的 MCP 服务器
- **[MCP Create](https://github.com/tesla0225/mcp-create)** - 一种动态 MCP 服务器管理服务，可动态创建、运行和管理 Model Context Protocol 服务器。
- **[MCP Installer](https://github.com/anaisbetts/mcp-installer)** - 此服务器是一个为您安装其他 MCP 服务器的服务器。
- **[mcp-k8s-go](https://github.com/strowk/mcp-k8s-go)** - 基于 Golang 的 Kubernetes 服务器，用于 MCP 浏览 pod 及其日志、事件、命名空间等。旨在实现可扩展性。
- **[mcp-local-rag](https://github.com/nkapila6/mcp-local-rag)** - "原始" RAG 样式的网络搜索模型上下文协议 (MCP) 服务器，该服务器使用 Google 的 MediaPipe Text Embedder 和 DuckDuckGo Search 在本地运行。✨ 无需 API ✨。
- **[mcp-proxy](https://github.com/sparfenyuk/mcp-proxy)** - 连接到在 SSE 传输上运行的 MCP 服务器，或将 stdio 服务器公开为 SSE 服务器。
- **[mem0-mcp](https://github.com/mem0ai/mem0-mcp)** - Mem0 的 Model Context Protocol 服务器，可帮助管理编码首选项。
- **[MSSQL](https://github.com/aekanun2020/mcp-server/)** - MSSQL 数据库集成，具有可配置的访问控制和模式检查
- **[MSSQL](https://github.com/JexinSam/mssql_mcp_server)** (by jexin) - Python 中的 MSSQL 数据库的 MCP 服务器
- **[MSSQL-Python](https://github.com/amornpan/py-mcp-mssql)** (by amornpan) - 用于 MSSQL 数据库访问的只读 Python 实现，具有增强的安全功能、可配置的访问控制和模式检查功能。专注于通过 Python 生态系统进行安全的数据库互动。
- **[MSSQL-MCP](https://github.com/daobataotie/mssql-mcp)** (by daobataotie) - MSSQL MCP，参考官方网站的 SQLite MCP 进行修改以适应 MSSQL
- **[Markdownify](https://github.com/zcaceres/mcp-markdownify-server)** - MCP，用于将几乎所有内容转换为 Markdown（PPTX、HTML、PDF、Youtube 脚本等）
- **[Mindmap](https://github.com/YuChenSSR/mindmap-mcp-server)** (by YuChenSSR) - 一个从包含 markdown 代码的输入生成思维导图的服务器。
- **[Minima](https://github.com/dmayboroda/minima)** - 用于本地文件 RAG 的 MCP 服务器
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** - MongoDB 的 Model Context Protocol Server。
- **[MongoDB Lens](https://github.com/furey/mongodb-lens)** - 用于 MongoDB 数据库的全功能 MCP 服务器。
- **[Monday.com](https://github.com/sakce/mcp-server-monday)** - 与 Monday.com 面板和项目互动的 MCP 服务器。
- **[Multicluster-MCP-Sever](https://github.com/yanmxa/multicluster-mcp-server)** - GenAI 系统与多个 Kubernetes 集群互动的网关。
- **[MySQL](https://github.com/benborla/mcp-server-mysql)** (by benborla) - NodeJS 中的 MySQL 数据库集成，具有可配置的访问控制和模式检查
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** (by DesignComputer) - Python 中的 MySQL 数据库集成，具有可配置的访问控制和模式检查
- **[n8n](https://github.com/leonardsellem/n8n-mcp-server)** - 此 MCP 服务器为 AI 助手提供工具和资源，以管理 n8n 工作流程和执行，包括列出、创建、更新和删除工作流程，以及监控其执行状态。
- **[NASA](https://github.com/ProgramComputer/NASA-MCP-server)** (by ProgramComputer) - 访问 NASA 数据源的统一网关，包括但不限于 APOD、NEO、EPIC、GIBS。
- **[NAVER](https://github.com/pfldy2850/py-mcp-naver)** (by pfldy2850) - 此 MCP 服务器提供与各种 Naver 服务互动的工具，例如搜索博客、新闻、书籍等。
- **[NS Travel Information](https://github.com/r-huijts/ns-mcp-server)** - 通过官方 NS API 访问荷兰铁路 (NS) 实时列车旅行信息和中断信息。
- **[Neo4j](https://github.com/da-okazaki/mcp-neo4j-server)** - 一个社区构建的与 Neo4j 图数据库互动的服务器。
- **[Neovim](https://github.com/bigcodegen/mcp-neovim-server)** - 适用于您的 Neovim 会话的 MCP 服务器。
- **[Notion](https://github.com/suekou/mcp-notion-server)** (by suekou) - 与 Notion API 互动。
- **[Notion](https://github.com/v-3/notion-server)** (by v-3) - Notion MCP 集成。通过 Claude 聊天搜索、读取、更新和创建页面。
- **[ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp)** (by teddyzxcv) - MCP 服务器，通过使用 ntfy 在手机上发送通知来让您随时了解情况
- **[oatpp-mcp](https://github.com/oatpp/oatpp-mcp)** - Oat++ 的 C++ MCP 集成。使用 [Oat++](https://oatpp.io) 构建 MCP 服务器。
- **[Obsidian Markdown Notes](https://github.com/calclavia/mcp-obsidian)** - 读取和搜索您的 Obsidian vault 或任何包含 Markdown 笔记的目录
- **[obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp)** - (by Steven Stavrakis) Obsidian.md 的 MCP 服务器，具有用于搜索、读取、写入和组织笔记的工具。
- **[OceanBase](https://github.com/yuanoOo/oceanbase_mcp_server)** - (by yuanoOo) 一个 Model Context Protocol (MCP) 服务器，支持与 OceanBase 数据库的安全互动。
- **[Okta](https://github.com/kapilduraphe/okta-mcp-server)** - 与 Okta API 互动。
- **[OneNote](https://github.com/rajvirtual/MCP-Servers/tree/master/onenote)** - (by Rajesh Vijay) 一个使用 Microsoft Graph API 连接到 Microsoft OneNote 的 MCP 服务器。从 OneNote 读取笔记本、分区和页面，在 OneNote 中创建新的笔记本、分区和页面。
- **[OpenAI WebSearch MCP](https://github.com/ConechoAI/openai-websearch-mcp)** - 这是一个基于 Python 的 MCP 服务器，提供 OpenAI `web_search` 内置工具。
- **[OpenAPI](https://github.com/snaggle-ai/openapi-mcp-server)** - 与 [OpenAPI](https://www.openapis.org/) API 互动。
- **[OpenAPI AnyApi](https://github.com/baryhuang/mcp-server-any-openapi)** - 使用内置的端点语义搜索与大型 [OpenAPI](https://www.openapis.org/) 文档互动。允许自定义 MCP 服务器前缀。
- **[OpenAPI Schema](https://github.com/hannesj/mcp-openapi-schema)** - 允许 LLM 探索大型 [OpenAPI](https://www.openapis.org/) 模式，而不会使上下文膨胀。
- **[OpenCTI](https://github.com/Spathodea-Network/opencti-mcp)** - 与 OpenCTI 平台互动，以检索威胁情报数据，包括报告、指标、恶意软件和威胁行为者。
- **[OpenDota](https://github.com/asusevski/opendota-mcp-server)** - 与 OpenDota API 互动，以检索 Dota 2 比赛数据、玩家统计数据等。
- **[OpenRPC](https://github.com/shanejonas/openrpc-mpc-server)** - 通过 [OpenRPC](https://open-rpc.org) 与 JSON-RPC API 互动和发现。
- **[Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools)** - 内容编辑代码、价值地图和产品营销定位工具。
- **[Pandoc](https://github.com/vivekVells/mcp-pandoc)** - MCP 服务器，用于使用 Pandoc 进行无缝文档格式转换，支持 Markdown、HTML、PDF、DOCX (.docx)、csv 等。
- **[PIF](https://github.com/hungryrobot1/MCP-PIF)** - 个人智能框架 (PIF)，提供文件操作、结构化推理和基于日志的文档工具，以支持跨会话的连续性和不断发展的人工智能协作。
- **[Pinecone](https://github.com/sirmews/mcp-pinecone)** - 用于搜索和上传记录到 Pinecone 的 MCP 服务器。允许简单的 RAG 功能，利用 Pinecone 的推理 API。
- **[Placid.app](https://github.com/felores/placid-mcp-server)** - 使用 Placid.app 模板生成图像和视频创意素材
- **[Playwright](https://github.com/executeautomation/mcp-playwright)** - 此 MCP 服务器将帮助您使用 Playwright 运行浏览器自动化和网络抓取
- **[Postman](https://github.com/shannonlal/mcp-postman)** - 用于通过 Newman 在本地运行 Postman 集合的 MCP 服务器。允许简单执行 Postman 服务器并返回集合是否通过所有测试的结果。
- **[Productboard](https://github.com/kenjihikmatullah/productboard-mcp)** - 通过 MCP 将 Productboard API 集成到代理工作流程中。
- **[Prometheus](https://github.com/pab1it0/prometheus-mcp-server)** - 查询和分析 Prometheus - 开源监控系统。
- **[Pulumi](https://github.com/dogukanakkaya/pulumi-mcp-server)** - 与 Pulumi API 互动的 MCP 服务器，创建和列出堆栈
- **[Pushover](https://github.com/ashiknesin/pushover-mcp)** - 使用 [Pushover.net](https://pushover.net/) 向您的设备发送即时通知
- **[QGIS](https://github.com/jjsantos01/qgis_mcp)** - 通过 MCP 将 QGIS 连接到 Claude AI。此集成支持提示辅助的项目创建、图层加载、代码执行等。
- **[QuickChart](https://github.com/GongRzhe/Quickchart-MCP-Server)** - 一个用于使用 QuickChart.io 生成图表的 Model Context Protocol 服务器
- **[Qwen_Max](https://github.com/66julienmartin/MCP-server-Qwen_Max)** - Qwen 模型的 Model Context Protocol (MCP) 服务器实现。
- **[RabbitMQ](https://github.com/kenliao94/mcp-server-rabbitmq)** - 与 RabbitMQ 互动以发布和消费消息的 MCP 服务器。
- **[RAG Web Browser](https://github.com/apify/mcp-server-rag-web-browser)** 用于 Apify 的开源 RAG Web Browser [Actor](https://apify.com/apify/rag-web-browser) 的 MCP 服务器，用于执行网络搜索、抓取 URL 并以 Markdown 格式返回内容。
- **[Reaper](https://github.com/dschuler36/reaper-mcp-server)** - 与您的 [Reaper](https://www.reaper.fm/)（数字音频工作站）项目互动。
- **[Redis](https://github.com/GongRzhe/REDIS-MCP-Server)** - Redis 数据库操作和缓存微服务服务器，支持键值操作、过期管理和基于模式的键列表。
- **[Redis](https://github.com/prajwalnayak7/mcp-server-redis)** MCP 服务器，用于与 Redis Server、AWS Memory DB 等互动，以进行缓存或其他适合内存和基于键值存储的用例
- **[Rememberizer AI](https://github.com/skydeckai/mcp-server-rememberizer)** - 一个 MCP 服务器，旨在与 Rememberizer 数据源互动，从而促进增强的知识检索。
- **[Replicate](https://github.com/deepfates/mcp-replicate)** - 通过简单的基于工具的界面在 Replicate 上搜索、运行和管理机器学习模型。浏览模型、创建预测、跟踪其状态并处理生成的图像。
- **[Rquest](https://github.com/xxxbrian/mcp-rquest)** - 一个 MCP 服务器，提供具有准确 TLS/JA3/JA4 指纹的逼真浏览器式 HTTP 请求功能，用于绕过反机器人措施。
- **[Rijksmuseum](https://github.com/r-huijts/rijksmuseum-mcp)** - 与 Rijksmuseum API 接口，以搜索艺术品、检索艺术品详细信息、访问图像图块和探索用户收藏。
- **[Salesforce MCP](https://github.com/smn2gnt/MCP-Salesforce)** - 与 Salesforce 数据和元数据互动
- **[Scholarly](https://github.com/adityak74/mcp-scholarly)** - 用于搜索学术和学术文章的 MCP 服务器。
- **[scrapling-fetch](https://github.com/cyberchitta/scrapling-fetch-mcp)** - 访问受机器人保护的网站的文本内容。使用 Scrapling 从具有反自动化措施的站点获取 HTML/markdown。
- **[SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng)** - [SearXNG](https://docs.searxng.org) 的 Model Context Protocol Server
- **[ServiceNow](https://github.com/osomai/servicenow-mcp)** - 一个与 ServiceNow 实例互动的 MCP 服务器
- **[Siri Shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts)** - MCP 与 macOS 上的 Siri Shortcuts 互动。将所有 Shortcuts 公开为 MCP 工具。
- **[Snowflake](https://github.com/isaacwasserman/mcp-snowflake-server)** - 此 MCP 服务器使 LLM 能够与 Snowflake 数据库互动，从而实现安全且受控的数据操作。
- **[Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server)** - 此 MCP 服务器使 LLM 能够在 SendAI 的 Solana Agent Kit 的帮助下与 Solana 区块链互动，从而实现 40 多个协议操作，并且还在不断增加
- **[Spotify](https://github.com/varunneal/spotify-mcp)** - 此 MCP 允许 LLM 播放和使用 Spotify。
- **[Starwind UI](https://github.com/Boston343/starwind-ui-mcp/)** - 此 MCP 提供相关命令、文档和其他信息，以允许 LLM 充分利用 Starwind UI 的开源 Astro 组件。
- **[Stripe](https://github.com/atharvagupta2003/mcp-stripe)** - 此 MCP 允许与 Stripe 集成以处理付款、客户和退款。
- **[TMDB](https://github.com/Laksh-star/mcp-server-tmdb)** - 此 MCP 服务器与电影数据库 (TMDB) API 集成，以提供电影信息、搜索功能和推荐。
- **[Tavily search](https://github.com/RamXX/mcp-tavily)** - Tavily 的搜索和新闻 API 的 MCP 服务器，具有显式的站点包含/排除
- **[Terminal-Control](https://github.com/GongRzhe/terminal-controller-mcp)** - 一个 MCP 服务器，通过标准化界面实现安全的终端命令执行、目录导航和文件系统操作。
- **[Ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster)** - 通过 Ticketmaster Discovery API 搜索活动、场馆和景点
- **[Todoist](https://github.com/abhiz123/todoist-mcp-server)** - 与 Todoist 互动以管理您的任务。
- **[Typesense](https://github.com/suhail-ak-s/mcp-typesense-server)** - Model Context Protocol (MCP) 服务器实现，为 AI 模型提供对 Typesense 搜索功能的访问。此服务器使 LLM 能够发现、搜索和分析存储在 Typesense 集合中的数据。
- **[Travel Planner](https://github.com/GongRzhe/TRAVEL-PLANNER-MCP-Server)** - 旅行计划和行程管理服务器，集成了 Google Maps API，用于位置搜索、地点详细信息和路线计算。
- **[Unity Catalog](https://github.com/ognis1205/mcp-server-unitycatalog)** - 一个 MCP 服务器，使 LLM 能够与 Unity Catalog AI 互动，支持对 Unity Catalog 函数的 CRUD 操作，并将它们作为 MCP 工具执行。
- **[Unity3d Game Engine](https://github.com/CoderGamester/mcp-unity)** - 一个 MCP 服务器，使 LLM 能够与 Unity3d Game Engine 互动，支持访问各种 Unit 的编辑器引擎工具（例如，控制台日志、测试运行器日志、编辑器功能、层次结构状态等），并将它们作为 MCP 工具执行或收集为资源。
- **[Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)** - 使用 VegaLite 格式和渲染器从获取的数据生成可视化效果。
- **[Video Editor](https://github.com/burningion/video-editing-mcp)** - 一个 Model Context Protocol Server，用于使用 [Video Jungle](https://www.video-jungle.com/) 添加、编辑和搜索视频。
- **[Virtual location (Google Street View,etc.)](https://github.com/mfukushim/map-traveler-mcp)** - 集成 Google Map、Google Street View、PixAI、Stability.ai、ComfyUI API 和 Bluesky，以在 LLM 中提供虚拟位置模拟（用 Effect.ts 编写）
- **[VolcEngine TOS](https://github.com/dinghuazhou/sample-mcp-server-tos)** - 用于 VolcEngine TOS 的示例 MCP 服务器，可以灵活地从 TOS 获取对象。
- **[Wanaku MCP Router](https://github.com/wanaku-ai/wanaku/)** - Wanaku MCP Router 是一个基于 SSE 的 MCP 服务器，提供可扩展的路由引擎，允许将您的企业系统与 AI 代理集成。
- **[Webflow](https://github.com/kapilduraphe/webflow-mcp-server)** - 与 Webflow API 接口
- **[WildFly MCP](https://github.com/wildfly-extras/wildfly-mcp)** - WildFly MCP 服务器，使 LLM 能够与正在运行的 WildFly 服务器互动（检索指标、日志、调用操作等）。
- **[Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)** - 用于 Windows 系统上安全命令行互动的 MCP 服务器，支持对 PowerShell、CMD 和 Git Bash shell 的受控访问。
- **[World Bank data API](https://github.com/anshumax/world_bank_mcp_server)** - 一个服务器，用于获取世界银行作为其数据 API 的一部分提供的数据指标
- **[X (Twitter)](https://github.com/EnesCinr/twitter-mcp)** (by EnesCinr) - 与 twitter API 互动。发布推文并按查询搜索推文。
- **[X (Twitter)](https://github.com/vidhupv/x-mcp)** (by vidhupv) - 直接通过 Claude 聊天创建、管理和发布 X/Twitter 帖子。
- **[xcodebuild](https://github.com/ShenghaiWang/xcodebuild)**  - 🍎 构建 iOS Xcode 工作区/项目并将错误反馈给 llm。
- **[Xero-mcp-server](https://github.com/john-zhang-dev/xero-mcp)** - 使客户端能够与 Xero 系统互动，以简化会计、发票和业务运营。
- **[xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server)** 一个 MCP 服务器，支持使用自然语言查询从数据库中获取数据，由 XiyanSQL 作为文本到 SQL LLM 提供支持。
- **[XMind](https://github.com/apeyroux/mcp-xmind)** - 读取和搜索包含 XMind 文件的 XMind 目录。
- **[YouTube](https://github.com/ZubeidHendricks/youtube-mcp-server)** - 用于视频管理、短片创建和分析的综合 YouTube API 集成。

## 📚 框架

这些是使构建 MCP 服务器或客户端更容易的高级框架。

### 服务端框架

* **[EasyMCP](https://github.com/zcaceres/easy-mcp/)** (TypeScript)
- **[FastAPI to MCP auto generator](https://github.com/tadata-org/fastapi_mcp)** – 一个零配置工具，用于通过 **[Tadata](https://tadata.com/)** 自动将 FastAPI 端点公开为 MCP 工具
* **[FastMCP](https://github.com/punkpeye/fastmcp)** (TypeScript)
* **[Foxy Contexts](https://github.com/strowk/foxy-contexts)** – **[strowk](https://github.com/strowk)** 构建 Golang 中 MCP 服务器的库
* **[MCP-Framework](https://mcp-framework.com)** 使用 Typescript 优雅而快速地构建 MCP 服务器。附带一个 CLI，用于使用 `mcp create app` 创建您的项目。在 5 分钟内开始使用您的第一个服务器，由 **[Alex Andru](https://github.com/QuantGeekDev)** 提供
* **[Quarkus MCP Server SDK](https://github.com/quarkiverse/quarkus-mcp-server)** (Java)
* **[Template MCP Server](https://github.com/mcpdotdirect/template-mcp-server)** - 一个 CLI 工具，用于创建新的 Model Context Protocol 服务器项目，该项目具有 TypeScript 支持、双传输选项和可扩展结构

### 客户端框架

* **[codemirror-mcp](https://github.com/marimo-team/codemirror-mcp)** - CodeMirror 扩展，实现 Model Context Protocol (MCP)，用于资源提及和提示命令

## 📚 资源

关于 MCP 的其他资源。

- **[AiMCP](https://www.aimcp.info)** - **[Hekmon](https://github.com/hekmon8)** 提供的 MCP 客户端和服务器集合，用于查找合适的 mcp 工具
- **[Awesome Crypto MCP Servers by badkk](https://github.com/badkk/awesome-crypto-mcp-servers)** - **[Luke Fan](https://github.com/badkk)** 提供的 MCP 服务器精选列表
- **[Awesome MCP Servers by appcypher](https://github.com/appcypher/awesome-mcp-servers)** - **[Stephen Akinyemi](https://github.com/appcypher)** 提供的 MCP 服务器精选列表
- **[Awesome MCP Servers by punkpeye](https://github.com/punkpeye/awesome-mcp-servers)** (**[网站](https://glama.ai/mcp/servers)**) - **[Frank Fiegel](https://github.com/punkpeye)** 提供的 MCP 服务器精选列表
- **[Awesome MCP Servers by wong2](https://github.com/wong2/awesome-mcp-servers)** (**[网站](https://mcpservers.org)**) - **[wong2](https://github.com/wong2)** 提供的 MCP 服务器精选列表
- **[Discord Server](https://glama.ai/mcp/discord)** – **[Frank Fiegel](https://github.com/punkpeye)** 提供的专门用于 MCP 的社区 discord 服务器
- **[Discord Server (ModelContextProtocol)](https://discord.gg/jHEGxQu2a5)** – 与开发者联系，分享见解，并在一个活跃的 Discord 社区中协作处理项目，该社区致力于 Model Context Protocol，由 **[Alex Andru](https://github.com/QuantGeekDev)** 提供

- **[MCP Badges](https://github.com/mcpx-dev/mcp-badges)** – 由 **[Ironben](https://github.com/nanbingxyz)** 提供的快速突出显示您的 MCP 项目的清晰醒目的徽章
- **[MCP Servers Hub](https://github.com/apappascs/mcp-servers-hub)** (**[网站](https://mcp-servers-hub-website.pages.dev/)**) - **[apappascs](https://github.com/apappascs)** 提供的 MCP 服务器精选列表
- **[MCP X Community](https://x.com/i/communities/1861891349609603310)** – **[Xiaoyi](https://x.com/chxy)** 提供的 MCP 的 X 社区
- **[mcp-cli](https://github.com/wong2/mcp-cli)** - **[wong2](https://github.com/wong2)** 提供的 Model Context Protocol 的 CLI 检查器
- **[mcp-get](https://mcp-get.com)** - **[Michael Latman](https://github.com/michaellatman)** 提供的用于安装和管理 MCP 服务器的命令行工具
- **[mcp-guardian](https://github.com/eqtylab/mcp-guardian)** - **[EQTY Lab](https://eqtylab.io)** 提供的用于代理/管理 MCP 服务器控制的 GUI 应用程序 + 工具
- **[mcp-manager](https://github.com/zueai/mcp-manager)** - **[Zue](https://github.com/zueai)** 提供的用于为 Claude Desktop 安装和管理 MCP 服务器的简单 Web UI
- **[MCPHub](https://github.com/Jeamee/MCPHub-Desktop)** – **[Jeamee](https://github.com/jeamee)** 提供的用于发现、安装和管理 MCP 服务器的开源 MacOS 和 Windows GUI 桌面应用程序
- **[mcp.run](https://mcp.run)** - 用于安装和运行安全 + 便携式 MCP 服务器的托管注册表和控制面板。
- **[mcp-dockmaster](https://mcp-dockmaster.com)** - 用于为 Windows、Linux 和 MacOS 安装和管理 MCP 服务器的开源 UI。
- <img height="12" width="12" src="https://mkinf.io/favicon-lilac.png" alt="mkinf Logo" /> **[mkinf](https://mkinf.io)** - 用于加速 AI 代理工作流程的托管 MCP 服务器的开源注册表。
- **[Open-Sourced MCP Servers Directory](https://github.com/chatmcp/mcp-directory)** - **[mcpso](https://mcp.so)** 提供的 MCP 服务器精选列表
- <img height="12" width="12" src="https://opentools.com/favicon.ico" alt="OpenTools Logo" /> **[OpenTools](https://opentools.com)** - **[opentoolsteam](https://github.com/opentoolsteam)** 提供的用于查找、安装和构建 MCP 服务器的开放注册表
- **[PulseMCP](https://www.pulsemcp.com)** ([API](https://www.pulsemcp.com/api)) - **[Tadas Antanavicius](https://github.com/tadasant)**、**[Mike Coughlin](https://github.com/macoughl)** 和 **[Ravina Patel](https://github.com/ravinahp)** 提供的用于发现 MCP 服务器、客户端、文章和新闻的社区中心和每周新闻通讯
- **[r/mcp](https://www.reddit.com/r/mcp)** – **[Frank Fiegel](https://github.com/punkpeye)** 提供的专门用于 MCP 的 Reddit 社区
- **[r/modelcontextprotocol](https://www.reddit.com/r/modelcontextprotocol)** – Model Context Protocol 社区 Reddit 页面 - 讨论想法、获取问题答案、与志同道合的人建立联系并展示您的项目！由 **[Alex Andru](https://github.com/QuantGeekDev)** 提供


- **[Smithery](https://smithery.ai/)** - **[Henry Mao](https://github.com/calclavia)** 提供的用于查找适合您的 LLM 代理的工具的 MCP 服务器注册表
- **[Toolbase](https://gettoolbase.ai)** - **[gching](https://github.com/gching)** 提供的只需点击几下即可管理工具和 MCP 服务器的桌面应用程序 - 无需编码

## 🚀 快速入门

### 使用本仓库中的 MCP 服务器
基于 TypeScript 的服务器可直接使用 `npx` 运行。

例如，以下命令将启动 [Memory](src/memory) 服务器：
```sh
npx -y @modelcontextprotocol/server-memory
```

基于 Python 的服务器可使用 [`uvx`](https://docs.astral.sh/uv/concepts/tools/) 或 [`pip`](https://pypi.org/project/pip/) 直接运行，推荐使用 `uvx` 以获得更便捷的安装体验。

例如，以下命令将启动 [Git](src/git) 服务器：
```sh
# 使用 uvx
uvx mcp-server-git

# 使用 pip
pip install mcp-server-git
python -m mcp_server_git
```

请遵循[此处](https://docs.astral.sh/uv/getting-started/installation/)指引安装 `uv` / `uvx`，以及[此处](https://pip.pypa.io/en/stable/installation/)指引安装 `pip`。

### 配置 MCP 客户端
单独运行服务器本身并无太大实用价值，您需要将其配置到 MCP 客户端中使用。以下是 Claude Desktop 使用上述服务器的配置示例：

```json
{
  "mcpServers": {
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    }
  }
}
```

更多 Claude Desktop 作为 MCP 客户端的配置示例如下：

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/allowed/files"]
    },
    "git": {
      "command": "uvx",
      "args": ["mcp-server-git", "--repository", "path/to/git/repo"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "<YOUR_TOKEN>"
      }
    },
    "postgres": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-postgres", "postgresql://localhost/mydb"]
    }
  }
}
```

## 🛠️ 创建自定义服务器

有意构建专属 MCP 服务器？请访问[官方文档](https://modelcontextprotocol.io/introduction)获取完整指南、最佳实践和技术实现细节。

## 🤝 参与贡献

参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何为本仓库做出贡献。

## 🔒 安全声明

发现安全漏洞请参考 [SECURITY.md](SECURITY.md) 进行报告。

## 📜 许可协议

本项目采用 MIT 许可证，完整内容请参阅 [LICENSE](LICENSE) 文件。

## 💬 社区交流

- [GitHub 讨论区](https://github.com/orgs/modelcontextprotocol/discussions)

## ⭐ 支持我们

若 MCP 服务器对您有所帮助，欢迎为仓库点亮星标并贡献新的服务器或改进方案！

---

由 Anthropic 提供维护，与社区共建共享。Model Context Protocol 坚持开源理念，诚邀所有人贡献自己的服务器与改进方案！
