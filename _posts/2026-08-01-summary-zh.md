---
layout: default
title: "Horizon Summary: 2026-08-01 (ZH)"
date: 2026-08-01
lang: zh
---

> 从 13 条内容中筛选出 6 条重要资讯。

---

1. [“qm”多人代理工具的介绍](#item-1) ⭐️ 7.0/10
2. [DeepSeek V4 Flash 人工智能模型发布](#item-2) ⭐️ 7.0/10
3. [无状态 MCP 2.0 重新点燃了对模型上下文协议的兴趣](#item-3) ⭐️ 7.0/10
4. [Oxide 和朋友们讨论了 Simon Willison 的人工智能发展](#item-4) ⭐️ 7.0/10
5. [smevals：AI 模型评估的新工具](#item-5) ⭐️ 7.0/10
6. [datasette-agent 0.4a0 发布，支持在浏览器中执行 JavaScript](#item-6) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [“qm”多人代理工具的介绍](https://github.com/yc-software/qm) ⭐️ 7.0/10

“qm”多人代理工具被引入，引发了关于其协作潜力和“反模板”技能新颖性的讨论。 “qm”工具之所以重要，是因为它通过引入可以跨不同框架工作的多人代理工具，解决了软件工程和人工智能/机器学习中的协作挑战，并可能实现多渠道协作。 “反模板”技能因其能够从简介中推断设计方向并制作避免模板化外观的界面而受到关注，这表明了一种高端消费者体验。

hackernews · tosh · 7月31日 18:04 · [社区讨论](https://news.ycombinator.com/item?id=49126604)

**背景**: 多人代理是人工智能和软件工程中日益增长的趋势，旨在增强协作和生产力。它们在不同平台之间运行，并且可以同时与多个用户互动，需要复杂的上下文管理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://smithery.ai/skills/rand/anti-slop">anti-slop - Skill | Smithery</a></li>
<li><a href="https://github.com/jalaalrd/anti-ai-slop-writing">GitHub - jalaalrd/anti-ai-slop-writing: AI writing skill that eliminates detectable AI patterns. Works with Claude Code, Codex, Cursor, Gemini CLI, and 8+ other agents. · GitHub</a></li>
<li><a href="https://www.tasteskill.dev/">Taste Skill | The Anti-Slop Frontend Framework for AI Agents</a></li>

</ul>
</details>

**社区讨论**: 社区讨论显示了对“qm”工具的高度兴趣，评论集中在“反模板”技能的新颖性、多渠道协作的潜力，以及对多人代理发展方向的认可。

**标签**: `#AI`, `#ML`, `#Software Engineering`, `#Collaboration`, `#Innovation`

---

<a id="item-2"></a>
## [DeepSeek V4 Flash 人工智能模型发布](https://simonwillison.net/2026/Jul/31/deepseek-v4-flash-0731/#atom-everything) ⭐️ 7.0/10

拥有 3040 亿参数的 DeepSeek V4 Flash 人工智能模型已经发布，具备增强的能力和有竞争力的定价。 这一发布意义重大，因为它以低于 MiniMax M3（一个拥有 4280 亿参数的模型）的成本提供了更高的性价比。 DeepSeek V4 Flash 的定价为每百万输入 0.14 美元和每百万输出 0.27 美元，使其在智能指数与每任务成本智能指数图表上成为一个经济高效的选择。

rss · Simon Willison · 7月31日 23:59

**背景**: DeepSeek V4 Flash 是 DeepSeek V4 系列的一部分，作为一个总共拥有 2840 亿参数和 130 亿激活参数的 Mixture-of-Experts 模型开发，针对 1M 令牌上下文窗口进行了高效推理的优化。Hugging Face 是一个允许共享机器学习模型和数据集的平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash">deepseek -ai/ DeepSeek - V 4 - Flash · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hugging_Face">Hugging Face</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Deep Learning`, `#Hugging Face`, `#Artificial Intelligence`

---

<a id="item-3"></a>
## [无状态 MCP 2.0 重新点燃了对模型上下文协议的兴趣](https://simonwillison.net/2026/Jul/31/stateless-mcp/#atom-everything) ⭐️ 7.0/10

MCP 2.0，也就是无状态模型上下文协议的推出，是该协议自推出以来最重要的更新。这一发展重新点燃了作者的个人兴趣，并激发了新的工具和项目。 无状态 MCP 更新之所以重要，是因为它简化了客户端和服务器的实现，可能使 AI 应用程序更容易访问并与外部工具集成。这可能导致协议的更广泛采用，并增强 AI 系统之间的互操作性。 新的无状态规范通过消除会话管理的需求来降低复杂性，允许使用单个 HTTP 请求执行以前需要两个请求的操作。这一变化与更可扩展和可维护的 Web 应用程序的趋势相一致。

rss · Simon Willison · 7月31日 23:13

**背景**: 模型上下文协议（MCP）是由 Anthropic 在 2024 年 11 月引入的一个开放标准，用于标准化 AI 系统（如大型语言模型）与外部工具和数据源的集成。它面临着来自 Anthropic 的 Skills 的竞争，后者允许更灵活的代理利用，但代价是增加了复杂性和安全风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol</a></li>
<li><a href="https://modelcontextprotocol.io/">What is the Model Context Protocol (MCP)? - Model Context Protocol</a></li>

</ul>
</details>

**标签**: `#Model Context Protocol`, `#LLM`, `#Agent Frameworks`, `#Anthropic`, `#MCP 2.0`

---

<a id="item-4"></a>
## [Oxide 和朋友们讨论了 Simon Willison 的人工智能发展](https://simonwillison.net/2026/Jul/31/oxide-and-friends/#atom-everything) ⭐️ 7.0/10

Oxide 和朋友们播客邀请了 Simon Willison 讨论人工智能的最新进展，包括开放权重模型、网络安全事件和关于人工智能领导的公开信。 这个播客很重要，因为它提供了对人工智能技术当前状态和未来的见解，这是软件工程和系统研究的关键领域。 讨论的主题包括 Kimi K3 对开放权重模型能力的展示、意外的网络安全攻击以及由主要人工智能人物签署的关于美国人工智能领导的公开信的影响。

rss · Simon Willison · 7月31日 21:33

**背景**: 开放权重模型是公开发布的人工智能模型的学习参数，允许其他人下载和使用它们。讨论是及时的，因为它涵盖了人工智能透明度和可访问性的最新发展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Open-weight_model">Open-weight model</a></li>
<li><a href="https://www.microsoft.com/en-us/corporate-responsibility/topics/open-weight/">Open Weights and American AI Leadership</a></li>

</ul>
</details>

**标签**: `#AI`, `#Open Weight Models`, `#Cybersecurity`, `#Podcast`, `#AI Leadership`

---

<a id="item-5"></a>
## [smevals：AI 模型评估的新工具](https://simonwillison.net/2026/Jul/31/smevals/#atom-everything) ⭐️ 7.0/10

smevals，与 Jesse Vincent 的 Prime Radiant 合作开发，是一个新工具，旨在运行小型评估套件，覆盖各种 AI 模型配置并评估结果。 smevals 之所以重要，是因为它提供了一种结构化的方法来评估不同 AI 模型的性能，这可以帮助研究人员和开发人员了解模型能力，并就模型选择和改进做出明智的决策。 smevals 通过创建包含 YAML 文件和可执行脚本的评估套件来运行。它允许用户对这些套件进行模型运行和使用一组定义好的检查来评分，提供了 Web 服务器界面和静态 HTML 报告，以便探索结果。

rss · Simon Willison · 7月31日 21:15

**背景**: smevals 是更广泛的 AI 研究生态系统的一部分，在这里准确评估模型性能至关重要。它建立在评估框架的先前迭代基础上，旨在简化评估 AI 模型针对特定任务或挑战的过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/prime-radiant-inc/smevals">GitHub - prime-radiant-inc/ smevals : A framework for running evals ...</a></li>
<li><a href="https://primeradiant.com/blog/2026/smevals.html">smevals - a small eval suite for evaluating models... | Prime Radiant</a></li>

</ul>
</details>

**标签**: `#AI`, `#Evaluation`, `#Model Testing`, `#Tool`, `#Prime Radiant`

---

<a id="item-6"></a>
## [datasette-agent 0.4a0 发布，支持在浏览器中执行 JavaScript](https://simonwillison.net/2026/Jul/31/datasette-agent/#atom-everything) ⭐️ 7.0/10

Datasette-agent 0.4a0 版本引入了一个新的特性，允许通过`await context.browser_task()`机制直接在用户的浏览器中执行自定义 JavaScript 代码。 这一增强功能意义重大，因为它使得 Datasette Agent 插件能够提供在用户浏览器中运行 JavaScript 的工具，可能会改变基于浏览器的工具开发和与 Datasette 集成的格局。 新机制允许以安全和受控的方式执行 JavaScript，利用浏览器的原生能力，同时保持 Datasette 数据处理的完整性。

rss · Simon Willison · 7月31日 14:14

**背景**: Datasette 是一个用于发布和探索数据的开源工具。Datasette Agent 是一个扩展，提供了一个用于查询数据的会话界面，插件扩展了其功能，比如生成图表。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/May/21/datasette-agent/">Datasette Agent</a></li>
<li><a href="https://github.com/datasette/datasette-agent">GitHub - datasette/datasette-agent: An LLM-powered agent for Datasette · GitHub</a></li>

</ul>
</details>

**标签**: `#datasette`, `#browser`, `#javascript`, `#plugins`, `#tools`

---