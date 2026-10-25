---
layout: default
title: "Horizon Summary: 2026-10-25 (ZH)"
date: 2026-10-25
lang: zh
---

> 从 1 条内容中筛选出 1 条重要资讯。

---

**AI 深度解读**
1. [从零构建推理模型：Raschka 发布 8 集配套视频课程](#item-ai-deepdive-1) ⭐️ 7.0/10

---

## AI 深度解读

<a id="item-ai-deepdive-1"></a>
### [从零构建推理模型：Raschka 发布 8 集配套视频课程](https://magazine.sebastianraschka.com/p/building-reasoning-models) ⭐️ 7.0/10

rss · sebastianraschka.com · 10月24日 11:14

**「背景」** 推理模型已成为当前 LLM 的主流形态，但多数工程师对其实现机制了解有限。Sebastian Raschka 发布了一套 8 集、约 11 小时的免费视频课程，作为其新书《Build a Reasoning Model \(From Scratch\)》的配套内容。

**「解读」** 作者用&quot;引擎&quot;类比解释概念关系：推理模型是在传统 LLM 之上通过可验证奖励强化学习（RLVR）和可选的推理时扩展升级得到的&quot;引擎&quot;，而 agent harness 是围绕它的工具框架，负责上下文管理与工具调用。课程基于预训练的 Qwen3 0.6B 模型，用 Python 和 PyTorch 从零实现完整技术链路：先加载模型并实现流式生成、KV 缓存与 torch.compile；再逐步构建数学答案 verifier（答案提取、归一化、数学等价判断），它既用于 MATH-500 评估，也充当 RLVR 的奖励信号；随后实现推理时扩展技术，包括 temperature scaling、multinomial sampling、top-p filtering、self-consistency 多数投票、log 概率打分和 self-refinement 循环；核心部分是实现简化版 GRPO 训练循环，并进一步分析 clipped policy ratio、KL 损失项、format rewards 的作用及 reward hacking 风险；最后用 DeepSeek R1 生成的答案做蒸馏训练，作为 RL 之外的另一条路线，并在 MATH-500 上对比评估。早期示例可在 CPU 上运行，训练实验建议使用 GPU。

**「启示」** 作者认为动手从零实现仍是理解推理模型的最佳方式；这套视频配开源代码，让工程师能在普通硬件上亲自复现从评估、推理时扩展到 RLVR 与蒸馏的完整链路。

**标签**: `#reasoning models`, `#GRPO`, `#RLVR`, `#inference-time scaling`, `#distillation`

---