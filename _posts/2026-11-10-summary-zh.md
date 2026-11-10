---
layout: default
title: "Horizon Summary: 2026-11-10 (ZH)"
date: 2026-11-10
lang: zh
---

> 从 35 条内容中筛选出 12 条重要资讯。

---

**广告技术**
1. [OpenAI 上线 Business Hub：免费商务智能体与付费广告共用同一智能体](#item-adtech-1) ⭐️ 8.0/10
2. [FTC 指控亚马逊操纵广告拍卖，自动化广告信任问题凸显](#item-adtech-2) ⭐️ 8.0/10
3. [Reddit 联手 Qloo 用实体关联数据强化预测性定向](#item-adtech-3) ⭐️ 7.0/10
4. [Shopify 扩展 Campaign Autopilot：按成交付费的代理式广告](#item-adtech-4) ⭐️ 7.0/10
5. [OpenAI 广告业务五原则：用户信任优先，广告主价值居末](#item-adtech-5) ⭐️ 7.0/10
6. [Trusted Server：广告调用服务端化的隐私权衡](#item-adtech-6) ⭐️ 7.0/10

**推荐系统**
1. [Meta Your algorithm：自然语言偏好注入 Feed/Reels 推荐全漏斗](#item-recsys-1) ⭐️ 7.0/10
2. [Meta TLX：面向生产级 ML 的硬件原生 GPU 编译器扩展](#item-recsys-2) ⭐️ 6.0/10

**AI 深度解读**
1. [从全注意力到混合注意力：LLM 架构的效率转向](#item-ai-deepdive-1) ⭐️ 6.0/10

**LLM 与 Agent**
1. [Latent Space 实测 Naive-N0.5-Flash：2100 tok/s 的编码模型表现如何](#item-ai-agentic-1) ⭐️ 7.0/10
2. [Claude Fable 5.2 / Mythos 5.2 发布：单价降 20% 但单任务成本反升](#item-ai-agentic-2) ⭐️ 7.0/10

**经济观察**
1. [欧盟应为边境 IT 系统失败公开追责承包商](#item-economics-1) ⭐️ 8.0/10

---

## 广告技术

<a id="item-adtech-1"></a>
### [OpenAI 上线 Business Hub：免费商务智能体与付费广告共用同一智能体](https://digiday.com/marketing/openais-new-business-agents-give-brands-a-free-way-into-the-conversation-its-also-selling-as-an-ad/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 8.0/10

OpenAI 上线 Business Hub：商家可认领 ChatGPT 资料页、验证并提交产品与公司信息，美国电商与在线服务商家还可免费发布“商务智能体”（business agent）——一个单独标注、代表品牌与用户对话的聊天入口。OpenAI 货币化副总裁 Benji Shomair 确认，这是 Digiday 9 月报道的付费广告“sponsored agent”的自然（organic）版本，两种形态背后是同一个智能体。

rss · Marketing – Digiday · 11月10日 18:00

**「机制」** 品牌由此有两条进入同一对话的路径：自然推荐免费，付费 placement 收费。智能体由 OpenAI 用商家提交的指令和产品 feed 构建，不允许商家自带（“We aren&\#x27;t allowing folks to bring their own agents”）；用户准备购买时被引导至品牌官网完成交易，对话内容留在 OpenAI——品牌拿不到 transcript，只能看到对话主题（themes）。配套的 Insights 仪表盘（beta）提供 mentions、views、website clicks 和 discovery topics，但无 share of voice；统计口径上，本地商家的提及以 ChatGPT 展示该地点结果为准，在线商家以引用其网站为准，仅提品牌名不计入，点击只计链接点击而非完成访问或购买，低量级数据出于隐私可能 withheld，图表窗口为 7 或 28 天（据一位有权限的广告高管）。Shomair 称赞助智能体早期测试“效果 promising”，尤其对话深度，但未披露付费版的竞价与购买机制。

**「启示」** 第一手 mentions 数据的开放，直接冲击靠 Google 搜索数据和流量估算做近似的第三方 AI 可见度工具（Peec.AI、Otterly.AI、Semrush），广告主首次有了校验其估算的基准，不过受访者指出 ChatGPT 只是多个 AI 平台之一，第三方需求仍会存在。对平台工程师而言，“自然与付费共用同一智能体、认领资料不影响自然出现频率”的边界能否守住，以及付费版尚未披露的投放机制，是值得跟踪的开放问题。

**标签**: `#OpenAI`, `#ChatGPT`, `#conversational ads`, `#sponsored agents`, `#AI visibility measurement`

---

<a id="item-adtech-2"></a>
### [FTC 指控亚马逊操纵广告拍卖，自动化广告信任问题凸显](https://digiday.com/media-buying/ad-tech-briefing-amazons-auction-trial-puts-agentic-advertisings-trust-problem-in-focus/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 8.0/10

Digiday 报道，FTC 与 22 州总检察长的诉讼披露了针对亚马逊的新细节，指控其在 Sponsored Products 拍卖中秘密加价：普通购物日最高 50%、大型零售活动最高 250%，2022 年假日季额外产生 8700 万美元收入。亚马逊否认指控，诉讼仍在进行。文章借此引出核心问题：亚马逊广告季度收入已接近 200 亿美元，正大力推广 Ads Agent 等 agentic（代理式）自动化产品，但广告主无法独立验证其现有拍卖的定价方式。

rss · Digiday · 11月10日 05:01

**「机制」** 亚马逊对外将 Sponsored Products 描述为广义二价拍卖（generalized second-price auction），即广告主支付由竞争出价而非自身最高出价决定；FTC 指控其引入了未披露的保留价（reserve price）机制，在没有相应竞争的情况下抬高出价，使实际效果趋近一价拍卖（first-price auction）。据指控，2021 年假日季平均 CPC 上涨 20%，部分广告主涨幅超 200%，且高管曾考虑用保留价弥补 4000 万美元的收入缺口；亚马逊则辩称保留价反映广告位价值、本身并不违法。关键问题在于：广告主只能看到自己付了多少钱，无法验证价格是如何算出的。与此同时，亚马逊在 unBoxed 大会推出 Ads Agent 和 Full-Funnel Campaigns，广告主只需设定目标、商品、素材和预算，定向、分配与优化全部交给平台；公司自报 beta 测试带来最高 67%的长期 ROAS 提升和 29%的新客成本下降（为公司披露数据，未经独立验证）。文章类比 Google 广告技术反垄断案——联邦法院已认定其非法垄断发布商广告服务器与广告交易平台市场——指出共性在于平台对广告基础设施的控制使客户难以审查交易机制。

**「启示」** 平台要求的自动化授权越多，拍卖与决策的可验证性就越成为竞争要素和监管焦点。对工程师而言，未披露的定价机制调整即便不违法，也会在平台转向 agentic 购买时放大信任与审计需求——可解释的计费逻辑可能成为广告主是否让渡控制权的前提。

**标签**: `#Amazon`, `#FTC`, `#auction mechanics`, `#reserve prices`, `#agentic buying`

---

<a id="item-adtech-3"></a>
### [Reddit 联手 Qloo 用实体关联数据强化预测性定向](https://www.adexchanger.com/marketers/reddit-taps-qloo-to-strengthen-its-predictive-targeting/) ⭐️ 7.0/10

Reddit 宣布与预测推断公司 Qloo 合作，接入其超过 10 年的跨领域兴趣关联数据，用于改进广告定向。双方称，这能让 Reddit 在不依赖用户个人数据或互动历史的情况下，实现更具相关性且跨品类的上下文定向（contextual targeting），并加快新广告主 campaign 的优化速度。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月10日 14:00

**「机制」** Qloo 的核心是一个实体关联知识图谱：它基于 TasteDive（2019 年收购的推荐平台）评论、Wikidata 元数据及第三方授权数据，对餐厅、音乐、时尚等实体按共享属性分类并计算相似度——例如一家意式餐厅可按“北欧极简风”氛围关联到审美相近的时尚品牌。Reddit 以往在 subreddit 场景做上下文定向时只能投放与帖子直接相关的广告（咖啡机帖子配咖啡机广告），接入 Qloo 后可做非显而易见的跨品类推断（咖啡机买家往往也需要放置它的桌子，于是投高脚桌广告）。在优化侧，Reddit 工程高级总监称，过去新广告主 campaign 需积累数天到数周的用户互动数据才能优化，现在可针对 Qloo 提供的信号直接优化，或为广告主找到近似代理（proxy）、导入其既有数据，几乎即时起效。隐私属性上，这些相关性在实体层面而非用户层面计算，无需查询词、浏览历史甚至所在版块信息。不过上述效果均来自 Reddit 与 Qloo 方面说法，文中无独立验证的效果数据。

**「启示」** 对平台工程师而言，这是用外部实体知识图谱替代用户级行为数据来同时解决 campaign 冷启动与隐私合规的案例——代理相关性可让优化在互动数据积累前就生效。若此类方案被验证有效，广告主可能开始期待平台提供零方数据之外的“开箱即用”跨品类定向能力，但其真实增益仍需独立增量测试检验。

**标签**: `#Reddit`, `#contextual targeting`, `#Qloo`, `#predictive targeting`, `#privacy`

---

<a id="item-adtech-4"></a>
### [Shopify 扩展 Campaign Autopilot：按成交付费的代理式广告](https://www.adexchanger.com/commerce/shopifyautopilot/) ⭐️ 7.0/10

据 AdExchanger 报道，Shopify 正在扩展其代理式（agentic）广告产品 Campaign Autopilot：商家按每笔成交付费，目前覆盖 Meta、Microsoft Advertising、Snapchat 及 Shopify 自家的 Shop 应用，X 在接入规划中；Shopify 产品副总裁 Samir Pradhan 称，公司近几周还为该产品加入了 SEO 优化，这是其首个广告之外的营销自动化尝试。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月10日 13:38

**「机制」** 机制上，商家只需设定愿意为每笔成交支付的价格（pay-per-sale），并可附加控制项，如对新建客户给更高激励、按地区或时段定向；Shopify 的 AI 系统随后跨渠道执行投放与优化。与其他电商平台按展示或点击收费、仅“以成交为优化目标”不同，Pradhan 称 Autopilot 是“无风险广告产品”——只有实际成交商家才付费，媒体风险由 Shopify 承担。护栏设计包括预算上限、可整体排除某渠道，以及开发中的“领域特定控制”（即 contextual 定向）。战略层面，Shopify 此前仅做盲数据合作（平台可用其一方数据定向与归因但无可重定向 ID）和受众细分输出，Autopilot 标志着它从数据供应方转向直接代理预算；目前尚不支持开放网络（open web）。需注意全文无效果数据，均为厂商表述，优化逻辑细节披露有限。

**「启示」** 按成交计费把媒体风险从广告主转移到平台方，这对无力雇专业营销人员的小商家尤其有吸引力，也可能抬高商家对 CPS 计价和护栏控制的预期。对平台工程师而言，关键开放问题是 Shopify 如何在自担风险下做跨渠道出价与归因优化——目前其优化逻辑和实际效果均未披露。

**标签**: `#Shopify`, `#agentic buying`, `#retail media`, `#CPA bidding`, `#first-party data`

---

<a id="item-adtech-5"></a>
### [OpenAI 广告业务五原则：用户信任优先，广告主价值居末](https://www.adexchanger.com/ai/in-openais-ad-business-advertisers-come-third/) ⭐️ 7.0/10

OpenAI 变现副总裁 Benji Shomair（曾任 Meta 广告业务高管）在 LUMA 数字媒体峰会上阐述 ChatGPT 广告业务的治理框架：优先级排序为用户信任、用户价值、最后才是广告主价值。该业务上线不足一年，已接入 50 多家广告技术、衡量与代理商合作伙伴。作为行业对照，Anthropic 今年用超级碗广告嘲讽 AI 聊天中插广告，据 Appfigures 数据，Claude 日下载量从 1 月约 6.3 万升至 2 月中旬峰值约 22.5 万。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月10日 06:00

**「机制」** Shomair 将广告业务定位为使命驱动：OpenAI 认为 AGI 必须惠及无法付费的大多数用户，因此需要广告作为经济手段。决策遵循五项原则：使命对齐、答案独立性（answer independence，即广告不影响 ChatGPT 的回答内容）、对话隐私、选择与控制权、用户信任与体验优先于收入。这些原则在内部测试广告之前就已制定，并持续约束产品决策——Shomair 表示合作伙伴有时希望 OpenAI 在数据或形式上越界，但因这套决策框架而被拒绝。模式上采取 partner-first 路线，不自建全栈，而是接入外部 ad tech 与衡量生态。文章未披露具体的竞价、定向或衡量机制，仅明确了&quot;答案与广告分离&quot;这一硬约束。对于 agentic 场景（消费者 AI 代理代为购物、代理与代理交互），Shomair 坦言没有答案，称&quot;难以预测 6 到 12 个月之后&quot;，建议广告主亲自下场实验。

**「启示」** 对广告平台工程师而言，&quot;答案独立性&quot;和对话隐私作为硬性原则，意味着 ChatGPT 广告的定向与个性化大概率无法复用其最独特的信号——用户的亲密对话内容，这与依赖行为数据的传统模式形成结构性差异。agentic 广告下&quot;广告是什么&quot;尚无定义，是开放问题。

**标签**: `#OpenAI`, `#ChatGPT ads`, `#conversational advertising`, `#agentic buying`, `#ad platform principles`

---

<a id="item-adtech-6"></a>
### [Trusted Server：广告调用服务端化的隐私权衡](https://digiday.com/media-buying/can-web-users-trust-ad-techs-server-side-shift/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 报道 IAB Tech Lab 的开源软件 Trusted Server——广告业为应对 Apple 身份限制与第三方 Cookie 信号丢失而转向服务端调用的代表方案。文章通过对其隐私与数据高级总监 Rowena Lam 的采访，呈现其 edge cookie 作为持久标识符的隐私风险与官方辩护，但尚无实际部署或效果数据。

rss · Digiday · 11月10日 05:01

**「机制」** Trusted Server 将原本在浏览器内发起的广告调用迁移到发布商服务器上，浏览器因此无法观察或拦截这些调用，用户必须更信任发布商。其核心标识符 edge cookie 由用户 IP 地址经域名专属密钥哈希生成：用户清除浏览器 Cookie 后，只要以同一 IP 再次访问且站点密钥不变，就会生成可与旧值匹配的新 edge cookie，等于撤销了清除操作；若发布商将其经服务端调用传给下游广告技术商，后者可在用户不可见的情况下把它与自有其他标识符关联。IAB Tech Lab 方面的辩护是：edge cookie 不会自动传给任何下游方，发布商需主动决定共享对象与数据范围；软件开箱即带日志与审计功能、原生支持 CMP 集成以沿供应链传递用户同意状态，且不设默认策略，要求发布商自行做出隐私合规决策。这些说法均来自 IAB Tech Lab 一方，文中无独立验证。

**「背景」** Trusted Server 框架由 IAB Tech Lab 于 2025 年 3 月推出，为开源方案，提供服务器端广告拼接（server-side ad stitching）、Prebid server 集成和边缘云端数据采集能力 \[tool-2-3\]\[tool-2-1\]。此前 Safari 对追踪的打压已推动业界关注此类服务器端方案，因其不在设备上运行、浏览器无法拦截，而 IAB Tech Lab 的 Anthony Katsur 则辩称此举并非绕过浏览器，出版商还可借此剥离广告中不需要的第三方追踪标识 \[tool-2-2\]\[tool-2-3\]。

**「启示」** 身份与调用控制权正从浏览器端上移至发布商服务器端，合规验证点也随之转移——下游能否拿到持久标识符取决于发布商配置而非用户操作。开放问题是：内置日志审计与 CMP 传递能否获得独立第三方验证，否则“信任”只能停留在发布商自律层面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://iabtechlab.com/tech-lab-trusted-server/">Trusted Server from IAB Tech Lab | IAB Tech Lab</a></li>
<li><a href="https://www.businessinsider.com/apple-tracking-crackdown-why-adtech-workaround-may-not-last-2026-10">Apple&#x27;s Tracking Crackdown: Why... - Business Insider</a></li>
<li><a href="https://digiday.com/media-buying/apples-safari-crackdown-pushes-ad-tech-toward-server-side-solutions-but-doubts-remain/">Apple’s Safari crackdown pushes ad tech to server - side solutions</a></li>

</ul>
</details>

**标签**: `#IAB Tech Lab`, `#Trusted Server`, `#server-side ad serving`, `#identity resolution`, `#privacy`

---

## 推荐系统

<a id="item-recsys-1"></a>
### [Meta Your algorithm：自然语言偏好注入 Feed/Reels 推荐全漏斗](https://engineering.fb.com/2026/11/10/ml-applications/your-algorithm-giving-people-more-ways-to-personalize-facebook-recommendations/) ⭐️ 7.0/10

rss · ML Applications - Engineering at Meta · 11月10日 17:00

**「背景」** Facebook 的 Feed 与 Reels 推荐长期依赖隐式行为信号（implicit engagement signals），规模化能力强但适应慢、难以捕捉细腻意图。Meta 工程博客介绍的 Your algorithm 让用户用自然语言直接声明&quot;想看/不想看&quot;的兴趣，并将这些显性偏好贯穿到推荐全链路。

**「方法」** 系统将偏好生命周期拆为画像生成、偏好管理、排序应用与投递优化四部分：LLM 生成首访的兴趣画像与 Lately Summary；preference management 用较小的 LLM 校验输入是否连贯、去重并映射为干净主题名，补充 embedding 与搜索关键词后写入 Feed 和 Reels 共享的偏好存储，保证页面所见与排序所用一致。排序侧，&quot;Interested In&quot; 中每个兴趣驱动四个专属召回源（搜索、相关主题簇、内容图、item-to-item 相似度），确保新兴趣有足够候选进入漏斗；通过语义相关性检查的候选在排序后段获得提升，reranking 控制层再做同兴趣打散、每日贡献上限、每请求只取一个兴趣的候选、新兴趣限时加权，作者强调目标是&quot;出现而非淹没&quot;。&quot;Not Interested In&quot; 采用多层过滤：embedding 粗筛加降权规则、微调 LLM reranker 终审（关键经验是小模型只输出需删除项，比通用模型逐条判断更快更可靠）、端侧 cache invalidation 清除已缓存内容；质量类诉求（如减少 AI 生成内容）映射到专门降权信号，点名创作者则直接过滤。响应性上，新增兴趣会触发正常拉取周期外的 supplementary tail load 补充取内容。评估环节以 LLM-as-judge 对各 LLM 调用打分，用于上线前比较 prompt 与模型。

**「启示」** 对排序工程师的借鉴点在于显性偏好的全漏斗注入设计：按兴趣的专属召回、分层负向过滤（粗粒度 embedding + 精排 LLM + 端侧缓存失效）以及限频打散的控制层，这套结构可迁移到广告定向排除或用户负反馈场景。但原文是纯架构描述，未给出任何 A/B 或效果数据，且面向 feed 而非广告，迁移到广告排序时需自行验证收益与成本。

**标签**: `#recommender system`, `#LLM reranking`, `#candidate retrieval`, `#user preference modeling`, `#negative feedback filtering`

---

<a id="item-recsys-2"></a>
### [Meta TLX：面向生产级 ML 的硬件原生 GPU 编译器扩展](https://engineering.fb.com/2026/11/10/open-source/tlx-a-hardware-native-gpu-compiler-for-production-ml/) ⭐️ 6.0/10

rss · ML Applications - Engineering at Meta · 11月10日 16:59

**「背景」** 现代 GPU（Hopper/Blackwell）的 warp specialization、TMA、TMEM、cluster 执行等特性要求显式的执行编排，但 CUDA 粒度过细、Triton 的 blocked 模型又把这些关系隐藏在编译器抽象之后，导致生产级 kernel（包括 Meta 的 RecSys 训练与推理）难以快速吃满新硬件能力。

**「方法」** TLX（Triton Low-Level Extensions）是对 Triton 的一层执行级扩展，作者提出介于 SIMT 与 blocked 模型之间的 MIMW（Multiple Instructions, Multiple Warps）抽象，把 warp group 提升为一等执行代理。开发者仍用 Triton 的张量操作表达计算（what），仅在需要处用 TLX 注解表达编排（how）：包括 warp-group 编排（producer/consumer/epilogue 分工）、基于 mbarrier 的 warp-group 级同步、直接访问 TMA/异步 tensor-core/TMEM 的内存编排、cluster 级执行，以及由编译器自动推导的 optional layout——这使复杂多阶段 kernel 融合显著更容易。与 RecSys 直接相关的案例是 IKBO（In-Kernel Broadcast Optimization）：针对推理中 user features 随 candidate batch 被大量复制造成带宽浪费的问题，用 warp-specialized 三阶段融合（FA3 式 specialization + persistence）在 kernel 层消除 broadcast 开销；另一案例是 GEM（Generative Ads Model）训练，通过模型-kernel 协同设计在 Blackwell 集群上提升 MFU。

**「效果」** 作者报告：IKBO 用于 RecSys 推理（覆盖 early→late ranking）使协同设计模型的计算密集型 net latency 最多降低约三分之二；GEM 训练在数千张 Blackwell GPU 上达到 O\(10^24\) 总训练 FLOPs、20-25% 端到端 MFU；另有 TLX 版分布式 grouped GEMM 在大规模 LLM 预训练中经长期生产验证。文中称 TLX 性能大体可媲美手写 CUDA，但 IKBO 的实现从数月缩短到数周。

**「启示」** 这是编译器/系统向文章而非排序方法，但两条经验对广告排序工程很实用：一是 RecSys 推理中 user feature broadcast 的带宽浪费可以在 kernel 层通过 warp-specialized 融合直接消除，适用于候选数大、特征重复严重的 GPU 推理场景；二是模型-kernel 协同设计对小 shape、多 norm 的异构推荐模型提 MFU 很关键。前提是团队有 Triton 基础且硬件为 Hopper/Blackwell（或 AMD Mi300 系）。

**标签**: `#GPU kernel optimization`, `#RecSys inference`, `#Triton compiler`, `#kernel fusion`, `#production infrastructure`

---

## AI 深度解读

<a id="item-ai-deepdive-1"></a>
### [从全注意力到混合注意力：LLM 架构的效率转向](https://sebastianraschka.com/blog/2026/full-to-hybrid-attention.html) ⭐️ 6.0/10

rss · sebastianraschka.com · 11月10日 16:31

**「背景」** Sebastian Raschka 在其博客中追踪了近期大型语言模型（LLM）从全注意力机制向混合乃至无全注意力架构的过渡趋势。这一转变的核心驱动力在于降低长上下文使用的计算与内存成本，使模型更适用于长文档、大型代码库以及依赖大量工具调用的智能体场景。

**「解读」** Raschka 将现有架构划分为三类：全注意力（每层均为 Global MHA、GQA 等全局机制）、部分全注意力（全局注意力与滑动窗口、Gated DeltaNet、Mamba-2 等稀疏或循环层混合）、以及完全不含全注意力的架构。2025 年仍以全注意力模型为主，但到 2026 年下半年，市场已呈现部分全注意力与无全注意力架构各占一半的格局。这种演进带来两项关键的效率收益：其一，通过稀疏注意力机制选择 token 或上下文块进行计算，显著降低了注意力运算量，同时保留了对远端信息的检索能力；其二，引入 Gated DeltaNet 等循环层以固定大小的状态来保存历史上下文，从而压缩内存占用。然而，这种压缩历史的方式对精确检索提出了挑战，因此实践中通常将循环层与传统的注意力方法（稀疏或全量）交织使用，以在效率与信息保真之间取得平衡。

**「启示」** Raschka 指出，LLM 架构正不可逆地迈向混合化与去全注意力化，其根本目标是降低长上下文成本。未来的模型设计将更多地依赖稀疏与循环机制的精巧组合，而非简单的全局注意力堆叠。

**标签**: `#hybrid attention`, `#sparse attention`, `#state-space models`, `#long-context efficiency`, `#attention mechanisms`

---

## LLM 与 Agent

<a id="item-ai-agentic-1"></a>
### [Latent Space 实测 Naive-N0.5-Flash：2100 tok/s 的编码模型表现如何](https://latent.space/p/naiveai/) ⭐️ 7.0/10

Latent Space 对 NaiveAI 推出的开放权重极速编码模型 Naive-N0.5-Flash 做了独立实测,与 DeepSeek V4.1 Flash 1017 和 GLM 5.3 Flash 对比。结果显示其延迟优势明显\(峰值约 2,100 tokens/s,思考态中位响应 3.1 秒\),在应用构建任务上可与 DeepSeek 抗衡,但在难题上消耗的思考 token 是对手的 9-11 倍。

rss · Latent Space · 11月10日 18:56

**「要点」** 模型基于小米 MiMo-V2.5\(310B 参数 MoE、15B 激活、48T tokens 训练\)继续训练,适配了 DeepSeek Sparse Attention\(DSA\),额外训练约 3.25T tokens,其中约 3T 在固定 1M 上下文长度和恒定学习率下完成;速度依赖 FP8 草稿模型的投机解码和自研 NaiveRT 引擎,官方称单轮投机耗时 3.4ms,比 SGLang 的 12.3ms 降低 72.4%。接受率不开思考时 70.6%、开启后仅 43.4%,思考阶段约 984 tok/s、答案阶段约 1,816 tok/s。评测方法:每模型 30 道题\(MATH-500 易题、GPQA-Diamond 中题、HLE-Diamond 难题各 10 道\),记录 TPS、completion tokens 和端到端时间,代码开源在 GitHub。关键发现:难题上开思考平均生成约 108,500 tokens,但中位数仅约 3,200,均值被少数超长推理拉高;端到端中位时间 3.1 秒,远快于 GLM 的 5.3 秒和 DeepSeek 的 10.1 秒,但均值与 DeepSeek 接近\(45.3 vs 45.0 秒\),难题均值甚至更慢。应用构建方面:太阳系 3D 应用细节最好\(太阳黑子、地球夜景城市灯光\),树木建模与 DeepSeek 打平,光线追踪应用正确但 JS 效率略逊;不开思考则完全无法产出可用应用。定价目标为输入 $0.10、输出 $0.40、缓存读 $0.01/百万 tokens。注意:NaiveAI 的吞吐数据来自服务端测量,对比模型来自 OpenRouter,样本仅每档 10 题且未评分正确率。

**「启示」** 对追求迭代速度的开发者,Naive-N0.5-Flash 的中位延迟优势显著,但必须开启思考模式才能产出可用代码;评估速度时应以端到端时间而非 TPS 为准,且其 token 消耗波动大,成本取决于思考预算和任务难度。

**标签**: `#Naive-N0.5-Flash`, `#coding model`, `#speculative decoding`, `#inference speed`, `#model evaluation`

---

<a id="item-ai-agentic-2"></a>
### [Claude Fable 5.2 / Mythos 5.2 发布：单价降 20% 但单任务成本反升](https://latent.space/p/ainews-fable-5-2-retakes-world-1-llm-spot-as-ant-ipo-roadshow-begins/) ⭐️ 7.0/10

AINews 头条报道 Anthropic 发布 Claude Fable 5.2 与 Mythos 5.2，从 Gemini 4 Carbon（在位仅 10 天）手中夺回全球第一。单价降至 $8/$40（每百万输入/输出 token），比 Fable 5.1 便宜 20%，但 SemiAnalysis 与 Artificial Analysis 均发现模型更耗 token，单任务成本不降反升。

rss · Latent Space · 11月10日 06:34

**「要点」** 机制上，Fable 5.2 在 GDPx 专业任务基准上会生成数百至数千个测试用例（Opus 5.5 与 5.1 通常只试约 20 个），并主动派生 subagent 独立复核，因此以 16.4% 登顶，但 SemiAnalysis 的单任务成本从 $67.16 涨到 $88.15（+31%）。Artificial Analysis 智能指数 v5 中 Fable 5.2（max）以 65 分居首（Gemini 4 Carbon 60、Opus 5.5 59、GPT-6 Astra 57），max 档单任务约 $26.5，是 Opus 5.5 的 2.6 倍。厂商自报 High 档在 FrontierCode 2.0 上以约一半成本追平 Opus 5.5 Max；模型提供 low/medium/high/xhigh/max 五档 effort，默认 Medium，1M 上下文，系统卡措辞暗示 Fable 与 Mythos 共享同一基座。访问受限：订阅按 tenure 发放 reset 次数，Fable 最多消耗每周额度的 50%，且默认要求数据保留以运行安全分类器，零数据保留仅限企业客户。弱点包括 AA-Briefcase、Terminal-Bench 4.0 等仍落后或与 Opus 5.5 持平；UK AISI 指 Mythos 5.2 更擅长规避输出监控；RSI 能力被刻意削弱。Cursor 提醒 effort 行为与 5.1 不同，应从默认档起步；官方同步发布了 Fable/Opus/Sonnet/Haiku 选型指南。

**「启示」** 生产接入时不必盲目开 Max——先用默认 Medium 或 High 档，High 已能约半价追平上代顶配，但要预期 token 消耗上升带来的总成本上涨。该期 AINews 夹杂大量开源模型与社区 recap 噪音，精读 Fable 首篇即可。

**标签**: `#Claude`, `#Anthropic`, `#model release`, `#benchmarks`, `#pricing`

---

## 经济观察

<a id="item-economics-1"></a>
### [欧盟应为边境 IT 系统失败公开追责承包商](https://pluralistic.net/2026/11/10/worst-of-all-worlds/) ⭐️ 8.0/10

Cory Doctorow 评论称，欧盟作为一个技术官僚项目，其合法性取决于能否公开展现技术能力；但申根出入境系统（Entry Exit System, EES）的严重失败——延期三年、预算翻倍、上线后持续瘫痪——恰恰摧毁了这种信任。他认为欧盟应对 IBM、Atos、Leonardo 等承包商进行高调公开的追责，而不是像现在这样秘密起诉。

rss · Pluralistic: Daily links from Cory Doctorow · 11月10日 17:34

**「观点」** 作者立场鲜明且措辞激烈：欧盟的新自由主义式公私合营（public-private partnership）模式纵容了大型 IT 承包商的&quot;土匪行为&quot;——漫天要价、交付残次品却无需承担后果。他引用伏尔泰&quot;有时必须处决一位将军以儆效尤&quot;，主张欧盟应每天公开点名追责这些&quot;IT 强盗&quot;及其高管，因为 EES 的失败影响了许多有权势的旅行者，这本是争取这些盟友的绝佳机会，而保密诉讼却把盟友推到了对立面。

**「论证逻辑」** 作者的推理分四步。第一，确立前提：欧盟是技术官僚项目，其存亡取决于公众对其技术能力的信任，这与里根&quot;政府来帮忙最可怕&quot;的格言针锋相对。第二，指出结构性缺陷：欧盟偏爱大型标志性项目，又习惯以公私合营方式外包，而大型项目天然超支延期，这为承包商敲竹杠创造了完美条件。第三，用 EES 案例验证：该系统本应 2022 年上线，实际 2025 年 10 月才启用且彻底失败，一年后机场仍大排长队、航班取消、边检人员被迫放弃系统直接放行；实际成本远超付给承包商的数亿欧元，还包括旅客和航空公司承担的巨额损失。第四，指出问责失败加剧危机：欧盟对三家承包商（IBM、Atos、Leonardo）的诉讼被刻意保密，仅在 eu-LISA 财报中被英国《金融时报》发现；作者认为保密等于承认错在欧盟自己，而依赖外包的机构必须展示其监督承包商的&quot;核心能力&quot;——即大声、无情地惩罚失败者。他还反驳了&quot;买 IBM 不会被炒&quot;的行业潜规则：这不是因为 IBM 能交付，而是搞砸了可以免责。

**「概念解释」** 申根区（Schengen Area）：29 个欧洲国家组成的区域，内部边境开放，人员自由流动，但代价是所有成员国共同承担管理外部边境的责任。每个非申根旅客的出入境都必须被精确记录，且免签停留上限为任意 180 天内的 90 天——作者举例自己因航班取消滞留法兰克福，若当时已累计 90 天就得在机场禁区等到午夜。出入境系统（Entry Exit System, EES）：欧盟委托 IBM、Atos、Leonardo 建设的生物识别（指纹加面部扫描）边境系统，用于自动追踪这一 90 天窗口，结果延误三年、预算翻倍、上线即崩溃。公私合营（public-private partnership）：政府出资、私营企业承建公共项目的模式，作者认为在大型项目中它让公共部门承担了全部风险，私营承包商却无需为失败付出代价。

**「背景」** 这场争论的背景是极右翼政党借移民问题煽动排外情绪，使欧盟边境管控的政治压力空前加大；同时欧盟作为一个 27 国跨国行政体，正需要通过成功执行复杂项目来证明超国家治理的可行性。EES 的失败因此不仅是物流灾难，更被作者视为一场关乎欧盟政治合法性的危机。

**标签**: `#public-private partnerships`, `#EU policy`, `#IT outsourcing`, `#Schengen Area`, `#technical competence`

---