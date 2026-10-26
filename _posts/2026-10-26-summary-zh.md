---
layout: default
title: "Horizon Summary: 2026-10-26 (ZH)"
date: 2026-10-26
lang: zh
---

> 从 34 条内容中筛选出 6 条重要资讯。

---

**广告技术**
1. [Daily Mail 试水 GEO：把 AI 答案可见性做成品牌内容产品](#item-adtech-1) ⭐️ 8.0/10
2. [Stagwell 收购 Freestar：控股公司吞下供给端变现环节](#item-adtech-2) ⭐️ 7.0/10
3. [中期选举政治广告推高地方 CPM，抢占条款打乱区域广告主 Q4 投放](#item-adtech-3) ⭐️ 7.0/10
4. [Pinterest 开放程序化库存，Magnite 担任主 SSP](#item-adtech-4) ⭐️ 7.0/10

**广告实操教程**
1. [Ubersuggest 通过 MCP 连接器接入 Claude](#item-adtech-practical-1) ⭐️ 8.0/10

**经济观察**
1. [Doctorow：新闻网站&quot;浏览即同意&quot;条款应被定为非法](#item-economics-1) ⭐️ 7.0/10

---

## 广告技术

<a id="item-adtech-1"></a>
### [Daily Mail 试水 GEO：把 AI 答案可见性做成品牌内容产品](https://digiday.com/media/the-daily-mail-tests-geo-with-brands-ahead-of-ai-visibility-product/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 8.0/10

据 Digiday 报道，Daily Mail 正在美、英、澳三地运行 12–15 个生成式引擎优化（generative engine optimization, GEO）测试，计划明年初将「AI 可见性」正式产品化，作为新的品牌内容收入来源。SEO 与电商总监 Carly Steven 称，一个个人金融品牌客户的目标 prompt 可见性从约 50% 提升到近 75%。

rss · Media – Digiday · 10月26日 04:01

**「机制」** 测试流程是：先识别消费者研究某类产品时可能使用的 prompt，跨多个 AI 平台长期追踪这些 prompt 的答案，统计品牌被引用的情况及被引用来源的类型；由于 LLM 输出是概率性的，团队通过长时间纵向追踪来建立稳定基准（benchmark），再针对性制作定制品牌内容以提升引用率。机会评估有明确边界：若某话题的引用以政府或医疗网站为主，媒体品牌内容难以介入；只有当出版商占引用来源较大份额、而品牌可见性低时才出手。衡量商业影响是难点——AI 推荐常不产生直接点击，引荐分析（referral analytics）会漏掉后续搜索转化。Steven 将此比作户外广告的归因缺口，部分品牌改用站内「你如何听说我们」表单等购买后调查手段：她举例称某品牌 analytics 中 Claude 仅占 0.1% 引荐，但表单数据显示其贡献约 11% 转化。产品化还涉及商业、电商、原生广告与编辑团队协作，并需权衡是否解封特定内容访问以支持品牌可见性。Future（30+ 客户且有续约）、Ziff Davis、Forbes 也在构建类似的 GEO 咨询或监测产品。

**「启示」** 对广告平台工程师而言，这显示「AI 答案可见性」正成为出版商售卖的新广告品类，其效果度量依赖纵向引用追踪与调查式归因而非点击数据，意味着现有基于引荐和末次触点的衡量体系在这一渠道上系统性失真。值得关注的问题是：这种依赖概率性 LLM 输出的产品能否形成可复现、可规模化的投放与度量标准。

**标签**: `#generative engine optimization`, `#AI visibility`, `#publisher monetization`, `#attribution`, `#branded content`

---

<a id="item-adtech-2"></a>
### [Stagwell 收购 Freestar：控股公司吞下供给端变现环节](https://digiday.com/media-buying/stagwell-buys-freestar-putting-publisher-ad-sales-inside-a-holdco/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

据 Digiday 报道，独立控股集团 Stagwell 于 10 月 26 日宣布收购发布商变现公司 Freestar（服务 Fortune、Boston Globe Media 等数百家发布商），将其并入 Owned Media 部门。这是 Stagwell 供给侧布局的最新一步，交易条款未披露，目的是让控股集团直接掌握供给端库存与中间费用经济，同时引发买卖双方利益冲突与透明度的质疑。

rss · Digiday · 10月26日 14:30

**「机制」** 这笔交易的逻辑在于控股公司向上游供给路径（supply path）垂直整合。传统上，决定哪些发布商库存被打包出售给客户的是 SSP 和 Freestar 这类变现伙伴；收购后，Stagwell 可决定自家打包的库存组合，并把 Freestar 的供给直接接入其 7 月上线的自有市场 Stagwell Curate——该平台在库存进入竞价（bid）之前完成策展，Stagwell 的 AI 购买代理（agentic buying）直接插入其中。经济动因是 principal media（本金采买）模式让控股集团看清了中间费用的价值：与其向第三方 ad tech 支付不透明的费用，不如自己拥有执行层，把程序化差价留在集团内部。拥有 Freestar 还让 Stagwell 得以知晓发布商的实际成交价，压缩中间隐藏费用的空间。这与行业趋势一致：The Trade Desk 曾推 Open Path 直连发布商绕开 SSP，部分供应商也让买家跳过 TTD，各方都在争夺中间环节的费用归属——TTD 与 Publicis 的费用之争公开暴露了技术层的价值。风险在于：Freestar 现有的发布商客户如今要面对谈判桌对面（买方）拥有的变现伙伴，买卖双方的利益如何隔离成为透明度焦点，大型发布商明确表示尚未看到普遍性的发布商收益。

**「启示」** 对平台工程师而言，这标志控股集团正把供给端基础设施视为竞争壁垒：随着 agentic buying 系统落地，控股公司希望 AI 代理运行在自己拥有的供给栈上，未来客户会要求解释非 principal 媒体花费为何也要经过其自有（O&amp;O）栈。广告技术费用本身正成为 USP，交易和合作决策将越来越以费用经济性为基准。

**标签**: `#Stagwell`, `#Freestar`, `#principal media`, `#supply path`, `#ad tech fees`

---

<a id="item-adtech-3"></a>
### [中期选举政治广告推高地方 CPM，抢占条款打乱区域广告主 Q4 投放](https://digiday.com/media-buying/midterm-political-spending-throws-spanner-into-regional-advertiser-holiday-plans/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 报道，11 月中期选举前的政治广告投放显著推高了德州、威斯康星等战场州的电视与流媒体广告价格。据 AdImpact 数据，预计 120 亿美元政治支出中约 82 亿美元投向 TV/CTV；受访代理公司称德州线性电视 CPM 上涨 10%-15%（部分节目达 30%-50%），premium CTV CPM 从 34-35 美元涨至 43 美元，YouTube CPM 上涨约 20%。

rss · Digiday · 10月26日 04:01

**「机制」** 核心机制是地方电视台合同中的抢占条款（pre-emption）：当竞选团队或 PAC 出价更高时，媒体方可顶掉已预订的普通广告主，品牌只能获得补播库存（make-good），不直接损失预算但投放节奏被打乱、广告落在次优库存上。全国性广告主可暂时回避涨价的 DMA，而区域广告主受地理定向（geo-targeting）限制无法转移，冲击因此集中在地方层级。部分广告主转向 Netflix、Amazon Prime Video、Disney+等不接受政治广告的避风港平台，但涌入的需求又推高了这些本已处于价格顶端平台的 CPM。代理机构的应对包括按 DMA 撤出预算、升级到受政治通胀影响较小的全国性库存、提前锁量，或在选前彻底停投（go dark）——但 Q4 通常占广告主全年预算的 50%，停投代价极高，仅少数客户选择。此外，政治资金也在流向社交平台：据 AdsMom，10 月 11 日当周政治客户在 YouTube 和 Meta 上花费 1.49 亿美元，远高于 7 月末的 3400 万美元。

**「启示」** 对平台与算法工程师而言，这显示周期性政治需求冲击会沿地方线性→地方 CTV→premium 流媒体逐级传导价格，库存预留与定价机制需考虑政治买家的抢占优先级；同时也凸显禁政治广告的平台在选举季会获得可观溢出需求。

**标签**: `#political advertising`, `#CTV`, `#CPM inflation`, `#media buying`, `#preemption`

---

<a id="item-adtech-4"></a>
### [Pinterest 开放程序化库存，Magnite 担任主 SSP](https://www.adweek.com/programmatic/pinterest-opens-its-inventory-to-programmatic-buyers-with-magnite-as-its-main-pipe/) ⭐️ 7.0/10

Pinterest 宣布其展示与视频库存正式面向程序化购买全面开放（Programmatic Deals），覆盖北美、南美和亚太市场，此前已与代理商和品牌自今年年初开始测试。买家可在 Amazon Ads、Google Display &amp; Video 360、DeepIntent 和 Yahoo DSP 中通过私有市场（private marketplace, PMP）和优先交易（preferred deals）采买，Magnite 担任其主要 SSP 基础设施。此举正值 Pinterest 增长放缓：据原文，公司三季度营收增速指引为 13%-15%，低于二季度的 18%（二季度营收 11.8 亿美元，原文此处被付费墙截断）。

rss · AdWeek: AdFreak · 10月26日 07:00

**「机制」** 此前 Pinterest 的变现主要依赖直销与自助投放，如今改为通过 deal-based 通道接入外部需求：买家在原本就用于规划和采买媒介的 DSP 内，以 PMP 和 preferred deals 与 Pinterest 成交，Magnite 承担 SSP 管道角色，负责把库存接进各家 DSP。采用交易协议而非公开竞价，意味着 Pinterest 在引入 DSP 端增量预算的同时，仍保留对价格、准入广告主和库存分配的控制权；公司还表示正在测试程序化保量（programmatic guaranteed），即把预定式直销也搬进程序化管道。这一路径与社交平台普遍的&quot;围墙花园开放&quot;模式一致：不自建竞价市场，而是借成熟 SSP/DSP 管道获取需求。由于文章截断，拍卖动态、价格下限及衡量集成等细节未披露。

**「启示」** 对平台工程师而言，这印证了一个趋势：社交围墙花园正以 deal 通道为低摩擦入口接入程序化需求，SSP 管道的选型成为平台变现架构的关键决策。开放问题在于拍卖机制、底价策略与衡量集成如何设计——原文未给出答案，值得后续跟踪。

**标签**: `#Pinterest`, `#programmatic`, `#Magnite`, `#DSP`, `#private marketplace`

---

## 广告实操教程

<a id="item-adtech-practical-1"></a>
### [Ubersuggest 通过 MCP 连接器接入 Claude](https://neilpatel.com/blog/ubersuggest-inside-claude/) ⭐️ 8.0/10

Neil Patel 团队发布 Ubersuggest 在 Claude 官方连接器目录上线，基于开放标准 MCP（Model Context Protocol）实现。用户在对话中即可调用关键词研究、竞品分析、外链、站点审计等 SEO 数据，无需切换仪表盘或导出 CSV。据原文，该连接器背后是 58 个工具，数据权限沿用用户现有 Ubersuggest 套餐且为只读。

rss · Neil Patel · 10月26日 16:00

**「机制」** 机制上，MCP 让 LLM 在对话中途调用外部应用的工具接口，而非仅凭训练数据作答：Claude 直接查询 Ubersuggest 的数据索引（与 ubersuggest.com 同源），返回实际搜索量、CPC、关键词难度、竞品排名等实测值，而不是生成貌似合理的猜测。原文列出八大能力域：域名分析（流量估计、自然与付费排名词、流量价值）、竞品研究（关键词重叠与差距）、外链（锚文本分布、外链差距并按域名权重排序）、SERP 分析（排名页面指标与点击分布估计）、站点审计（爬取进度、技术问题与 Page Speed 数据）、排名追踪（位置变化并解释 Top 结果变化），以及 AI 搜索可见性（AI Search Visibility）——按 prompt 维度报告品牌在 AI 助手回答中的出现情况。文章给出 8 个起手 prompt（关键词差距、外链差距、审计分诊、排名下跌诊断等），并承认局限：连接器只读、受套餐限额约束、完整可视化报告仍需回仪表盘。文中价格对比（Ubersuggest $12/月起 vs Semrush $139.95/月、Ahrefs $129/月）为厂商自述，属推广性质而非实测结果。

**「启示」** 对平台与算法工程师而言，这显示 MCP 连接器正成为数据工具的新分发与查询层：对话界面取代仪表盘点击路径，且因 MCP 是开放标准，同一连接器可复用到其他 AI 客户端。同时 AI 搜索可见性作为按 prompt 计量的新指标，提示品牌在生成式回答中的呈现正成为可测量的优化目标。

**标签**: `#Claude连接器`, `#Ubersuggest`, `#关键词研究`, `#竞品分析`, `#AI搜索可见性`

---

## 经济观察

<a id="item-economics-1"></a>
### [Doctorow：新闻网站&quot;浏览即同意&quot;条款应被定为非法](https://pluralistic.net/2026/10/26/abandon-hope/) ⭐️ 7.0/10

Cory Doctorow 评论《洛杉矶时报》网站的拦截弹窗：声称读者点&quot;继续&quot;即同意约束性仲裁、放弃集体诉讼并接受其隐私政策。他认为这类未经协商的&quot;浏览即同意&quot;合同既不可执行也不道德，应像加州对待竞业禁止条款那样被立法明令禁止。

rss · Pluralistic: Daily links from Cory Doctorow · 10月26日 15:47

**「观点」** 作者以极强措辞谴责此举，称其&quot;震惊良心&quot;、是&quot;既非法又不道德&quot;的制度性衰败，好比&quot;主权公民&quot;对警察和法官念的单方面法律咒语。他强调这不是《洛杉矶时报》独有，而是正在全美媒体业蔓延的做法（Bloomberg 等亦如此），而报纸的天职是告知读者而非误导读者。

**「论证逻辑」** 作者的论证分五步：一、合同成立需真实同意，而该报隐私政策达 8,865 字、服务条款 7,103 字，按 Firefox 阅读模式估算各需约一小时读完，普通读者不可能&quot;知情同意&quot;。二、仲裁条款危害极大：他举迪士尼案——一名女子因餐厅隐瞒过敏原身亡，迪士尼竟主张其鳏夫注册 Disney+ 试用时已&quot;放弃&quot;起诉权（舆论压力下仅就该案退让）。三、该弹窗很可能违反加州消费者隐私法（CCPA），该法要求隐私弃权明确、知情且可随时撤回，并禁止&quot;暗黑模式&quot;。四、他亲历 LAT、纽约时报、华盛顿邮报在刊登其文章后才补发单方面苛刻合同，说明恶劣条款已成行业流行病。五、出路：加州已把竞业禁止条款从&quot;不可执行&quot;升级为&quot;违法&quot;，他主张将同一禁令扩展到仲裁与隐私条款，并制裁违规公司及其法务；个人层面可用广告拦截过滤器屏蔽弹窗、向加州隐私保护局投诉，或在 30 天内按条款发邮件退出仲裁。

**「概念解释」** 浏览包装合同（browsewrap）指网站宣称用户仅仅浏览页面即&quot;同意&quot;其条款，区别于需主动点击确认的点击包装（clickwrap）；约束性仲裁（binding arbitration）条款使用户丧失向法院起诉的权利，争议只能交由私人仲裁解决；集体诉讼弃权（class action waiver）则阻止众多消费者联合起诉。三者叠加，等于读者看一眼新闻就让渡了几乎全部法律救济途径，这正是作者称之为&quot;伪合同&quot;（bogus agreements）的原因。

**标签**: `#media industry`, `#contract law`, `#binding arbitration`, `#terms of service`, `#consumer protection`

---