---
layout: default
title: "Horizon Summary: 2026-11-13 (ZH)"
date: 2026-11-13
lang: zh
---

> 从 27 条内容中筛选出 7 条重要资讯。

---

**广告技术**
1. [Schibsted 自建优化算法夺回 Meta 预算](#item-adtech-1) ⭐️ 8.0/10
2. [Google Ads 推出无效流量透明报告卡](#item-adtech-2) ⭐️ 7.0/10
3. [Viant 收购 Waymark：以生成式创意复制 Meta 自助模式进军 CTV](#item-adtech-3) ⭐️ 7.0/10
4. [Yahoo 成为首个 ILC 集体授权模式的被授权方](#item-adtech-4) ⭐️ 7.0/10
5. [IAB 发布 AI 归因蓝图：平台数据不透明成标准化障碍](#item-adtech-5) ⭐️ 7.0/10

**经济观察**
1. [技术创新是在巨大设计空间中搜索](#item-economics-1) ⭐️ 9.0/10
2. [Uber 的劳动力危机：机器人出租车为何算不过账](#item-economics-2) ⭐️ 8.0/10

---

## 广告技术

<a id="item-adtech-1"></a>
### [Schibsted 自建优化算法夺回 Meta 预算](https://www.adexchanger.com/publishers/custom-ad-algorithms-are-helping-schibsted-media-win-budgets-back-from-meta/) ⭐️ 8.0/10

北欧出版集团 Schibsted Media 与伦敦 Nodals AI 合作，基于自有第一方数据构建定制化广告优化算法，推出按 CPC 计价的直销原生广告产品，以对抗 Meta Advantage+ 等自动化工具并赢回效果预算。据 AdExchanger 报道，该方案自去年夏季测试以来已帮助其获得新客户预算并赢回部分流失客户。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月12日 08:30

**「机制」** Nodals 将 Schibsted 的第一方信号——包括登录数据、页面滚动深度、内容与广告点击行为——输入定制模型，预测用户对特定广告的点击与购买概率，并将优化算法内嵌于直销原生广告产品中。与 Meta 的“黑盒”自动化不同，出版商拥有算法与数据主权，规避了 Apple 对第三方 ID 图谱的限制。商业模式上，产品从 CPM 转向 CPC 计价，直接对标 Meta 的 ROI 逻辑。Schibsted 采取“边际竞争”策略：不追求全面超越 Meta，而是说服广告主将 Meta 预算的 10% 转移至其平台，利用约 50% 的本地用户触达在边际上提供增量转化，以应对 Meta 转化率趋于平缓的投放后期。

**「启示」** 出版商正通过“围墙花园化”的第一方数据优化能力直接对抗平台自动化工具，CPC 直销模式可能成为争夺效果预算的新标准。对平台工程师而言，这意味着需关注出版商自建算法对流量变现效率的冲击，以及透明化、可定制的优化产品如何影响预算分配逻辑。

**标签**: `#Schibsted`, `#first-party data`, `#ad optimization`, `#walled gardens`, `#direct sales`

---

<a id="item-adtech-2"></a>
### [Google Ads 推出无效流量透明报告卡](https://www.adexchanger.com/platforms/google-will-now-tell-you-exactly-how-much-its-crediting-you-for-invalid-traffic/) ⭐️ 7.0/10

Google Ads 在界面中新增 Invalid Traffic Overview Card，首次向广告主展示因无效流量（IVT）过滤而节省的具体金额，以及账单周期后检测到机器人流量所获得的退款金额。据 Google 称，2023 至 2024 年间 AI 驱动的检测增强使投向无效流量的广告减少了 40%。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月12日 13:01

**「机制」** Google 的 IVT 处理分为两个阶段：计费前过滤（pre-billing filtering）与计费后退款（post-billing credit）。系统分析所有流量（包括 agentic AI 代理产生的流量）以判断是否存在真实商业兴趣，目标是在账单周期结束前拦截无效流量，直接避免扣费；若后续分析发现漏网的 IVT，则自动将等额广告支出（如 100 美元）作为账单调整项退至下一张发票，且该额度适用于所有广告库存。此前广告主无法区分这两类补偿的具体金额，新功能通过 UI 卡片将&quot;节省金额&quot;与&quot;退款金额&quot;透明化，属于报告层改进，不改变底层检测或拍卖逻辑。

**「背景」** 无效流量占比持续上升：Thales 研究显示 2024 年自动化流量已占在线活动 53%，超过人类流量；DoubleVerify 指出 2024 年末因生成式 AI 和 AI 爬虫活动增加，IVT 同比增长 86%。

**「启示」** 平台开始将流量质量审计从黑盒转为可量化的财务透明指标，工程师需关注 IVT 检测的召回率与计费系统的对接逻辑。当自动化流量（含 AI 代理）超过人类流量时，区分&quot;恶意机器人&quot;与&quot;无商业价值的代理&quot;将成为平台流量分类的新挑战。

**标签**: `#Google Ads`, `#invalid traffic`, `#ad verification`, `#billing transparency`, `#bot traffic`

---

<a id="item-adtech-3"></a>
### [Viant 收购 Waymark：以生成式创意复制 Meta 自助模式进军 CTV](https://www.adexchanger.com/tv/viants-vanderhook-brothers-want-to-make-your-next-ctv-ad/) ⭐️ 7.0/10

Viant 以 2000 万美元收购生成式 AI 视频广告平台 Waymark，CEO Tim Vanderhook 与 COO Chris Vanderhook 在 AdExchanger 采访中阐述其战略：将 Meta 的自助式高创意量打法复制到 CTV。Waymark 过去一年已为 Comcast、NBCU 等媒体公司的本地广告主生成超一百万条广告。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月12日 11:00

**「机制」** Viant 试图构建一个闭环：此前收购的 Iris.TV 提供内容信号做广告与内容的匹配，TVision 做注意力测量，Waymark 则在旧创意失效时批量生成新版本——即&quot;内容定向+注意力验证+创意补给&quot;的自优化循环。其目标客群是中型市场和 DTC 品牌，这些品牌在 Meta 上月支出达数千万美元，因为 Meta 用算法接管了媒体优化和受众定向，只要求品牌尽可能多地产出创意；Viant 认为要在电视上复刻这一模式，必须用生成式 AI 替客户生产广告片，否则自助模式的人力成本不成立。创意疲劳是其核心论据：据 TVision 数据，人身伤害律所 Morgan &amp; Morgan 一条播了五年的广告人类注意力仅 21%，而新广告达 86%；且最优频次因品类差异巨大——医疗广告在 50 次曝光后仍能维持互动，而超级碗广告一次曝光后注意力就断崖式下跌。Tim 还援引数据称 banner 广告记忆度约 2%、电视广告 32%、电视加展示组合 38%，以此论证 CTV 价值。Viant 同时承认其集购买平台、身份、内容数据、测量与创意于一体存在&quot;自己批改作业&quot;的利益冲突质疑，其回应是一切可审计且自身不拥有内容。

**「背景」** 此次收购是 Viant 近两年收购链条的最新一环，此前已收购内容信号公司 Iris.TV、注意力测量公司 TVision 以及去年让投资者困惑的身份方案公司 lockr。采访中还提到开放网络目前仅占 Viant 业务的 10%或更低，已非增长动力，公司重心明显转向 CTV。

**「启示」** DSP 正将竞争边界从 bidding 和定向扩展到创意生产环节，创意更新速度与注意力测量可能成为平台差异化的新维度。但需注意文中注意力与记忆度数据均来自 Viant 自有测量资产 TVision 且服务于其收购叙事，工程师应关注其测量独立性及生成式创意在品牌安全与披露上的未决问题。

**标签**: `#Viant`, `#CTV`, `#generative creative`, `#creative fatigue`, `#attention measurement`

---

<a id="item-adtech-4"></a>
### [Yahoo 成为首个 ILC 集体授权模式的被授权方](https://digiday.com/media/yahoo-becomes-first-licensee-of-spotify-like-collective-ai-content-licensing-model/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Yahoo 成为互联网授权集体组织（The Internet Licensing Collective, ILC，前身为 Really Simple Licensing, RSL）的首个被授权方。该组织采用一种类似 Spotify 的集体模式，将 AI 内容授权费用汇入按使用方式细分的版税池，并根据内容在 AI 产品中的实际用途（如 grounding、retrieval 或引用）向出版商支付报酬。目前，出版商的内容将用于 Yahoo 的 AI 搜索引擎 Scout。

rss · Media – Digiday · 11月12日 14:01

**「机制」** ILC 建立了一个基于“按价值付费”（pay-per-value）的系统，而非传统的单一固定费用。被授权方支付与“需求侧收入”挂钩的一揽子许可费，这意味着随着 AI 业务规模的扩大，出版商获得的补偿也随之增长。核心机制在于“分段版税池”（segmented royalty pool）：来自不同 AI 公司的资金被隔离管理，确保出版商仅从实际使用其内容的特定产品收入中分成，防止高价值垂直领域内容被通用搜索内容稀释。分配规则（allocation rules）根据内容的贡献度计算，例如用于事实核查的 grounding 权重较低，而作为来源被明确引用并展示详细内容的权重较高。ILC 的分配逻辑旨在引导 AI 公司优先选择高质量来源，而非仅追求低成本内容。出版商可通过门户自主选择授权对象，并监控内容在 RAG 或训练中的具体用途。

**「背景」** 该模式标志着从 OpenAI 等公司与出版商签订的一对一协议向集体基础设施的转变。此前，Digiday 曾报道 Google 和 Microsoft 也在测试类似的“按价值付费”模型。ILC 联合创始人 Doug Leeds 提到，Mather Economics 的一份报告估计，集体授权未来可能为出版商带来相当于 AI 公司收入 15% 至 35% 的补偿。目前已有超过 3,000 家出版商加入该集体。

**「启示」** 对于广告平台或算法工程师，这确立了内容价值评估的新基准：内容不再是静态资产，而是根据对生成式响应的贡献度（如引用 vs. 简单检索）进行动态定价的信号。这预示着未来的 AI 搜索产品需要在系统层面集成更精细的内容溯源与计费逻辑，以应对日益复杂的授权合规性与成本结构。

**标签**: `#AI content licensing`, `#publisher monetization`, `#Yahoo`, `#pay-per-value`, `#RSL`

---

<a id="item-adtech-5"></a>
### [IAB 发布 AI 归因蓝图：平台数据不透明成标准化障碍](https://digiday.com/media/media-briefing-the-iab-finds-ai-measurement-standards-elusive-for-publishers-amid-platform-data-gaps/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 7.0/10

Digiday 报道，IAB 历时数月制定的《AI 时代归因蓝图》（AI-Era Attribution Blueprint）已发布，试图标准化衡量 AI 对转化的影响，但因 AI 平台内部数据不可见而受阻。Similarweb 数据显示，获得 AI 推荐的用户 7 天内访问品牌官网的可能性高 2.5 倍，但其中仅 8.8%来自 AI 直接引荐，55.9%被归因于搜索、19.9%归于直接流量。

rss · Media – Digiday · 11月12日 13:30

**「机制」** 归因断裂的根源在于推荐、决策甚至交易都发生在 AI 平台内部，曝光、点击和引荐数据对广告主与测量方不可见，AI 驱动的转化被错误记入搜索或直接流量，导致预算流向“捕获”转化而非“影响”转化的渠道。该蓝图提出三层框架：一是按意图（intent）、决策、交易三个环节分类由谁或何者完成；二是定义 AI 参与所产生的各类“主张”（claims）及各自所需证据；三是指出使这些主张难以验证的透明度与测量缺口。最典型的场景是出版商内容支撑了 AI 答案，但用户不点击引用链接，销售最终被零售商记为搜索或直接流量；训练数据中的内容无法从外部追溯，grounding 与引用相对可观察，但引用本身不能证明影响力，且缺少从源头信号到下游转化的连接。Profound 对浏览器会话数据的分析发现，三分之一消费者在购买前一个月内有未被归因的相关 AI 对话（数据未含 Google AI Mode 与 AI Overviews）。目前 Time 与 Mobian 合作测量面向 AI agent 的广告，Bustle Digital Group 与 Profound 合作测量 GEO campaign 效果，但这些只能覆盖局部环节，无法打通 AI 影响力与销售的链路。

**「背景」** 两个外部进展可能部分缓解数据缺口：英国竞争与市场管理局（CMA）要求 Google 在 12 月 3 日前向英国出版商提供其 AI 搜索功能的点击率数据；OpenAI 正在测试分析仪表板，让企业查看其在 ChatGPT 回答中的出现次数及带来的点击，但不披露具体 prompt、用户数据或竞品排名，仍给第三方 GEO 测量公司留下空间。

**「启示」** 对平台与算法工程师而言，AI 归因目前更多是对行业的“行动呼吁”而非可执行标准，核心缺口在于平台侧证据层的开放；出版商和品牌（如 Prudential 明确表示缺少平台第一方数据限制了其向 LLM 投放预算）都在等待平台数据落地，谁能率先提供可验证的意图-转化链路数据，谁就能在 GEO 与 AI 广告预算分配中占据优势。

**标签**: `#IAB`, `#AI attribution`, `#GEO`, `#AI search`, `#measurement`

---

## 经济观察

<a id="item-economics-1"></a>
### [技术创新是在巨大设计空间中搜索](https://www.construction-physics.com/p/technology-as-a-search-problem) ⭐️ 9.0/10

本文提出，理解技术进步的最佳方式是把“创造新技术”看作在极其庞大的技术可能性空间中搜索可行组合；这种搜索之所以可行，是因为人们不断获取信息来排除不可能方案。作者用自己的 PTOP 仿真模型说明，模块化与科学知识能显著缩小搜索范围。

rss · Construction Physics · 11月12日 13:01

**「观点」** 作者明确认为，新技术不是凭空出现，而是在一个包含所有可能部件、材料和自然现象组合的高维“技术空间”中逐步找到可行点。其核心主张是：创新本质上是搜索过程，而信息、模块化和科学知识是让这种搜索不至于被天文数字般的组合压垮的关键机制。

**「论证逻辑」** 作者先指出技术空间大到难以想象：仅以维基百科列出的 272 个方程估算，可能组合就超过 2^272，数量级已接近甚至超过可观测宇宙原子数。随后他说明，面对如此大的空间，人类靠信息逐层筛选：每一点有效知识都能排除大量错误方向。飞行器的例子用来说明，物理定律和鸟类的存在先缩小了范围，莱特兄弟又通过更强的信息收集能力更快收敛到可行设计。最后，PTOP 模型进一步显示，模块化能把一次猜中整体方案的难题，变成逐级锁定子方案的较短阶梯；科学知识则通过排除不可能组合来提升搜索效率。

**「概念解释」** 技术空间（technology space）指所有可能技术方案构成的集合；组合爆炸（combinatorial explosion）指可选元素稍多就会使总方案数急剧膨胀。模块化（modularity）是先找到并固定可复用的子部件，避免每次都从头整体设计；科学知识在这里被理解为能排除错误组合的信息。作者据此构建 PTOP 模型：技术由“现象、对象、属性”组成，合适对象以合适属性排列时触发自然现象，逐级链式反应形成可用技术。

**「背景」** 文章属于对创新经济学和技术演化理论的解释性建模尝试，借用了 Matt Clancy、Brian Arthur、Joel Mokyr 等人的思路，并用作者自己的仿真来研究“为什么有些技术容易发明、有些极难”。这对理解研发效率、科学转化为发明，以及复杂技术为何常靠逐步改进而非一次性完成很重要。

**标签**: `#innovation economics`, `#technological progress`, `#combinatorial design space`, `#science and invention`, `#simulation models`

---

<a id="item-economics-2"></a>
### [Uber 的劳动力危机：机器人出租车为何算不过账](https://pluralistic.net/2026/11/12/starvation-wages/) ⭐️ 8.0/10

Cory Doctorow 评论 Uber 的商业模式：其盈利依赖司机自带车辆并承受低于生存线的工资来补贴公司。他认为用昂贵的机器人出租车取代司机在经济上算不过账，Uber 正逼近极限。

rss · Pluralistic: Daily links from Cory Doctorow · 11月12日 20:50

**「观点」** 作者强烈批判 Uber，认为其成功建立在财务谎言、工资压榨和价格欺诈之上。他断定，转向自动驾驶车队是根本性误判：用公司需自购、维护和投保的高资本机器人，取代自带车辆、几乎免费供公司使用的绝望劳动者，只会让局面更糟。

**「论证逻辑」** 作者先指出 Uber 早年靠随意上调所持滴滴等失败对手股权的估值伪装盈利。IPO 后它真正实现盈利，手段是压低司机工资、提高乘客价格：司机只在载客时计酬，还要自担油费、保险、折旧和车贷，多伦多净时薪约 2.5 加元。如今三季度财报显示司机供给跟不上需求（印度、巴西尤其明显），CFO 的应对是对别处乘客涨价&quot;再平衡&quot;。作者推论：这种司机补贴不可持续；而单价约 20 万美元的机器人出租车远比&quot;司机自带车&quot;昂贵——GM Cruise 曾披露其用 1.5 名高薪工程师取代一名低薪司机。因此机器人救不了这个模式，Uber 将撞墙。

**「概念解释」** 算法工资歧视（algorithmic wage discrimination）：Uber 依据监控数据推断司机的经济窘迫程度，据此压到其愿接受的最低工资。监视定价（surveillance pricing）：按乘客数据算出每人愿付的最高价，对同样的行程差别收费。&quot;过早的真相&quot;（premature truth）：科技老板为谎言开脱的说辞，声称谎言很快会成真；作者认为 Uber 当年的盈利谎言后来靠压榨得以&quot;兑现&quot;，但机器人出租车不会。

**标签**: `#gig economy`, `#autonomous vehicles`, `#labor economics`, `#Uber`, `#platform economics`

---