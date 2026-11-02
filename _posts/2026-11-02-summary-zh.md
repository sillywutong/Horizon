---
layout: default
title: "Horizon Summary: 2026-11-02 (ZH)"
date: 2026-11-02
lang: zh
---

> 从 23 条内容中筛选出 4 条重要资讯。

---

**广告技术**
1. [AI Overviews 挤压搜索点击，买家重审 Google 搜索预算](#item-adtech-1) ⭐️ 8.0/10
2. [AI 标签无法告诉消费者广告宣称是否真实](#item-adtech-2) ⭐️ 7.0/10

**LLM 与 Agent**
1. [看不见数据时如何构建法律智能体](#item-ai-agentic-1) ⭐️ 7.0/10

**经济观察**
1. [自动开盒：反隐私政策如何催生 AI 恶意软件](#item-economics-1) ⭐️ 7.0/10

---

## 广告技术

<a id="item-adtech-1"></a>
### [AI Overviews 挤压搜索点击，买家重审 Google 搜索预算](https://digiday.com/marketing/google-search-loses-its-free-pass-with-buyers/?utm_campaign=digidaydis&amp;utm_medium=rss&amp;utm_source=general-rss) ⭐️ 8.0/10

Digiday 采访 18 位媒体买家后报道称，AI Overviews 和 AI Mode 正在压缩搜索点击供给并推高 CPC，买家开始用 MMM 和增量测试重审 10%-30%的 Google 搜索预算，部分资金转向 Meta、TikTok 及 Google 自有 AI 投放产品。

rss · Marketing – Digiday · 11月2日 05:01

**「机制」** AI Overviews 在结果页直接回答查询，减少点击进入广告主页面的机会，优质广告位收缩；Google 自动化出价工具对剩余流量竞价抬价，Q4 季节性竞争进一步推高 CPC——Tinuiti 称 Q3 品牌词 CPC 同比上涨约 5%。供给端同时收缩：Alphabet Q3 搜索广告收入增速降至 12%，为年内最低，高管将部分放缓归因于 AI Mode。测量端，买家以 MMM、geo-testing 和 incrementality 测试重新分配归因：Power Digital 称模型把更多转化功劳归给上层漏斗，削弱搜索末次点击优势。Accuracast 的 AI 投放平台 Unyte.AI 在 ROI 走弱时自动把预算从 Google 迁往能产生增量转化的渠道。Tinuiti 观察到客户削减竞品词（conquesting）等低效搜索投放，Q3 其美国客户 Facebook 投放增长 16%；部分买家则将预算留在 Google 体系内转向 AI Max、PMax、YouTube。

**「背景」** IAB 与 PwC 数据显示，搜索去年占美国数字广告支出 1142 亿美元（38.8%），仍是多数媒体计划最大单项，中大型广告主的月搜索预算从数万到数百万美元不等。

**「启示」** 搜索广告的自动豁免地位正在瓦解：点击供给受 AI 回答挤压、CPC 上行，增量测量使末次点击归因不再构成护城河。平台工程师需要正视广告主会以增量回报而非转化量来要求预算证明，并观察预算在 Meta、TikTok 与 Google AI 投放产品间的再分配。

**标签**: `#Google`, `#AI Overviews`, `#incrementality`, `#media mix modeling`, `#paid search budgets`

---

<a id="item-adtech-2"></a>
### [AI 标签无法告诉消费者广告宣称是否真实](https://www.adexchanger.com/data-driven-thinking/ai-labels-dont-tell-consumers-whether-an-ads-claims-are-real/) ⭐️ 7.0/10

AdExchanger 客座专栏文章（作者 Sourin Chakrabarti 在 Meta 从事广告 AI 标注工作，强调观点属个人）论证：当前通用的 AI 生成标签只标示制作工具，无法告诉消费者合成内容是否伪造了产品宣称的证据。文章引用 Sora 伪造执法视频、假冒 NHS 医生的减肥贴广告等案例，并提出基于风险分级的披露框架。

rss · AdExchanger: News and Views on Data-Driven Digital Advertising · 11月2日 05:25

**「机制」** 核心判断标准借用 FTC v. Colgate-Palmolive 判例（当年用树脂玻璃冒充砂纸演示剃须膏效果）：广告是仅仅&quot;示意&quot;一个宣称，还是把合成场景当作真实世界的证据？作者调查现有体系——Google 的&quot;How this ad was made&quot;面板、Meta 的&quot;AI info&quot;标签、TikTok 的 AIGC 自披露控件，以及欧盟 Article 50、中国强制 AI 标识、纽约合成表演者规则——指出它们只回答&quot;是否用了 AI&quot;，同一标签既覆盖装饰性背景也覆盖伪造证言，误导程度却天差地别。作者基于 IAB 2026 年 1 月披露框架提出三级处理：常规修图与装饰性背景不加警示；可能被误认为真实证据的合法合成内容必须说明性质（如&quot;经核实客户证言的 AI 重演&quot;&quot;模拟演示，性能宣称基于实验室测试&quot;）；伪造背书、虚构专家意见、无据结果则直接拒审。落地机制是要求广告主申报三项信息：AI 生成人物或场景的角色、素材是否展示产品性能或效果、支持宣称的真实证据；平台留存申报答案与向消费者展示的告知，形成可审计的&quot;served disclosure receipt&quot;。紧迫性来自规模：据文章引述，2025 年广告主在 Google 创建的 Gemini 生成素材是 2024 年的三倍，仅第四季度就近 7000 万条，Meta 据报道目标在 2026 年底前实现广告创建与投放的 AI 自动化，因此仅靠事后投诉的治理不可行。

**「启示」** 对平台工程师而言，这一框架若获监管采纳，披露义务将从统一水印/标签转向按风险分级的声明式申报加审计留痕，且需前置嵌入广告创建与审核工作流。需注意该方案属规范性建议，未经实证检验，部分执法案例也未给出详细来源。

**标签**: `#AI labeling`, `#synthetic media`, `#ad disclosure`, `#FTC`, `#Meta`

---

## LLM 与 Agent

<a id="item-ai-agentic-1"></a>
### [看不见数据时如何构建法律智能体](https://latent.space/p/building_legal_agents_when_you_can_t_see_the_data_-_jacob_lauritzen_cto_of_legora/) ⭐️ 7.0/10

Latent Space 采访 Legora CTO Jacob Lauritzen，探讨在无法访问客户数据（数据归律所客户所有）的严格隐私约束下，如何构建、测试和部署法律 AI 智能体。Legora 采用合成测试环境、引用系统和表格化审查工作流来解决这一核心矛盾。

rss · Latent Space · 11月2日 22:54

**「要点」** Legora 从斯德哥尔摩地下室起步，现已支持律师起草 Word 文档、在单一表格中审查 10,000 份合同，并协调律师、客户与其他智能体的工作。核心机制包括：由三名工程师与三名律师构建模拟客户工作的测试环境（类似强化学习中的 &quot;worlds&quot;）；通过改写（paraphrase）痕迹分析将失败案例归纳为 10-20 种类型，以在无法读取原始轨迹的前提下进行产品迭代；以及模仿 RL 世界模型的模拟数据室（含 10,000 份文件）用于验证智能体表现。技术架构上，出于数据隐私考虑，Legora 将所有服务运行在 Azure 上，不使用 ElevenLabs。产品方面，其 Tabular Review（百万单元格电子表格）被行业广泛模仿，支持通过列表创建智能体、智能体再生成列表的链式工作流。模型策略上，Legora 曾长期拒绝提供模型选择器，现已添加；Jacob 估计当前模型可完成约 60% 的法律工作，引用准确率在特定版本发布后从 70% 提升至 99%。团队规模从原计划保持 20 名工程师（&quot;300 Spartans&quot; 幻灯片）扩展至 100 人，并区分法律工程师与前线部署工程师（forward-deployed engineers）的分工协作。

**「启示」** 在数据不可见的合规场景中，可通过构建基于客户工作模式的合成测试环境、利用改写后的痕迹进行 failure mode 分析，以及采用表格化界面来突破评估与调试的瓶颈。

**标签**: `#legal agents`, `#evaluation`, `#data privacy`, `#agent workflow`, `#retrieval`

---

## 经济观察

<a id="item-economics-1"></a>
### [自动开盒：反隐私政策如何催生 AI 恶意软件](https://pluralistic.net/2026/11/02/agony-verification/) ⭐️ 7.0/10

Cory Doctorow 评论称，新型 Volta 窃密恶意软件能借助 AI 像情报分析师一样自动整理受害者档案（他称之为“自动开盒”），而其威力来自几十年来政策刻意敌视隐私所积累的海量泄露数据。他认为这不是意外灾难，而是可预见且被预见到的政策后果。

rss · Pluralistic: Daily links from Cory Doctorow · 11月2日 08:20

**「观点」** 作者措辞强烈地认为：从克林顿政府的 Clipper 芯片、NSA 对民用加密的禁令，到加、英、欧如今仍想禁用有效加密，政策制定者长期把“方便监控坏人”置于公众安全之上，应对今日 AI 放大的黑客灾难负责。他批评年龄验证法案本质是全民监控，并把数据比作“沾油的破布”——只有堆积牟利、失火后由社会买单。他主张以大幅提高数据收集的法律成本、合法化隐私拦截工具、对泄露企业施以“公司死刑”、拆除 9·11 后的数据融合中心等措施扭转局面。

**「论证逻辑」** 作者的因果链是：禁用或削弱加密、反规避法禁止逆向工程加装隐私保护、隐私立法缺位（美国联邦消费者隐私法自 1988 年未更新）或执法落空（欧盟“假装在爱尔兰”），共同导致企业无节制囤积数据且保管不善。Equifax 泄露 1.48 亿人数据后仍获准在美、加、巴西继续收购同业，说明违规成本只是零花钱。Volta 的运作印证了这条链：受害者电脑被入侵后，恶意软件把窃得数据与 Ticketmaster、AT&amp;T 等旧泄露库合并，用大模型生成“带引用的结构化评估”，按预期收益给受害者排序并精准钓鱼，还特别瞄准 Discord、Roblox 等青少年平台。作者强调危害有“长引信”——从 9·11 后的数据汇聚到 ICE 的执法，从社保号泄露到 DOGE 人员窃取社保数据，因果被时间隔开，政客因此借“政治的永恒当下”推卸责任。

**「概念解释」** 自动开盒（autodoxing）指恶意软件在入侵的同时自动完成传统上由人肉搜索者做的工作：汇总目标的身份信息并生成可利用的档案。加密后门（backdoor）指为执法预留的访问通道，作者引用澳大利亚前总理特恩布尔“数学定律在澳大利亚不适用”的名言说明：任何能让警方进入的通道同样能被罪犯利用。反规避法（anticircumvention）则禁止用户逆向自己的设备来加隐私保护，等于把监控固化进每个应用。

**标签**: `#surveillance economics`, `#data breaches`, `#tech policy`, `#encryption`, `#AI-enabled cybercrime`

---