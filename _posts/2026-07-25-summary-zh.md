---
layout: default
title: "Horizon Summary: 2026-07-25 (ZH)"
date: 2026-07-25
lang: zh
---

> 从 15 条内容中筛选出 4 条重要资讯。

---

1. [Anthropic 发布 Claude Opus 5 AI 模型](#item-1) ⭐️ 7.0/10
2. [Postgres LISTEN/NOTIFY 展示可扩展性](#item-2) ⭐️ 7.0/10
3. [Opus 5 登顶人工智能分析排行榜](#item-3) ⭐️ 7.0/10
4. [安全摄像头登录页面内置 GitHub 管理员令牌](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Anthropic 发布 Claude Opus 5 AI 模型](https://www.anthropic.com/news/claude-opus-5) ⭐️ 7.0/10

Anthropic 发布了新的 AI 模型 Claude Opus 5，该模型不需要数据保留，允许组织访问类似 Fable 的模型而无需遵守 30 天数据保留政策。 Claude Opus 5 的发布意义重大，因为它为 Fable 提供了一个限制更少的替代品，可能会影响关心数据保留政策的组织选择 AI 模型。 Opus 5 保留了其前身 4.8 的'Claude-isms'，并在图像到 HTML 转换等任务中以更高的准确性超越了 Fable 和 Gemini 3.1 Pro。

hackernews · alvis · 7月24日 16:57 · [社区讨论](https://news.ycombinator.com/item?id=49038433)

**背景**: Claude 是由 Anthropic 开发的一系列大型语言模型，以其“宪法 AI”方法提高道德和法律合规性而闻名。随着隐私要求的扩展，AI 中的数据保留政策变得越来越重要，AI 系统生成的各种类型的数据需要不同的保留考虑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://iapp.org/resources/article/creating-a-data-retention-policy-for-personal-information-and-ai">Creating a data retention policy for personal information and AI</a></li>
<li><a href="https://gimmal.com/data-retention-policies-in-the-ai-era-whats-changing/">Data Retention Policies in the AI Era: What's Changing?</a></li>
<li><a href="https://www.pertamapartners.com/insights/ai-data-retention-policies-how-long-keep-what">AI Data Retention Policies Guide | Pertama Partners</a></li>

</ul>
</details>

**社区讨论**: 用户正在比较 Opus 5 与 Fable 和 Gemini 3.1 Pro 的性能，指出 Opus 5 似乎更准确地遵循设计源真实性。然而，一些用户在使用 Opus 5 进行代码计划审查时遇到了错误。

**标签**: `#AI`, `#Anthropic`, `#Claude Opus 5`, `#Fable`, `#Community Discussion`

---

<a id="item-2"></a>
## [Postgres LISTEN/NOTIFY 展示可扩展性](https://www.dbos.dev/blog/postgres-listen-notify-scalability) ⭐️ 7.0/10

一个案例研究表明，Postgres LISTEN/NOTIFY 能够在一台强大的机器上处理高达 60K 每秒的写入量，显著提高了之前的性能限制。 这种可扩展性的提高对于依赖 Postgres 进行实时数据流和进程间通信的数据库管理员和开发人员至关重要，因为它允许在不降低性能的情况下处理更高的负载。 该研究在一台拥有 96 个 vCPU 和 384GB RAM 的机器上进行，实现了 20k 的写入量，并在优化后扩展到 60k，对于这样的机器来说，这是一个相当大的吞吐量。

hackernews · KraftyOne · 7月24日 19:05 · [社区讨论](https://news.ycombinator.com/item?id=49040296)

**背景**: Postgres LISTEN/NOTIFY 是一个允许在同一数据库内进行进程间通信的功能。它传统上被视为在可扩展性方面有限，但这个案例研究通过展示显著的性能改进挑战了这种观念。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.postgresql.org/docs/current/sql-notify.html">PostgreSQL: Documentation: 18: NOTIFY</a></li>
<li><a href="https://www.postgresql.org/docs/current/sql-listen.html">PostgreSQL: Documentation: 18: LISTEN</a></li>
<li><a href="https://www.dbos.dev/blog/postgres-listen-notify-scalability">Postgres LISTEN/NOTIFY Actually Scales | DBOS</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了根据扩展需求选择技术的重要性，一些人认为使用具有错误扩展因子的技术是一个常见错误。同时，也有人对 DBOS 有效利用 Postgres 的方法表示赞赏。

**标签**: `#Postgres`, `#Scalability`, `#Database`, `#LISTEN/NOTIFY`, `#Performance`

---

<a id="item-3"></a>
## [Opus 5 登顶人工智能分析排行榜](https://artificialanalysis.ai/models) ⭐️ 7.0/10

Opus 5 成为人工智能分析排行榜上的首位，引发了关于模型可靠性和成本效益的讨论。 这一变化反映了当前 AI 模型性能的最新状态，并提供了哪些模型在智能能力方面领先的见解，影响着 AI 的采纳和发展。 特别是'Adaptive Reasoning, Max Effort'版本的 Opus 5 在 170 个模型中得分 61，显示了高水平的性能。然而，它也因比其他模型更昂贵和更慢而被指出。

hackernews · aarondong · 7月24日 19:45 · [社区讨论](https://news.ycombinator.com/item?id=49040741)

**背景**: 人工智能分析排行榜是一个综合基准，它衡量 AI 在包括数学、科学、编码和推理在内的各种评估中的能力。它提供了一个全面的模型性能视图，以跟踪 AI 的进步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/leaderboards/models">LLM Leaderboard - Comparison of AI models from OpenAI ...</a></li>
<li><a href="https://www.datalearner.com/en/leaderboards/external/aa-quality-index">Artificial Analysis Intelligence Index - AI Model Leaderboard ...</a></li>
<li><a href="https://venturebeat.com/orchestration/anthropic-launches-claude-opus-5-a-cheaper-ai-model-for-coding-agents-and-enterprise-workflows">Anthropic launches Claude Opus 5, a cheaper AI model for coding, agents and enterprise workflows | VentureBeat</a></li>

</ul>
</details>

**社区讨论**: 社区成员正在讨论模型得分与实际可用性之间的权衡，一些人对审查和成本表示担忧。关于高分与可靠性及成本效益之间的价值也存在争论。

**标签**: `#AI`, `#Artificial Intelligence`, `#Leaderboard`, `#Opus 5`, `#Model Comparison`

---

<a id="item-4"></a>
## [安全摄像头登录页面内置 GitHub 管理员令牌](https://hhh.hn/hanwha-github-token/) ⭐️ 7.0/10

发现一款安全摄像头在其登录页面中硬编码了一个 GitHub 管理员令牌，暴露了一个严重的安全漏洞。 这一事件突显了物联网设备中普遍存在的不良安全实践，可能使敏感数据和系统暴露于未经授权的访问之下。 硬编码的 GitHub 管理员令牌可能赋予攻击者对组织 GitHub 仓库的管理员访问权限，允许操纵代码并可能部署恶意软件。

hackernews · hhh · 7月24日 11:54 · [社区讨论](https://news.ycombinator.com/item?id=49034292)

**背景**: 包括安全摄像头在内的物联网设备，由于快速发展周期和对功能而非安全性的关注，常常缺乏强大的安全措施。这可能导致诸如硬编码凭证之类的漏洞，这是一个重大风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IoT_security">IoT security</a></li>
<li><a href="https://www.fortinet.com/resources/cyberglossary/iot-security">What is IoT Security? Definition and Challenges of IoT Security | Fortinet</a></li>

</ul>
</details>

**社区讨论**: 用户对物联网设备的安全性表示担忧，一些人建议为摄像头使用单独的 VLAN，其他人强调了产品开发中需要更好的安全实践。

**标签**: `#security`, `#IoT`, `#GitHub`, `#camera`, `#cybersecurity`

---