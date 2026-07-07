---
layout: default
title: "Horizon Summary: 2026-07-07 (ZH)"
date: 2026-07-07
lang: zh
---

> 从 9 条内容中筛选出 6 条重要资讯。

---

1. [腾讯发布 295B 参数混合专家模型 Hy3](#item-1) ⭐️ 8.0/10
2. [OpenWrt One——开源硬件路由器发布](#item-2) ⭐️ 7.0/10
3. [GLM 5.2 发布及其对 AI 利润率的影响](#item-3) ⭐️ 7.0/10
4. [在语言模型中探索“全球工作空间”](#item-4) ⭐️ 7.0/10
5. [sqlite-utils 4.0rc3 发布](#item-5) ⭐️ 7.0/10
6. [Fable 将 reMarkable 变成汤姆·里德尔的日记](#item-6) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [腾讯发布 295B 参数混合专家模型 Hy3](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

腾讯发布了一个新的 295B 参数混合专家（MoE）模型，名为 Hy3，其性能超越了同类大小的模型，并且可以在 OpenRouter 上免费使用。 Hy3 的发布意义重大，因为它代表了人工智能和机器学习领域的一个重要进步，提供了在各种应用中改进的性能和实用性。它在 OpenRouter 上的免费可用性增加了可访问性，并可能加速该领域的创新。 Hy3 拥有 21B 个活跃参数和 3.8B 个 MTP 层参数。它在 Apache 2.0 许可下发布，并在各种产品和生产力任务中显示出显著的实用性提升。全尺寸模型为 598GB，FP8 量化版本为 300GB，上下文长度为 256K。

rss · Simon Willison · 7月6日 23:57

**背景**: 混合专家（MoE）模型是一种神经网络架构，利用专门的子网络池，每个标记只激活一个子集，以平衡模型容量和计算效率。OpenRouter 是一个平台，简化了各种提供商的大型语言模型的集成和管理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deeptechstars.substack.com/p/mixture-of-experts-explained-plus">Mixture - of - Experts , explained - plus OpenAI's new models that cost...</a></li>
<li><a href="https://kimi-k2.org/">Kimi K2 - Open Source AI Model | 1T Parameters | K2.7 Code</a></li>
<li><a href="https://www.linkedin.com/pulse/day-14-glam-googles-mixture-of-experts-model-efficient-durai-siujc">Day 14: GLaM – Google's Mixture - of - Experts Model for Efficient...</a></li>
<li><a href="https://grokipedia.com/page/openrouter">OpenRouter</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Mixture-of-Experts`, `#Tencent`, `#OpenSource`

---

<a id="item-2"></a>
## [OpenWrt One——开源硬件路由器发布](https://openwrt.org/toh/openwrt/one) ⭐️ 7.0/10

OpenWrt 项目宣布了一款开源硬件路由器 OpenWrt One。这款路由器延长了路由器的使用寿命，提供了比商业选项更多的功能，并旨在实现透明和可定制化。 OpenWrt One 路由器之所以重要，是因为它提供了一个开源的商业路由器替代品，提供了更多的灵活性和功能。这可以为用户带来更安全、更可定制的网络体验，特别是那些重视开源软件的用户。 OpenWrt One 旨在与各种硬件配合使用，并提供超过 9000 个可选软件包供安装。它可以通过命令行界面或 Web 界面进行配置，并且可以运行在 CPE 路由器、住宅网关和 SBC 等设备上。

hackernews · peter_d_sherman · 7月6日 18:23 · [社区讨论](https://news.ycombinator.com/item?id=48808482)

**背景**: OpenWrt 是基于 Linux 的嵌入式操作系统的开源项目，主要用于嵌入式设备来路由网络流量。它以其广泛的定制选项和活跃的社区支持而闻名。OpenWrt One 路由器是向提供透明和可定制的网络硬件解决方案迈出的一步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenWrt">OpenWrt</a></li>
<li><a href="https://eucloudservers.com/networking-performance/openwrt-one-open-hardware-router/">OpenWrt One – Open Hardware Router - EU Cloud Servers</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的用户分享了他们使用 OpenWrt 的经验，强调了它能够延长路由器的使用寿命并获得额外的功能。一些用户将其与其他开源路由器选项如 OPNSense 进行了比较，而其他用户则讨论了 OpenWrt One 的价格和硬件规格。

**标签**: `#OpenWrt`, `#Router`, `#Open Source`, `#Hardware`, `#Networking`

---

<a id="item-3"></a>
## [GLM 5.2 发布及其对 AI 利润率的影响](https://martinalderson.com/posts/the-upcoming-ai-margin-collapse-part-1-glm-5-2/) ⭐️ 7.0/10

中国人工智能公司 Z.ai 发布了其通用语言模型 GLM 的新版本 5.2，预计这将通过增加竞争和潜在降低利润率，对 AI 行业产生重大影响。 GLM 5.2 的发布之所以重要，是因为它引入了一个强大的开源替代品，可能由于竞争加剧和成本降低，导致 AI 推理利润率的崩溃。 GLM 5.2 拥有 744B 参数，其中 40B 为活跃参数，并且拥有 1M 上下文窗口，提供长视野编码、推理和代理任务的最新性能。它被认为是 Opus 和 GPT 模型的真正竞争对手，成本仅为其一小部分。

hackernews · martinald · 7月6日 20:14 · [社区讨论](https://news.ycombinator.com/item?id=48809877)

**背景**: Z.ai，原名 Zhipu AI，是一家专门从事人工智能的中国技术公司，以其 GLM 系列大型语言模型而闻名。该公司已经重新品牌化，并被认为是中国领先的“人工智能老虎”公司之一。GLM 模型在 MIT 许可下发布，使它们免费且开源，这是它们潜在颠覆 AI 市场的一个重要因素。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GLM_5.2">GLM 5.2</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://theaicronicle.com/en/news/economics/ai-trade-losing-key-signals-margin-crisis">AI Trade Crisis: Falling Profit Margins and Market ROI — The AI Chronicle</a></li>

</ul>
</details>

**社区讨论**: 社区讨论反映了对 GLM 5.2 影响的一系列观点。一些人认为，与市场主导地位相比，原始成本并不那么重要，而其他人则强调非串谋在维持竞争市场中的重要性。还有一种观点认为，包括 GLM 5.2 在内的人工智能正变得越来越经济高效和能力强，这可能会压低代币经济和利润。

**标签**: `#AI`, `#GLM`, `#industry`, `#competition`, `#margins`

---

<a id="item-4"></a>
## [在语言模型中探索“全球工作空间”](https://www.anthropic.com/research/global-workspace) ⭐️ 7.0/10

Anthropic 提出了一个名为“全球工作空间”的新概念，以增强语言模型的能力，并与认知科学理论相联系。 这种方法可能会显著影响人工智能/机器学习领域，通过提供一个新的框架来理解和改进大型语言模型，可能导致更有效和认知准确的人工智能系统。 “全球工作空间”概念被比作神经网络中的传输通道，“j-lens”则作为读取器来解释信息流，表明了一种通过操作内部表示来改变模型输出的机制。

hackernews · in-silico · 7月6日 17:44 · [社区讨论](https://news.ycombinator.com/item?id=48808002)

**背景**: 全球工作空间理论（GWT）由认知科学家伯纳德·巴尔斯提出，是一个用于理解意识和高阶认知的框架。它表明意识是从大脑中一个集成并广播信息的中心机制中产生的。大型语言模型（LLM）是为自然语言处理任务而训练的神经网络，处理大量文本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Global_workspace_theory">Global workspace theory</a></li>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映出好奇和怀疑的混合态度。一些用户质疑“全球工作空间”概念直接应用于语言模型的适用性，而其他用户则将其与过去的实验和模型能力的提升联系起来。

**标签**: `#AI`, `#ML`, `#language models`, `#cognitive science`, `#neural networks`

---

<a id="item-5"></a>
## [sqlite-utils 4.0rc3 发布](https://simonwillison.net/2026/Jul/6/sqlite-utils/#atom-everything) ⭐️ 7.0/10

sqlite-utils 4.0rc3 引入了复合外键和不区分大小写的列名支持。 这次更新非常重要，因为它增强了 sqlite-utils 的功能，使其在数据库管理方面更加强大，特别是复合外键的增加可以提高数据完整性。 更新包括对`table.foreign_keys` API 的微妙破坏性更改，这对于支持复合外键是必要的。此外，sqlite-utils 现在遵循 SQLite 的不区分大小写列名约定，影响工具的多个领域。

rss · Simon Willison · 7月6日 05:40

**背景**: sqlite-utils 是一个设计用于与 SQLite 数据库一起工作的工具，提供了一系列实用工具以更高效地管理和交互数据库。它因其简单和在处理 SQLite 数据库方面的有效性而被广泛使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://abridger.readthedocs.io/en/v0.1.0/examples_compound_foreign_keys/">Compound Foreign Keys — abridger 0.1.0 documentation</a></li>
<li><a href="https://medium.com/@me.sonu300/how-to-solve-the-postgresql-column-name-case-sensitivity-41409b6f612d">How to solve the PostgreSQL column name case sensitivity | Medium</a></li>

</ul>
</details>

**标签**: `#database`, `#SQLite`, `#release`, `#tooling`, `#database management`

---

<a id="item-6"></a>
## [Fable 将 reMarkable 变成汤姆·里德尔的日记](https://github.com/MaximeRivest/Riddle) ⭐️ 6.0/10

一个名为 Fable 的项目被开发出来，将 reMarkable 设备变成哈利·波特系列中汤姆·里德尔的日记的数字版本。 这个项目之所以重要，是因为它创造性地应用技术复制了一个虚构的魔法物品，展示了 reMarkable 设备在传统笔记之外的互动和创意应用的潜力。 该项目利用 Anthropic 的 Fable 5 AI 模型将 E-Ink 设备变成一个交互式笔记本，其中手写笔记消失，由 AI 以优美的书法回应。

hackernews · modinfo · 7月6日 23:00 · [社区讨论](https://news.ycombinator.com/item?id=48811591)

**背景**: reMarkable 设备是一款数字纸平板电脑，使用基于 Linux 的操作系统 Codex，针对电子纸显示技术进行了优化。它已经获得了一群开发者和爱好者，他们为它创建第三方软件和项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ReMarkable">reMarkable - Wikipedia</a></li>
<li><a href="https://www.bhaskarenglish.in/tech-science/news/canada-developer-ai-notebook-remarkable-anthropic-fable-5-tom-riddle-diary-138373370.html">Harry Potter's Tom Riddle diary comes to life using AI?: Canadian developer turns reMarkable tablet into an AI notebook using Anthropic's Fable 5 model</a></li>

</ul>
</details>

**社区讨论**: 社区成员对这个项目的反应不一，一些人欣赏其创造力，而其他人则对将技术与哈利·波特中的恶意日记进行比较的伦理含义表示担忧。也有人提出制作视频演示和截图的建议，以便更好地理解这个项目。

**标签**: `#DIY`, `#Harry Potter`, `#reMarkable`, `#Fable`, `#Community Projects`

---