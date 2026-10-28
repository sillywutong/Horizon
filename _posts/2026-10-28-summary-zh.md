---
layout: default
title: "Horizon Summary: 2026-10-28 (ZH)"
date: 2026-10-28
lang: zh
---

> 从 42 条内容中筛选出 9 条重要资讯。

---

**广告技术**
1. [MDM 播客：为 AI 代理发现重构电商（FERMÀT 创始人访谈）](#item-adtech-1) ⭐️ 7.0/10
2. [Apple’s identity-resolution block is not ATT for the web](#item-adtech-2) ⭐️ 7.0/10
3. [Lush 退出付费社交广告五年仍实现增长](#item-adtech-3) ⭐️ 7.0/10
4. [Safari 限制身份域名，广告业转向服务端方案但存疑](#item-adtech-4) ⭐️ 7.0/10
5. [Wurl 分析揭示 CTV 竞价请求类型标签混乱问题](#item-adtech-5) ⭐️ 7.0/10
6. [识别有毒 CMO 的十一种原型](#item-adtech-6) ⭐️ 7.0/10

**广告实操教程**
1. [如何向非营销背景的利益相关者讲清内容策略](#item-adtech-practical-1) ⭐️ 8.0/10

**推荐系统**
1. [Meta Andromeda 广告检索引擎：模型-系统-硬件协同设计](#item-recsys-1) ⭐️ 9.0/10

**经济观察**
1. [AI 代理为何斗不过电商：不透明是功能而非缺陷](#item-economics-1) ⭐️ 8.0/10

---

## 广告技术

<a id="item-adtech-1"></a>
### [MDM 播客：为 AI 代理发现重构电商（FERMÀT 创始人访谈）](https://mdm.co/podcast-designing-ecommerce-for-agentic-discovery-with-rishabh-jain/) ⭐️ 7.0/10

Eric Seufert 采访 FERMÀT Commerce 创始人 Rishabh Jain，讨论购物 AI 代理（agent）如何重塑电商发现、网站结构、排序经济与品牌对亚马逊的竞争。Jain 以自己使用浏览器型代理（他称 Muse）跨独立品牌完成服饰购买为例，认为第三方代理在独立品牌侧“确实在发生”，但不会发生在亚马逊这类平台（约占美国电商 36%）之内。需注意这是对谈中的观点与轶事，主持人自述为该公司投资人，全文无实测数据。

rss · MDM by Eric Seufert Mini RSS · 10月28日 13:43

**「机制」** 对话的机制核心有三层。其一是信任与转化：浏览器型代理在用户可视的回路（human-in-the-loop）中直接操作品牌网站，解决了 ChatGPT 式集成中信息不可信、品牌拿不到用户关系（邮箱）的问题，因此独立品牌的代理交易可行而平台型不行。其二是商家侧的接口重构：Jain 建议商户为代理而非人类展示信息，例如把服装的工厂规格表（spec sheet）直接放上网页供代理读取，形成类似 agents.md 的“给代理看的产品说明书”，并为代理优化信息流刷新与数据供给；落地页也应根据代理从广告创意中带来的意图信号动态适配，他把这描述为 Meta 广告机制的“代理化延伸”。其三是排序经济学：Seufert 提出代理未来可能对成交抽成（如 4-5%），并在同等相关时倾向推高客单价商品，即商品排序可能走向广告拍卖而非订阅；Jain 则把消费者偏好分为“已设定”与“开放”两类，代理与商家的机会在于识别开放偏好并用信息填充。实操建议是像当年做 SEO 一样“增长黑客”代理交互：反复构造页面让代理完成购物并迭代。局限在于全为前瞻性推测，未给出代理提前收窄选择集的检测方法，也未涉及衡量结果。

**「启示」** 对广告平台与算法工程师而言，这是一个值得关注的机制假设而非已验证趋势：若代理中介的购物起量，商品排序可能从订阅转向按成交抽成的拍卖逻辑，广告信号也将经由代理直接改写落地页与转化漏斗。但所有论断均来自访谈双方（含利益相关方）的推测，是否阅读原文取决于你是否关心代理电商的接口与排序设计思想，而非寻找数据证据。

**标签**: `#agentic commerce`, `#AI agents`, `#e-commerce`, `#advertising auctions`, `#conversion funnel`

---

<a id="item-adtech-2"></a>
### [Apple’s identity-resolution block is not ATT for the web](https://mdm.co/apples-identity-resolution-block-is-not-att-for-the-web/) ⭐️ 7.0/10

Eric Seufert examines Apple’s WebKit restrictions on alternative identifiers in iOS 27 and argues they should not be interpreted as a web version of ATT.

rss · MDM by Eric Seufert Mini RSS · 10月28日 01:46

**标签**: `#Apple`, `#WebKit`, `#identity resolution`, `#privacy`, `#attribution`

---

<a id="item-adtech-3"></a>
### [Lush 退出付费社交广告五年仍实现增长](https://digiday.com/marketing/how-lush-quit-social-media-ads-and-still-drove-growth/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 报道，美妆品牌 Lush 自 2021 年起全面退出 Instagram、Facebook、TikTok、Snapchat（后含 X）的付费广告与官方发帖，以抗议平台数据隐私与算法问题。五年后公司仍在增长：2025 财年营收£736.2M（约$982.3M），高于 2024 年的£672.7M；北美营销负责人 Julia Hamfelt 未披露具体投放金额。

rss · Marketing – Digiday · 10月28日 04:01

**「机制」** 机制上，Lush 用&quot;投资人而非平台&quot;的替代组合重建触达：创作者/影响者合作、线下活动、品牌联名（据 6 月财报贡献约£34M 销售额）、以及自有渠道——App 现有 280 万用户、邮件触达全球超 600 万人；同时保留 YouTube、Pinterest 的有机运营，并新增 Substack 与 Bluesky。值得注意的基线条件是：退出前付费社交在其预算中占比本就很小（Hamfelt 拒绝透露数额），因此营收增长不能强因果地归因于退出本身；报道也未说明其如何评估各渠道组合的效果，仅引用行业观点称高级增量测量（incrementality）正帮助品牌辨别哪些花费真正带来增量。行业背景上，IAB 报告称去年社交广告收入达$117B，超过搜索（$114.2B），eMarketer 预计明年社交将占广告支出三成以上——Lush 是逆这一趋势的个案。

**「启示」** 对平台与算法工程师而言，这是一个罕见的&quot;去平台化&quot;压力测试案例：它显示付费社交的 reach 价值在自有渠道与创作者生态足够强时可被替代，但因果证据有限。当更多品牌用增量测量审视社交预算，平台需要证明的就不只是触达规模，而是可归因的增量价值。

**标签**: `#Lush`, `#paid social`, `#media mix diversification`, `#owned channels`, `#creator marketing`

---

<a id="item-adtech-4"></a>
### [Safari 限制身份域名，广告业转向服务端方案但存疑](https://digiday.com/media-buying/apples-safari-crackdown-pushes-ad-tech-toward-server-side-solutions-but-doubts-remain/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Apple 对 Safari 中身份识别服务商域名的限制，正推动出版商和广告技术公司把身份与广告基础设施迁出浏览器：ID5 确认将更多身份基础设施转为服务端集成，IAB Tech Lab 2025 年 3 月提出的 Trusted Server Framework 也重新受到关注。据 Digiday 看到的实测结果，Audigent、ID5、LiveRamp、Permutive 和 The Trade Desk 等厂商受到影响，但因 iOS 27 采用率较低，目前商业冲击有限。

rss · Digiday · 10月28日 04:01

**「机制」** Apple 在 WebKit 说明中明确反对利用邮箱等信息派生的标识符在未经同意的情况下跨站识别用户，并在解释发布前就已生效限制。行业应对方案是把原先通过对第三方域名的浏览器端调用完成的身份识别与广告请求，迁移到出版商控制的服务端基础设施：ID5 CEO Mathieu Roche 称服务端方案&quot;不在设备上，设备就无法封锁&quot;，大型出版商数天即可完成改造，但小型出版商实施门槛更高。Trusted Server Framework 则是开源方案，将广告请求、Prebid Server 集成、边缘处理和广告拼接移入出版商自营基础设施，以降低对浏览器政策的依赖并增强对竞价和第一方数据的控制。核心争议在于：Apple 反对的是跨站追踪这一数据实践本身，而非其实现位置，因此服务端迁移可能只是把追踪搬到浏览器控制之外，引发新一轮猫鼠游戏；批评者还担心基础设施复杂度、云厂商依赖和指纹识别的延续，而出版商可能在 Apple 已表明反对的做法上投入重金后再遭限制。Apple 与 IAB Tech Lab 均未回应置评，部分信息依赖匿名消息源。

**「背景」** Trusted Server Framework 并非针对本次事件的应急方案：IAB Tech Lab 早在 2025 年 3 月就推出了这一开源框架，主张将广告请求、Prebid Server 集成、边缘处理等原本在浏览器内执行的功能迁入发布商自营的基础设施。此次 Safari 动作也是 Apple 长期收紧跨站追踪的延续——Safari 此前已通过智能防追踪（Intelligent Tracking Prevention, ITP）大幅限制第三方 Cookie 与跨站识别，而这次限制对象扩展到了身份服务商域名本身，等于把浏览器侧的规避空间进一步压缩，从而加速了行业向服务器侧迁移的讨论。

**「启示」** 对平台工程师而言，这表明身份与竞价架构的&quot;服务端化&quot;正从可选项变为抗浏览器限制的现实需求，但其持久性取决于数据实践能否通过隐私审查而非仅仅是部署位置。悬而未决的问题是：出版商控制的第一方个性化与跨站识别基础设施之间的界限，将决定 Trusted Server 类方案是长期解药还是下一轮对抗的开端。

**标签**: `#Apple Safari`, `#identity resolution`, `#server-side advertising`, `#IAB Tech Lab Trusted Server`, `#publisher monetization`

---

<a id="item-adtech-5"></a>
### [Wurl 分析揭示 CTV 竞价请求类型标签混乱问题](https://digiday.com/future-of-tv/future-of-tv-briefing-ctv-advertising-has-a-genre-label-problem/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 援引流媒体技术商 Wurl 的分析称，CTV 竞价请求中的类型标签和节目名过于混乱，难以支撑可靠的内容信号。在 2026 年 8 月一个黄金时段两小时的样本中，仅 11%的请求带可用节目名，93%带类型标签，但 35%的标签与 Wurl 自有分类不符，22%为“娱乐”类空泛标签，两小时内出现超过 3,600 个不同标签。

rss · Digiday · 10月28日 04:01

**「机制」** 在程序化 CTV 中，内容标签由内容方负责附加到竞价请求（bid request），买方据此做上下文定向和品牌安全判断。问题在于缺乏标准化：内容库元数据多为数十年前的遗留分类（Bernath 称之为“历史元数据包袱”），同一部剧可被标为剧情或喜剧，且无任何强制命名规范。IAB Tech Lab 的内容分类标准（Content Taxonomy）早在 2022 年就更新了 CTV 类目、后又扩充至 704 个类别，但内容方普遍未采用——704 仅为 Wurl 观测到的标签量的五分之一。即便 FreeWheel 今夏推出节目级报告，也未强制买卖双方统一节目命名，可能使跨方匹配失效。Wurl 自身的做法是用机器学习分析流和 EPG 元数据，对齐到 IAB 标准类别。局限在于：数据为单一供应商两小时窗口的快照，且其在分类服务上有商业利益。

**「启示」** 对平台工程师而言，这意味着基于 bid request 内容信号的上下文定向和节目级报告在输入端就不可靠，标签映射与清洗层是必要前置。开放问题是：标准早已存在，谁来推动内容方实际落地，还是由平台侧用 ML 分类绕过内容方。

**标签**: `#CTV`, `#content signals`, `#IAB Content Taxonomy`, `#show-level reporting`, `#bid request metadata`

---

<a id="item-adtech-6"></a>
### [识别有毒 CMO 的十一种原型](https://www.adweek.com/media/how-to-spot-a-toxic-cmo/) ⭐️ 7.0/10

作者在 Adweek 发文，基于三十年行业经验归纳出 11 种&quot;有毒 CMO&quot;原型，包括个人品牌经理、行动成瘾者、增长瘾君子、追风口者、尖端恐龙、挑战者扮演者、青年崇拜者、接单员、道歉式营销人、象牙塔国王和幸运天才。文章核心论点是：这些角色并非被招聘进来，而是被组织激励机制&quot;生产&quot;出来的，根因在于公司奖励可见的行动而忽视安静的品牌守护，且缺乏高管层对品牌的共同问责。

rss · AdWeek: AdFreak · 10月28日 10:00

**「机制」** 文章的机制分析在于组织激励如何系统性塑造 CMO 行为：推出新项目会带来汇报、里程碑和掌声，而默默维护品牌资产得不到同等回报，于是 CMO 倾向于不断启动转型、改名、追新平台（purpose、DTC、创作者、AI）。同时 CFO 要回报、销售要新品、CEO 要敏捷、董事会要 AI 愿景，CMO 被困在多重矛盾指令中，沦为可预测的畸形产物。对广告行业最相关的两类原型是&quot;尖端恐龙&quot;——熟练谈论程序化广告和文化微定向，却从未接触过 Byron Sharp 关于渗透率、轻度购买者和心智可得性的研究，工具升级了而增长认知没有；以及&quot;幸运天才&quot;——在品类顺风、对手失误或渠道扩张时发起 campaign，销量上升后把尾部风向归因为自己的英明，作者称其&quot;诊断能力弱但归因天赋高&quot;。作者开出的药方是：既然品牌价值占公司价值大头，高管委员会应像审查并购和重组一样审查品牌决策，建立共享的高管品牌问责，而非把品牌当作&quot;其他事项&quot;的最后议题。

**「启示」** 对广告平台工程师而言，这篇文章提醒：客户侧的营销决策者可能既缺乏效果证据框架（How Brands Grow 式认知），又身处奖励短期可见行动的组织中，这会持续推高对短期归因数字的需求。同时&quot;幸运天才&quot;式归因谬误（把品类顺风记为 campaign 功劳）正是增量测量要纠正的问题，平台在推广因果测量时需要意识到客户内部的政治阻力。

**标签**: `#。`, `#。`, `#。`, `#。`, `#。`, `#。`, `#。`

---

## 广告实操教程

<a id="item-adtech-practical-1"></a>
### [如何向非营销背景的利益相关者讲清内容策略](https://neilpatel.com/blog/teach-content-strategy-to-stakeholders/) ⭐️ 8.0/10

Neil Patel 博客作者 Shelby Dias 提出一套面向非营销利益相关者的内容策略沟通方法：核心论点是好策略常死于&quot;翻译&quot;而非内容本身，文中引用 Content Marketing Institute 数据称 21% 的 B2B 营销人把跨部门协作列为主要挑战之一。文章给出四条具体做法：用对方已有的指标开场、主动拆弹骇人数据、把新战术锚定到旧共识、交付可携带的行动清单。

rss · Neil Patel · 10月28日 16:00

**「机制」** 机制本质是一套&quot;指标翻译—预期管理—行动落地&quot;的沟通流程。第一步是把策略换算成对方部门已有的计价单位：对预算方讲效率（刷新存量页面 vs 新页面数月成熟期），对法务讲风险（署名作者降低无来源声明的归因风险），对销售讲速度（清晰结构让销售在交易中段直接发链接），并把自然流量、排名等指标对接到对方 dashboard 里的 pipeline、获客成本（CAC）上。第二步是预期管理：主动先说坏消息，例如文中引用 Pew Research 对 68,879 次 Google 搜索的追踪，AI Overview 出现时点击率从 15% 跌到 8%，作者建议在 stakeholder 自行脑补前先报数并立即给出应对叙事（把精力转向转化型页面、成为 AI 引用来源）。第三步是术语诚实化：承认 AEO（answer engine optimization）与 GEO（generative engine optimization）定义重叠且各家说法不一，并先讲不变的基本功（清晰写作、结构、专业性，与 Google E-E-A-T 信号重合），再讲变化，让新战术被读作演进而非否定去年投入。第四步是落地交付：用具体的 before/after 清单（如&quot;首 40 词回答主问题、规格表用通俗标签、加署名专家引语&quot;）替代&quot;让产品页更适配 AI 搜索&quot;这类空泛建议，并做成可转发的单页材料。

**「启示」** 对平台与算法工程师而言，这篇文章折射出一个需求侧信号：AI 搜索导致的 CTR 下滑已进入代理商对客户的标准话术，广告主会越来越期待平台方也能用他们自己的业务指标（而非曝光、点击）解释流量结构变化。同时 AEO/GEO 概念定义混乱、却在快速进入客户简报，围绕&quot;被 AI 引用&quot;的测量与优化能力可能成为一个尚无可信归因标准的新竞争点。

**标签**: `#内容营销`, `#利益相关者沟通`, `#内容策略`, `#AI搜索`, `#GEO/AEO`

---

## 推荐系统

<a id="item-recsys-1"></a>
### [Meta Andromeda 广告检索引擎：模型-系统-硬件协同设计](https://engineering.fb.com/2026/10/28/ml-applications/meta-andromeda-next-gen-ads-retrieval-gpu-co-design/) ⭐️ 9.0/10

rss · ML Applications - Engineering at Meta · 10月28日 16:00

**「背景」** 广告检索（retrieval）是广告推荐链路的第一阶段，需要在毫秒级从海量候选广告中筛出少量候选，再交给计算量更大的排序（ranking）阶段。Meta 称，随着生成式 AI 工具让广告候选池急剧膨胀，2024 版 Andromeda 的 GPU 优化 DNN 架构在质量与吞吐上都不再够用：继续提升模型质量成本不可持续，而在每秒数十亿次打分规模下，中间张量的显存带宽与跨主机网络传输成为新瓶颈。

**「方法」** 核心思路是把模型、系统、硬件作为一个整体做协同设计（co-design）。模型侧，新一代 Andromeda 引入受 LLM 启发的检索混合专家（Mixture-of-Experts）架构：用户塔从单塔升级为多个专门化的用户塔专家，融合序列互动事件、用户群组表征、LLM 语义特征与跨场景共现信号；广告塔采用融合实时 serving 上下文的联合编码；交互层则从稠密网络改为基于注意力的 MoE 门控网络，将候选动态路由到最相关的用户专家，以约 300 分之一的推理 FLOPs 达到接近排序级的表现力。系统侧有两个关键机制：一是把每次用户-广告打分涉及的模型与系统算子融合进单个 GPU kernel，使中间结果留在寄存器和共享内存中、不再写回 HBM，从而消除检索负载固有的显存带宽瓶颈；二是把索引匹配（广告主定向规则过滤）、打分与 top-K 选择同机共置（co-location）在同一 GPU 上，请求侧只发送紧凑的用户特征与定向查询、仅回传 top-K 结果，使网络流量下降约 100 倍，让系统重新变回 GPU 计算受限。作者还提到为此重新设计了支持实时更新的 GPU 并行索引结构。

**「效果」** Meta 报告（未经独立验证）：端到端单 GPU 服务器每秒可评估超过 10 亿条广告并覆盖全部合格候选，相比 2024 版吞吐提升约 100 倍；自 2025 年以来在 Facebook 上带来 2.4% 的转化提升。与 NVIDIA 的联合优化中，门控 kernel 提速 5.3 倍至每秒超 100 亿次打分、达到约 85% 的 HBM 峰值带宽，索引匹配提速超 2 倍，各组件提速 2-5 倍；INT8 量化在精度持平 FP16 的前提下再带来最高 2 倍吞吐。

**「启示」** 对广告排序工程师来说，可借鉴两点：用注意力门控的检索 MoE 在低成本下逼近排序级表现力，以及在十亿级吞吐下把中间张量显存流量和网络传输当作一等瓶颈来做 kernel 融合与算子共置。该方法适用于候选池极大、打分吞吐已到显存/网络带宽受限的系统；文中数字均为 Meta 官方口径，需注意未经验证。

**标签**: `#ads retrieval`, `#mixture-of-experts`, `#model-system co-design`, `#GPU serving optimization`, `#two-tower retrieval`

---

## 经济观察

<a id="item-economics-1"></a>
### [AI 代理为何斗不过电商：不透明是功能而非缺陷](https://pluralistic.net/2026/10/28/principle-agent-problem/) ⭐️ 8.0/10

Cory Doctorow 评论&quot;代理式 AI（agentic AI）&quot;替消费者网购的愿景为何注定碰壁：电商平台的利润恰恰依赖价格和界面的不透明，所以它们会封锁购物机器人，而不是让网站对机器可读——用他的话说，&quot;不透明是功能，不是缺陷&quot;。

rss · Pluralistic: Daily links from Cory Doctorow · 10月28日 10:54

**「观点」** 作者立场鲜明而尖锐：让 AI 代理在公开网络上替你比价、下单是幻想。他认为监控定价、滴漏定价、垃圾费等手段是大公司利润增长的来源，与自动化比价天然对立，因此电商平台注定会大规模屏蔽 AI 代理；AI 公司对此心知肚明，Google 的盈利计划反而是把监控数据加 AI 工具卖给商家，用于对消费者差别定价宰客。

**「论证逻辑」** 作者以他 2001 年批评语义网（Semantic Web）的旧文立论：任何以&quot;全世界先放下自身利益来配合我的计划&quot;为前提的方案都不可行。技术上，单一聊天机器人无法完成搜票、比价、交易等复杂任务，于是改为专业机器人组成的&quot;蜂群&quot;，但这带来双重代价：算力成本上升，且错误率相乘——每增加一个机器人，系统整体故障率反而更高。更根本的是利益问题：语义分歧背后是真实的利益与价值冲突，而非缺乏&quot;客观正确的分类&quot;；电商普遍使用监控定价、操纵品类、滴漏定价和垃圾费，这些手段表面违法、屡被起诉，却因太赚钱，企业宁交罚款也不停手，而它们都要求不透明，与自动比价水火不容。现实印证了他的预测：电商平台正在大规模屏蔽第三方 AI 代理。

**「概念解释」** 代理式 AI（agentic AI）指能替用户自主完成搜索、比价、下单等多步任务的 AI 系统。监控定价（surveillance pricing）是利用收集到的个人数据对不同消费者差别要价。滴漏定价（drip pricing）与垃圾费（junk fees）是先标低价、在结账流程中逐项加费，让真实价格很晚才显现。这些手段共同依赖信息不透明才能奏效，因此自动比价工具直接威胁其盈利根基，平台必封锁之。

**标签**: `#platform economics`, `#AI agents`, `#ecommerce`, `#pricing power`, `#market incentives`

---