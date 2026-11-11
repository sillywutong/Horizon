---
layout: default
title: "Horizon Summary: 2026-11-10 (ZH)"
date: 2026-11-10
lang: zh
---

> 从 26 条内容中筛选出 8 条重要资讯。

---

**广告技术**
1. [Agentic AI 对发布商的真正威胁：不是价格，而是能否进入竞价](#item-adtech-1) ⭐️ 9.0/10
2. [TIME 用 Kana AI 代理处理 RFP 与投放，销售仍由人负责](#item-adtech-2) ⭐️ 7.0/10
3. [Ogilvy 与 CAA 推出 Echo：用 AI 克隆名人拍广告](#item-adtech-3) ⭐️ 7.0/10
4. [OpenAI 测试 Business Hub：向品牌展示 ChatGPT 提及与点击数据](#item-adtech-4) ⭐️ 7.0/10
5. [谷歌 AI 退出控制捆绑设计令出版商难以抉择](#item-adtech-5) ⭐️ 7.0/10
6. [IETF 政策令牌：出版商 AI 训练退出机制解析](#item-adtech-6) ⭐️ 7.0/10

**广告实操教程**
1. [Ubersuggest 与 Moz SEO 工具对比：功能、定价与组合用法](#item-adtech-practical-1) ⭐️ 7.0/10

**经济观察**
1. [特朗普主义不可逆：美国霸权已终结](#item-economics-1) ⭐️ 7.0/10

---

## 广告技术

<a id="item-adtech-1"></a>
### [Agentic AI 对发布商的真正威胁：不是价格，而是能否进入竞价](https://www.adexchanger.com/the-sell-sider/publishers-agentic-ai-isnt-about-pricing-but-whether-you-get-any-bids-at-all/) ⭐️ 9.0/10

AdExchanger 客座专栏（作者 Jonathon Shaevitz，GrowthCode）认为，agentic AI 对发布商的紧迫威胁并非价格压力，而是基于身份的库存评估可能让发布商在竞价开始前就被排除。文章援引 IAB 对 360 名数字视频买家的调查（2026 年 2-3 月）：96% 认为 agentic AI 在程序化中有角色，63% 预期其作为优化出价的层面，但仅 28% 已用于交易执行。并以 2026 年微软将约 7 亿至 12 亿美元媒介业务转交 Publicis、Publicis 收购 LiveRamp（FTC 于 10 月附 5 年中立令批准）为例，说明买家已在既有基础设施上部署决策型 agents。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月9日 05:35

**「机制」** 作者把 agentic 逻辑拆成两半：决策层与执行层。执行层（自动谈判、下单）仍受人工审批门槛限制（40% 买家要求人类批准），且 IAB Tech Lab 的 Katsur 预测会有&quot;多次错误的开始&quot;；但决策层已在渗透，年花费 5000 万美元以上的视频买家中 63% 已用或计划用 agents 做库存发现与评估（小买家仅 30%）。关键论点是与 2017-2019 年转向第一价格拍卖（first-price auction）的类比：Google Ad Manager 2019 年 3 月宣布、四个月内完成切换，bid shading（出价遮蔽）随即通过既有集成在 SSP/DSP 间扩散，无需新标准；发布商只能事后从成交价报告里感知影响。不同之处在于：bid shading 优化的是&quot;已决定出价的价格&quot;，而身份驱动的 agents 决定的是&quot;哪些库存值得出价&quot;——评估发生在竞价上游，未通过评估的库存根本不会进入拍卖。文章建议发布商做三件不依赖标准落地的事：建立跨站点稳定标识符、结构化第一方属性让 bid request 携带清晰上下文、以书面合同明确授权数据访问（因为 bid request 信号对未中标的 bidder 也可见，授权是合同问题而非纯技术问题）。这些动作同时能提升当前拍卖中的匹配率与评估表现。

**「背景」** 文章的机制类比基于真实历史：2017 年起交易所转向第一价格拍卖，bid shading 作为避免在第一价格下多付的机器学习策略，数月内沿既有集成普及，被视为&quot;新购买逻辑无需新管道即可重塑拍卖&quot;的先例。作者还指出以往多次&quot;迫在眉睫&quot;的行业变迁（移动超越桌面用了约 8 年、cookie 弃用从 2020 年宣布到 2024 年放弃）都卡在集成成本分摊上，而 agentic 的特殊性在于买方已经付过这笔集成账单。

**「启示」** 对平台与算法工程师而言，竞争焦点正从拍卖内的出价优化上移到拍卖前的库存筛选：身份解析与 bid request 信号质量将决定库存是否进入考虑集。发布商侧可量化的准备工作（稳定 ID、结构化上下文、数据授权条款）现在就影响填充与匹配，而非等到自动交易标准成熟。

**标签**: `#agentic buying`, `#identity resolution`, `#auction dynamics`, `#first-price auctions`, `#bid shading`

---

<a id="item-adtech-2"></a>
### [TIME 用 Kana AI 代理处理 RFP 与投放，销售仍由人负责](https://www.adexchanger.com/ai/times-ai-agents-do-the-coordinating-and-its-sellers-still-do-the-selling/) ⭐️ 7.0/10

AdExchanger 报道，TIME 部署了广告技术初创公司 Kana 的两个 AI 代理：一个协助销售团队读取 RFP 并起草提案，另一个监控在线投放活动并推荐补救措施。TIME COO Mark Howard 称，这让销售人员从繁琐的协调工作中解放出来，但关系销售仍保留在人类手中。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月9日 06:00

**「机制」** Kana 的销售代理建立在一个知识图谱之上，该图谱汇聚了来自 Salesforce CRM、订单管理系统（OMS）以及直客和程序化广告服务器的数据，并引入了实时的广告投放数据——Vaidya 指出这对售前工具而言并不常见，因为这类数据通常属于广告运营用于事后分析的范畴。该代理能主动将历史数据和类似广告主的信息转化为提案素材，甚至为尚未合作的广告主生成新提案。另一个代理则面向广告运营，监控活动是否交付不足或节奏不当，并直接给出调整 trafficking、pacing 或预算等修复建议，以避免 make-good。尽管技术上可通过 MCP 服务器让发布商的代理与广告主的代理直接对接，TIME 明确表示不打算采用这种 agent-to-agent 的销售模式。

**「背景」** Kana 由 Krux 联合创始人 Tom Chavez 和 Vivek Vaidya 创立，Krux 是 Salesforce 约十年前收购的 DMP。两人于 2019 年成立了 super\{set\}，一家非传统风投公司，专注于联合创办和孵化数据与 AI 初创企业，其投资组合还包括隐私平台 Ketch 和数据洁净室提供商 Habu（后者于 2024 年被 LiveRamp 以 2 亿美元收购）。

**「启示」** 这一部署展示了 agentic AI 在发布商广告运营中的具体落地路径：将协调、数据整合和初步分析等操作性工作交给代理，而将关系建立和创意销售留给人类。尽管 TIME 声称生产力显著提升，但结果均为定性描述，缺乏量化数据支撑，其长期效果仍需观察。

**标签**: `#agentic AI`, `#publisher ad sales`, `#TIME`, `#campaign pacing`, `#Kana`

---

<a id="item-adtech-3"></a>
### [Ogilvy 与 CAA 推出 Echo：用 AI 克隆名人拍广告](https://digiday.com/marketing/ogilvy-and-caa-launch-partnership-to-clone-celebrity-talent-for-ai-ads/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 报道，WPP 旗下 Ogilvy 与经纪公司 CAA 合作推出 Echo 系统，让品牌在广告中使用 CAA 旗下艺人、运动员和创作者的 AI 数字替身，素材来自 CAA 的 Vault 扫描库。Ogilvy 称单素材成本可降低 65-75%，试点 campaign 预计年底上线，Terry Crews 等艺人已加入。

rss · Marketing – Digiday · 11月9日 15:00

**「机制」** Vault 由 Veritone 四年前为 CAA 建造，用 204 台相机捕捉艺人的声音、面部表情、肢体语言和步态，每 3-5 年更新一次，此前用于电影减龄和后期修复。现在 Ogilvy 可将这些授权素材接入 WPP Open，用于分镜、样片直至最终创意资产；授权谈判流程与传统拍摄相同，但产出更快、素材更多。治理上，艺人拥有其数字肖像，可挑选批准的品牌与市场并终审所有素材，成品加水印标明“AI 生成且经本人批准”，以规避 deepfake 争议并提前应对欧盟等地的 AI 监管。已有先例：Coca-Cola/Snickers 今年用 José Mourinho 的数字克隆投放 campaign，五年前 Shah Rukh Khan 排灯节项目则是 Echo 的原型。初期主要用于社交素材，运动员因赛季档期受限被视为重点场景，也有助于品牌低成本启用 B 级运动员。风险在于消费者信任：YouGov 数据显示 49%英国受访者对 AI 演员广告持负面态度，92%认为 AI 内容降低了网络信息可信度；且成本节省数字来自 Ogilvy 单方面说法，尚无实测 campaign 效果。

**「背景」** CAA 的 The Vault 并非新建：Veritone 四年前为其建成，204 台相机的全身扫描装置此前主要用于影视减龄和后期修复（tool-1-1、tool-1-2）。此次与 Ogilvy 的合作是这套素材首次被系统化地引入广告创意生产。文中提到的 Mourinho 数字分身也已有先例：2024 年欧洲杯期间 Snickers 推出的个性化视频工具让用户收到 AI 生成的 Mourinho 训话片段（tool-2-2、tool-2-1），Echo 相当于把这类一次性案例变为可规模化复用的基础设施。

**「启示」** 这意味着 AI 创意生产正与名人肖像授权基础设施打通，带水印的 AI 生成名人素材可能规模化进入社交与效果广告库存，平台在 AI 内容标注和审核上的配套能力会更受关注；但关键的成本与效果声明均出自代理方，真实增益尚待验证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://briefly.co/anchor/Marketing/story/ogilvy-and-caa-launch-partnership-to-clone-celebrity-talent-for-ai-ads">Key takeaways: Ogilvy and CAA launch partnership to clone ...</a></li>
<li><a href="https://www.vanityfair.com/story/caa-vault-actors-ai-replica">Inside CAA’s Secret AI “Vault,” Where Actors Can Live Forever ...</a></li>
<li><a href="https://musebyclios.com/sports/how-snickers-cloned-jose-mourinho-and-won-2-grand-clios/">How Snickers Cloned José Mourinho and Won... | Muse by Clios</a></li>
<li><a href="https://www.marketing-beat.co.uk/2024/06/26/snickers-jose-mourinho-ai/">Snickers clones José Mourinho for Euros campaign</a></li>

</ul>
</details>

**标签**: `#Ogilvy`, `#CAA`, `#AI creative`, `#digital likeness`, `#celebrity endorsement`

---

<a id="item-adtech-4"></a>
### [OpenAI 测试 Business Hub：向品牌展示 ChatGPT 提及与点击数据](https://digiday.com/marketing/chatgpt-is-about-to-show-brands-their-mention-count/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

据 Digiday 报道，OpenAI 正在测试一款嵌入未发布的 Business Hub 中的分析仪表盘，可向品牌展示其在 ChatGPT 回答中的每日提及次数（impressions）和导向其网站的点击数。企业需&quot;认领（claim）&quot;自身业务（如通过连接 Shopify 店铺验证身份）后解锁该功能，并同时获得一个基于企业提交信息回答用户问题的 business agent。

rss · Marketing – Digiday · 11月9日 05:01

**「机制」** 该仪表盘按天记录曝光与点击并绘制成图表，但相比 Google Search Console 明显收窄：不展示具体 prompt、不提供用户数据、无竞品排名。这与 GEO（generative engine optimization）供应商（如 Profound、Adthena）形成错位互补——后者靠大规模跑 prompt 模拟品牌可见度，却没有 OpenAI 的第一方真实计数；Marketplace Pulse 创始人 Kaziukėnas 预计两者将并存，外部工具追踪 prompt、OpenAI 数据用于验证 GEO 策略是否奏效。更关键的是变现逻辑：尽管仪表盘只涉及自然（organic）回答，但一旦可见度变成每日可见的数字，品牌就有动力提升它，而 OpenAI 恰好出售紧邻回答的赞助位。这复刻了 Google 的路径——Business Profile 与 Search Console 先提供自然可见性数据，再为广告销售铺路。OpenAI 广告业务 2026 年 2 月在美测试，9 月号称年化收入达 10 亿美元（不足 200 天），10 月称广告主超 10 万、覆盖 89 国；Business Hub 补上自然侧数据，可直接触达尚未投放的认领企业。

**「启示」** 第一方自然可见性数据正在成为 AI 平台广告获客的漏斗入口，OpenAI 此举可能压缩纯监测型 GEO 厂商的空间，同时让&quot;AI 回答中的品牌曝光&quot;成为可每日追踪、进而可付费优化的指标。对平台工程师而言，值得观察的开放问题是：在不暴露 prompt 与用户数据的前提下，平台方还能提供多少可操作的测量粒度。

**标签**: `#OpenAI`, `#ChatGPT ads`, `#generative engine optimization`, `#AI measurement`, `#organic visibility`

---

<a id="item-adtech-5"></a>
### [谷歌 AI 退出控制捆绑设计令出版商难以抉择](https://digiday.com/media/as-publishers-await-click-data-googles-ai-visibility-push-complicates-the-opt-out-decision/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 报道，在英国 CMA 首个行为要求下，谷歌推出 Search Console 控制项，允许出版商将内容排除在其 AI 功能之外，并于 8 月 31 日面向全球开放，页面级控制须在 2027 年 3 月 3 日前到位。但由于控制为捆绑式、且谷歌只给展示数据而扣留点击数据，出版商在 AI 可见性与内容控制权之间难以决策。

rss · Media – Digiday · 11月9日 05:01

**「机制」** 机制核心在于谷歌把 opt-out 做成全有或全无：出版商无法单独退出 AI Overviews、AI Mode 或 Discover 摘要，只能整体退出。谷歌目前仅共享展示数据（impressions），却扣留能验证 AI 露出是否带来真实点击的点击数据——按 CMA 要求须于 12 月 3 日前向英国出版商提供，是否全球同步未确认。与此同时，谷歌升级 AI 界面让链接更频繁、更显眼，新增文章轮播与相关报道链接，并称 Preferred Sources 今年增长七倍。SPUR 创始人 Buttle 指出，谷歌的策略是以 Discover 等 AI 表面的导流作为价值交换，让出版商&quot;自愿&quot;留下而非按次付费，并将 Discover 摘要与其他 AI 功能的退出捆绑以抬高退出成本。出版商还顾虑二阶效应：即使无人点击，品牌名称出现在 AI 答案顶部仍有可见性价值，且退出站点可能从 AI Overviews 内的 Top Stories 轮播中消失（谷歌未说明）。Daily Mail、Economist 等均表示在数据到位前暂缓试验，PPA 则正游说 CMA 要求按功能拆分控制。

**「背景」** 这一退出机制源于英国竞争与市场管理局（CMA）2026 年 6 月对 Google 搜索服务施加的首个行为要求（conduct requirement），这是自 2025 年 10 月 Google 被认定具有战略市场地位（strategic market status）后，CMA 依据数字市场竞争新规首次动用的监管工具。该要求允许出版商选择退出其内容被用于 Google 搜索的 AI 功能，被称为全球首例此类监管干预。

**「启示」** 这是平台通过产品捆绑与选择性数据披露重塑内容价值交换谈判地位的典型案例。点击数据披露后出版商的实际退出率，以及 CMA 是否强制拆分控制，将检验监管能在多大程度上约束 AI 搜索表面的设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gov.uk/find-digital-markets-measures/google-search-publisher-conduct-requirement">Google search publisher conduct requirement - GOV.UK</a></li>
<li><a href="https://www.gov.uk/government/news/cma-secures-fairer-deal-for-publishers-and-improves-google-search-services-in-uk">CMA secures fairer deal for publishers and improves Google ...</a></li>
<li><a href="https://www.techtimes.com/articles/317979/20260608/google-ai-overviews-opt-out-hits-search-console-gemini-excluded-publishers-weigh-trade-offs.htm">Google AI Overviews Opt-Out Hits Search Console: Gemini ...</a></li>

</ul>
</details>

**标签**: `#Google`, `#AI Overviews`, `#publisher opt-out`, `#CMA`, `#AI search`

---

<a id="item-adtech-6"></a>
### [IETF 政策令牌：出版商 AI 训练退出机制解析](https://digiday.com/media/wtf-is-the-ai-training-opt-out-policy-token/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 解释称，Anthropic、Google、Microsoft 和 OpenAI 已同意支持一项新的 IETF 标准，允许出版商通过 robots.txt 文件中的“政策令牌”选择退出 AI 训练。该标准由 Anthropic 技术负责人 Kevin Kelley 于 10 月 30 日提交，旨在让出版商用几行文本表达内容使用偏好，而非逐一管理每个爬虫。尽管主要 AI 公司承诺支持，但批评者认为这只是无法执行的“橱窗装饰”，因为数据显示爬虫几乎不检查 robots.txt 文件。

rss · Media – Digiday · 11月9日 05:01

**「机制」** 该机制的核心是在现有 robots.txt 协议基础上扩展一个专用政策令牌。出版商可在文件中添加\`User-Agent: \_\_usage\_ai-training\`，随后使用\`disallow\`或\`allow\`指令来声明是否允许内容用于 AI 训练，并可设置例外（如允许抓取新闻资料袋）。这取代了以往需为每个 AI 爬虫单独设置规则的繁琐方式。然而，其系统层面存在根本性缺陷：robots.txt 本质是自愿遵守的约定，缺乏技术强制力。ScalePost 数据显示，四大公司爬虫过去 30 天发出约 10 亿次请求，仅 0.15%指向 robots.txt 文件。此外，该标准不涵盖 AI 推理（inference）阶段的实时内容检索，也无法阻止 AI 公司通过 Common Crawl 等第三方数据源获取内容。微软明确警告，退出 AI 接地（grounding）将降低品牌在 AI 体验中的可见度，而 Google 的 Search 生成式 AI 控制则让出版商面临流量与保护的两难。

**「背景」** 该提案源于出版商与 AI 公司间持续的内容 scraping 冲突。此前，出版商已尝试通过 robots.txt 单独屏蔽 AI 爬虫、提起版权诉讼及谈判许可协议来维护权益。Google 在 2023 年推出的 Google-Extended 是重要先例，允许出版商限制内容用于 Gemini 模型训练。Microsoft 现有的 NoArchive 和 NoCache 偏好也将于 2027 年 2 月 1 日被新政策令牌取代。IETF 的 AI Preferences（AIPREF）工作组本应是公开讨论平台，但四大公司抢先宣布支持未经审议的草案，被 SPUR 联盟技术负责人 Alex Springer 批评为“单边强加事实标准”，违背了 IETF 的共识驱动原则。

**「启示」** 对广告平台工程师而言，此事件揭示了内容控制权与 AI 数据需求间的深层矛盾。政策令牌虽是标准化尝试，但默认“选择退出”（opt-out）而非“选择加入”（opt-in）的立场可能合法化未经许可的内容使用。平台竞争将围绕数据获取的合规性与可见性展开，出版商在保护内容与维持 AI 搜索/助手曝光度间面临艰难权衡。工程师需关注此类标准如何影响爬虫行为、数据管道及与内容提供方的关系，同时警惕无法执行的标准可能带来的虚假安全感。

**标签**: `#AI training opt-out`, `#robots.txt`, `#publishers`, `#IETF AIPREF`, `#AI scraping`

---

## 广告实操教程

<a id="item-adtech-practical-1"></a>
### [Ubersuggest 与 Moz SEO 工具对比：功能、定价与组合用法](https://neilpatel.com/blog/ubersuggest-vs-moz/) ⭐️ 7.0/10

Neil Patel 在其博客对比了自有产品 Ubersuggest 与 Moz，覆盖功能、定价与适用场景：Ubersuggest 起价 29 美元/月（含 290 美元起的终身版），Moz Pro 起价 99 美元/月，作者称 Ubersuggest 比 Moz 便宜 240%以上。文章建议按预算和需求选型，并提出可组合使用两款工具的 Chrome 扩展进行关键词与竞品研究。

rss · Neil Patel · 11月9日 20:00

**「机制」** 两者均为 SEO 工具链产品，核心流程是从种子词或域名出发，抓取关键词建议、搜索量、CPC 与竞争度，再做排名追踪、网站审计、内容与外链分析。值得注意的数据依赖关系是：Ubersuggest 的外链指标（domain/page authority、spam score）通过 Moz API 获取，即其权威度数据源自 Moz 索引而非自建，这使其在压低价格的同时复用成熟指标。差异化上，Ubersuggest 侧重关键词研究与选题，附带 AI 内容生成和多语言支持；Moz 侧重技术 SEO，追踪 Google 之外的多个搜索引擎（Bing、Yahoo、DuckDuckGo、Yandex、Baidu 等），并通过单独售卖的 Moz Local（14 美元/月起）覆盖本地 SEO，还开放 API。组合工作流上，作者建议先用 Ubersuggest 扩展找关键词与流量领先的竞品，再用 Mozbar（作者称其安装量超 80 万）检查目标站点的权威度、元信息与外链。需注意这是作者为自家产品撰写的对比，无实测数据支撑。

**「启示」** 对广告技术工程师而言，这篇的营销价值大于技术价值：它展示了 Moz 这类权威度指标（DA/PA）通过 API 已成为第三方工具的数据底座，说明行业指标授权是一种可行的数据分发模式。由于是厂商自我对比，其价格优势结论应视为营销主张而非客观评测。

**标签**: `#SEO工具`, `#关键词研究`, `#Ubersuggest`, `#Moz`, `#竞品分析`

---

## 经济观察

<a id="item-economics-1"></a>
### [特朗普主义不可逆：美国霸权已终结](https://pluralistic.net/2026/11/09/brunch-is-canceled-forever/) ⭐️ 7.0/10

作者科里·多克托罗（Cory Doctorow）认为，特朗普的第二个任期通过“2025 计划”（Project 2025）对美国国家能力造成了不可逆的破坏，使美国永久失去了作为全球金融体系主导者、技术平台提供者和安全保障者的地位。因此，加拿大等盟友不应幻想回到特朗普之前的旧秩序，而应转向真正的国内产业政策和基于具体议题的“小型多边主义”（minilateralism）。

rss · Pluralistic: Daily links from Cory Doctorow · 11月9日 08:12

**「观点」** 多克托罗坚决主张“特朗普主义”（Trumpism）无法被撤销，旧的美国霸权秩序已经永久破裂。他批评加拿大总理马克·卡尼（Mark Carney）言行不一：尽管卡尼宣称旧秩序已经“断裂”，却仅采取报复性关税这一象征性回应，而未配合大规模的国内工业投资来重建制造业。多克托罗认为，这种应对方式反映了自由派幻想“回到过去”的心态，而非接受现实、建立新的经济主权。

**「论证逻辑」** 多克托罗的推理基于几个关键前提：首先，与特朗普第一任期不同，第二任期有“2025 计划”的系统支持，该计划旨在进行无法逆转的结构性改革；其次，这些改革已经造成了实质性破坏，包括赶走数十万专业公务员、终止长期科研项目、摧毁大学研究能力、恐吓移民导致人才外流，以及将巨额财富转移给寡头阶层；第三，这些损害涉及人员、信任和基础设施，无法通过简单的人事更替来修复。因此，即便未来政府更迭，美国也不再具备担任全球领导者的能力和信誉。多克托罗进一步指出，“武器化相互依赖”（weaponized interdependence）的前提是其他国家依赖美国，但现在各国都在努力摆脱这种依赖，因此美国已无法再通过美元、云计算或安全承诺来施加影响。

**「概念解释」** 文中关键概念包括：1\) 武器化相互依赖（weaponized interdependence）：指美国利用其在全球网络（如美元结算、云计算服务、海底光缆）中的中心地位，通过切断服务来胁迫他国；多克托罗认为这种策略已失效，因为各国正在“去风险化”并寻找替代方案。2\) 小型多边主义（minilateralism）：指国家基于特定目标组建临时、有限联盟，而非依赖固定的大型盟友体系；这是卡尼所主张但未能贯彻的策略。3\) 友岸外包（friendshoring）：拜登政府提出的将关键供应链转移至“友好国家”的策略，但多克托罗认为这要求高度的长期信任，而当前国际关系已不具备这种稳定性。

**标签**: `#geopolitical economy`, `#weaponized interdependence`, `#US hegemony`, `#industrial policy`, `#trade and tariffs`

---