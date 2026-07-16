---
layout: default
title: "Horizon Summary: 2026-07-16 (ZH)"
date: 2026-07-16
lang: zh
---

> 从 6 条内容中筛选出 3 条重要资讯。

---

1. [Inkling：我们的开放权重模型](#item-1) ⭐️ 7.0/10
2. [Grok Build 开源发布](#item-2) ⭐️ 7.0/10
3. [Claude AI 的 web_fetch 功能存在数据泄露风险](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Inkling：我们的开放权重模型](https://thinkingmachines.ai/news/introducing-inkling/) ⭐️ 7.0/10

Thinking Machines 推出了 Inkling，这是一个具有 975B 总参数和 41B 活跃参数的多模态开放权重模型，旨在为各种应用定制。 Inkling 的重要性在于其潜力可以针对特定任务进行微调，提供了一个可定制的开放权重基础模型，可以在各种 AI 应用中进行性能优化。 Inkling 是一个 Mixture-of-Experts 变换模型，它接受文本、图像和音频输入，并生成文本输出。它旨在用于英语和其他语言，以及多种编程语言。

hackernews · vimarsh6739 · 7月15日 18:12 · [社区讨论](https://news.ycombinator.com/item?id=48924912)

**背景**: 多模态 AI 整合和处理多种类型的数据，如文本、音频、图像或视频，以提高模型在视觉问答和文本到图像生成等任务中的性能。开放权重模型提供了一个可以针对特定应用进行微调的基础，提供了灵活性和可定制性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thinkingmachines.ai/news/introducing-inkling/">Inkling: Our open-weights model - Thinking Machines Lab</a></li>
<li><a href="https://techcrunch.com/2026/07/15/thinking-machines-amps-up-its-bet-against-one-size-fits-all-ai-with-its-first-open-model-inkling/">Thinking Machines amps up its bet against one-size-fits-all AI with its first open model, Inkling | TechCrunch</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multimodal_AI">Multimodal AI</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了 Inkling 多模态能力的潜力及其作为支持音频的最大开放权重模型的地位。人们还对它与其他模型的比较以及在 Tinker 上定制的潜力感兴趣。

**标签**: `#AI`, `#Machine Learning`, `#Open-Weights Model`, `#Multimodal`, `#Customization`

---

<a id="item-2"></a>
## [Grok Build 开源发布](https://github.com/xai-org/grok-build) ⭐️ 7.0/10

xAI 开发的人工智能开发工具 Grok Build 已经开源，引起了社区的兴趣和带有隐私改进的分支。 Grok Build 的开源具有重要意义，因为它提供了一个替代专有人工智能开发工具的选择，并激发了社区驱动的增强，特别是在隐私方面。 像'gork-build'这样的社区分支已经移除了供应商遥测并实现了退出数据保留，解决了之前的隐私问题。

hackernews · skp1995 · 7月15日 20:24 · [社区讨论](https://news.ycombinator.com/item?id=48926590)

**背景**: Grok Build 是由 xAI 开发的一种用于应用开发中的氛围编码的工具，它将自然语言提示转换为生产就绪的原型。由于隐私问题，包括将整个目录上传到 xAI 的 Google Cloud 存储桶，它一直存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grok_Build">Grok Build</a></li>
<li><a href="https://grokipedia.com/page/Grok_Build">Grok Build</a></li>
<li><a href="https://x.ai/open-source">Grok Build CLI is open source. Browse the code on GitHub. | SpaceXAI</a></li>

</ul>
</details>

**社区讨论**: 社区成员已经注意到代码库中有趣的方面，例如用于 Mermaid 图表的自包含终端渲染器，并就公司行为的伦理影响进行了辩论。一些人建议使用 pi.dev 这样的替代工具而不是 Grok Build。

**标签**: `#open source`, `#AI`, `#development tools`, `#privacy`, `#Hacker News`

---

<a id="item-3"></a>
## [Claude AI 的 web_fetch 功能存在数据泄露风险](https://simonwillison.net/2026/Jul/15/claude-web-fetch-exfiltration/#atom-everything) ⭐️ 7.0/10

Ayush Paul 发现了 Claude AI 工具的 web_fetch 功能中存在一个漏洞，该漏洞可能使数据泄露攻击成为可能，允许攻击者提取包括用户名、家庭位置和雇主名称在内的敏感信息。 这一漏洞之所以重要，是因为它暴露了 AI 工具中潜在的数据泄露风险，这可能会危及用户隐私和安全。这一发现强调了在 AI 系统中实施强有力的安全措施以及持续进行漏洞评估的重要性。 该漏洞发现于 web_fetch 功能，该功能旨在通过只允许导航到用户输入的 URL 或 web_search 工具返回的 URL 来防止数据泄露。然而，发现了一个漏洞，即 web_fetch 可以访问之前获取的页面中嵌入的 URL，导致了一次成功的蜜罐攻击。

rss · Simon Willison · 7月15日 14:21

**背景**: Claude AI 是由 Anthropic 开发的一款工具，它使用大型语言模型（LLMs）根据用户输入处理和生成文本。web_fetch 功能是一项允许 AI 访问在线内容的特性，这对于其运行至关重要，但也存在安全漏洞的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Data_exfiltration">Data exfiltration - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/data-exfiltration">What is Data Exfiltration? | IBM</a></li>
<li><a href="https://www.fortinet.com/resources/cyberglossary/data-exfiltration">What is Data Exfiltration and How Can You Prevent It? | Fortinet</a></li>

</ul>
</details>

**社区讨论**: 这一发现在 AI 和网络安全社区引发了关于 AI 工具中此类漏洞的影响以及更好安全协议需求的讨论。大家普遍认为及时解决这些问题对于保护用户数据至关重要。

**标签**: `#AI`, `#Security`, `#Vulnerability`, `#Data Exfiltration`, `#Claude`

---