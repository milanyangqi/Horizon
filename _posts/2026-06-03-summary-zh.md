---
layout: default
title: "Horizon Summary: 2026-06-03 (ZH)"
date: 2026-06-03
lang: zh
---

> 从 14 条内容中筛选出 6 条重要资讯。

---

1. [通过 VSCode 漏洞实现一键 GitHub 令牌盗窃](#item-1) ⭐️ 8.0/10
2. [微软发布 137B 参数 AI 模型 MAI-Code-1-Flash](#item-2) ⭐️ 7.0/10
3. [斯坦福研究显示 AI 在特定任务中胜过法学教授](#item-3) ⭐️ 7.0/10
4. [micropython-wasm 0.1a1 发布](#item-4) ⭐️ 7.0/10
5. [Linux 上使用 Nvidia GPU 显存作为交换空间](#item-5) ⭐️ 6.0/10
6. [datasette-agent-micropython 0.1a0 版本发布](#item-6) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [通过 VSCode 漏洞实现一键 GitHub 令牌盗窃](https://blog.ammaraskar.com/github-token-stealing/) ⭐️ 8.0/10

Visual Studio Code（VSCode）中的一个漏洞允许攻击者通过一键点击盗窃 GitHub 令牌，利用这个漏洞可以恶意地未经授权访问用户的 GitHub 账户。 这次安全漏洞影响依赖 VSCode 进行日常工作的开发者，可能导致敏感仓库和个人数据被泄露。它强调了及时安全响应的重要性以及开发环境中需要强大的安全实践。 这个漏洞特别令人担忧，因为它可以通过打开恶意文件而无需用户交互即可触发。文章讨论了报告漏洞所采取的步骤以及微软安全响应中心（MSRC）缺乏紧迫性的回应，这引发了关于他们安全协议有效性的问题。

hackernews · ammar2 · 6月2日 15:29 · [社区讨论](https://news.ycombinator.com/item?id=48371562)

**背景**: VSCode 是由微软开发的流行的开源代码编辑器，拥有大量的扩展生态系统，可以增强其功能。GitHub 令牌用于 GitHub 服务和 API 的身份验证，授权访问仓库和其他资源。被泄露的令牌可能导致未经授权的代码更改、数据暴露或其他恶意活动。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jit.io/blog/vscode-extensions-for-2023">Top 20 Best VScode Extensions for 2026 | Jit</a></li>
<li><a href="https://blog.trailofbits.com/2023/02/21/vscode-extension-escape-vulnerability/">Escaping misconfigured VSCode extensions - The Trail of Bits Blog</a></li>
<li><a href="https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens">Managing your personal access tokens - GitHub Docs</a></li>

</ul>
</details>

**社区讨论**: 社区评论反映了对安全漏洞的担忧和个人经历。一些用户对 MSRC 处理漏洞报告的方式表示失望，而其他用户强调了积极对待安全和准备应对潜在令牌泄露的重要性。

**标签**: `#Security`, `#VSCode`, `#GitHub`, `#Bugs`, `#Token Theft`

---

<a id="item-2"></a>
## [微软发布 137B 参数 AI 模型 MAI-Code-1-Flash](https://microsoft.ai/news/introducingmai-code-1-flash/) ⭐️ 7.0/10

微软推出了新的 AI 模型 MAI-Code-1-Flash，该模型拥有 1370 亿参数，旨在提高编码效率和质量。 MAI-Code-1-Flash 的发布意义重大，因为它代表了 AI 领域模型规模和潜在能力的大幅增加，这可能导致更复杂的 AI 辅助编码解决方案。 MAI-Code-1-Flash 旨在提供更高效的高质量编码帮助。它已经与 Claude Haiku 4.5 和其他模型进行了基准测试，在编码任务中显示出竞争力。

hackernews · EvanZhouDev · 6月2日 18:47 · [社区讨论](https://news.ycombinator.com/item?id=48374466)

**背景**: 数十亿参数的 AI 模型是人工智能领域向更大更强模型发展的趋势的一部分。这些模型经过大量数据的训练，可以执行复杂的任务，如语言翻译、编码协助等。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2021/02/google-trillion-parameter-ai/">Google Open-Sources Trillion-Parameter AI Language Model Switch Transformer - InfoQ</a></li>
<li><a href="https://news.ycombinator.com/item?id=34684648">How many parameters? The LaMDA paper describes 2B, 8B, and 137B parameter variat... | Hacker News</a></li>
<li><a href="https://travis.media/blog/ai-model-parameters-explained/">AI Model Parameters Explained: 2B vs 7B vs 40B and Beyond</a></li>

</ul>
</details>

**社区讨论**: 社区对此次发布反应不一。一些用户比较 MAI-Code-1-Flash 的性能与其他模型，并讨论使用这些 AI 工具的成本影响，而其他用户对基准测试和小规模云模型在编码中的实用价值表示怀疑。

**标签**: `#AI`, `#Machine Learning`, `#Software Development`, `#Microsoft`, `#Model Launch`

---

<a id="item-3"></a>
## [斯坦福研究显示 AI 在特定任务中胜过法学教授](https://law.stanford.edu/press/ai-outperforms-law-professors-in-stanford-law-study/) ⭐️ 7.0/10

斯坦福法学院最近进行的一项研究发现，人工智能系统在特定任务中胜过了法学教授，特别是在提供一年级合同法问题的答案方面。 这项研究之所以重要，是因为它表明人工智能可能在法学教育和实践中扮演更重要的角色，有可能改变法律教学和法律服务的提供方式。 该研究涉及 16 位法学教授，并将他们的答案与一个名为 Gemini 的 AI 系统生成的答案进行了比较。结果表明教授们的表现差异很大，而 AI 提供了更一致的回应。

hackernews · berlianta · 6月2日 23:43 · [社区讨论](https://news.ycombinator.com/item?id=48377761)

**背景**: 法律技术，或称 LegalTech，涉及使用软件、AI 算法和数字平台来支持法律服务。它包括用于文件搜索、尽职调查和合同工作中用户体验设计的工具。AI 在法学教育中的角色是一个新兴领域，有潜力增强学习体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Legal_technology">Legal technology</a></li>
<li><a href="https://www.linkedin.com/pulse/understanding-legal-tech-high-directness-vs-deena-nawab-ttzcc">Understanding Legal Tech : High Directness vs. High Specificity</a></li>

</ul>
</details>

**社区讨论**: 社区对这项研究的反应褒贬不一。一些人对研究的方法论和统计能力表示怀疑，而另一些人则看到了 AI 降低法律培训成本和作为法学学生有效导师的潜力。

**标签**: `#AI`, `#Law`, `#Education`, `#Legal Technology`, `#Stanford`

---

<a id="item-4"></a>
## [micropython-wasm 0.1a1 发布](https://simonwillison.net/2026/Jun/2/micropython-wasm/#atom-everything) ⭐️ 7.0/10

发布了 micropython-wasm 0.1a1 版本，使得 Python 代码能够在 WebAssembly 环境中执行。 这一发布之所以重要，是因为它允许 Python 代码在 WebAssembly 上下文中运行，这可以导致更高效和安全的跨平台执行，特别是在沙箱环境中非常有用。 该版本修复了在构建 datasette-agent-micropython 时遇到的一些限制，表明了其实际应用和持续发展。

rss · Simon Willison · 6月2日 19:20

**背景**: MicroPython 是为微控制器和其他资源受限环境设计的轻量级 Python 3 实现，而 WebAssembly 是一种基于栈的虚拟机的二进制指令格式，使得在网络和其他地方的高性能应用成为可能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MicroPython">MicroPython</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>

</ul>
</details>

**标签**: `#Python`, `#WebAssembly`, `#Sandboxing`, `#Cross-Platform`, `#Release`

---

<a id="item-5"></a>
## [Linux 上使用 Nvidia GPU 显存作为交换空间](https://github.com/c0dejedi/nbd-vram) ⭐️ 6.0/10

名为'nbd-vram'的新项目允许 Linux 用户将 Nvidia GPU 的显存用作交换空间，可能提供了一种传统基于 RAM 交换的替代方案。 这个项目之所以重要，是因为它提供了一种利用 Nvidia GPU 上通常未充分利用的显存的方法，尤其对于内存有限的系统有益，例如没有升级路径的焊接内存笔记本电脑。 该项目通过使用网络块设备(NBD)协议将 GPU 显存暴露为一个块设备来实现这一点，该块设备可以被用作交换空间。然而，用户指出，顺序吞吐量大约为 1.3 GB/s，远低于 RTX 3070 显存的理论极限。

hackernews · tanelpoder · 6月2日 22:55 · [社区讨论](https://news.ycombinator.com/item?id=48377404)

**背景**: 显存，或称视频随机存取存储器，是一种用于存储像素数据以在计算机显示器上渲染的存储器。它的设计是为了快速读取，并且物理上更接近 GPU 核心以实现更低的延迟。交换空间是硬盘驱动器的一部分，被用作虚拟内存，允许计算机使用磁盘空间就好像它是 RAM 一样。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/VRAM">VRAM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Swap_space">Swap space</a></li>

</ul>
</details>

**社区讨论**: 社区对这个项目的看法不一。一些人认为它是特定用例的小众解决方案，比如升级性有限的笔记本电脑，而其他人则质疑其实用性，考虑到与 RAM 相比的较低吞吐量以及对图形处理显存分配的潜在影响。

**标签**: `#Linux`, `#Nvidia`, `#GPU`, `#VRAM`, `#Swap Space`

---

<a id="item-6"></a>
## [datasette-agent-micropython 0.1a0 版本发布](https://simonwillison.net/2026/Jun/2/datasette-agent-micropython/#atom-everything) ⭐️ 6.0/10

datasette-agent-micropython 的 0.1a0 alpha 版本已发布，旨在使用 Datasette Agent 和 GPT-5.5 安全地生成和执行 Python 代码。 此次发布之所以重要，是因为它代表了朝着更安全的代码执行和沙箱技术迈出的早期步骤，利用了人工智能和 WebAssembly 的能力。 alpha 版本显示出了希望，GPT-5.5 未能突破沙箱，表明有潜力进行安全的代码生成和执行。

rss · Simon Willison · 6月2日 19:28

**背景**: MicroPython 是为微控制器和其他受限环境设计的 Python 3 的精简实现。Datasette Agent 是用于探索和查询 SQLite 数据库中数据的 AI 助手。WebAssembly 是一种用于虚拟机的二进制指令格式，它使得在网络和其他地方的高性能应用成为可能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MicroPython">MicroPython - Wikipedia</a></li>
<li><a href="https://agent.datasette.io/">Datasette Agent: an AI assistant for Datasette to help explore and analyze data in SQLite</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>

</ul>
</details>

**标签**: `#datasette`, `#micropython`, `#sandboxing`, `#python`, `#webassembly`

---