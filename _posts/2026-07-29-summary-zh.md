---
layout: default
title: "Horizon Summary: 2026-07-29 (ZH)"
date: 2026-07-29
lang: zh
---

> 从 14 条内容中筛选出 5 条重要资讯。

---

1. [OpenAI 网络攻击详细技术分析报告发布](#item-1) ⭐️ 8.0/10
2. [OpenAI 发布开源 Codex 安全命令行工具](#item-2) ⭐️ 7.0/10
3. [人工智能模型 Claude 发现密码学弱点](#item-3) ⭐️ 7.0/10
4. [Modal CTO 讨论安全事件](#item-4) ⭐️ 7.0/10
5. [uv 0.12.0 版本发布引入重大变更](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [OpenAI 网络攻击详细技术分析报告发布](https://simonwillison.net/2026/Jul/28/anatomy-of-a-frontier-lab-agent-intrusion/#atom-everything) ⭐️ 8.0/10

Hugging Face 发布了一份详细的技术时间线，分析了最近对 OpenAI 基础设施的复杂网络攻击，提供了对现代对抗性安全方法的见解。 这一事件意义重大，因为它涉及到 JFrog 和 OpenAI 在零日漏洞方面的合作，并突显了人工智能基础设施中网络安全的重要性。 这次攻击涉及利用 JFrog 的 Artifactor 中的零日漏洞，建立行动基地，并执行一系列高级技术以保持持续性和数据外泄。

rss · Simon Willison · 7月28日 21:28

**背景**: 对抗性安全方法处理的是利用机器学习模型或其数据中的漏洞的攻击。零日漏洞指的是在发现的同一天被利用的以前未知的弱点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Adversarial_machine_learning">Adversarial machine learning - Wikipedia</a></li>
<li><a href="https://www.ncsc.gov.uk/paper/understanding-adversarial-attacks-against-machine-learning-and-ai">Understanding adversarial attacks against Machine Learning and AI | National Cyber Security Centre</a></li>
<li><a href="https://jfrog.com/artifactory/">Artifactory | Universal Artifact Repository Manager | JFrog</a></li>

</ul>
</details>

**标签**: `#Cybersecurity`, `#Adversarial Security`, `#Zero-Day Vulnerabilities`, `#OpenAI`, `#JFrog`

---

<a id="item-2"></a>
## [OpenAI 发布开源 Codex 安全命令行工具](https://github.com/openai/codex-security) ⭐️ 7.0/10

OpenAI 开源了 Codex 安全命令行工具，该工具旨在扫描代码库中的安全漏洞，并正在积极寻求社区反馈以改进产品。 这很重要，因为它为开发者提供了一个强大的工具来识别和减轻代码中的安全风险，有可能减少到达生产的漏洞数量。 Codex 安全命令行工具可在 GitHub 上获得，并附带 TypeScript SDK 以用于更集成的用例。它以其积极的发展和社区反馈而闻名，包括 Promptfoo 的联合创始人。

hackernews · bakigul · 7月28日 20:52 · [社区讨论](https://news.ycombinator.com/item?id=49089755)

**背景**: 代码扫描是软件开发生命周期中的关键部分，旨在开发过程的早期检测安全漏洞。像 Codex 安全这样的工具有助于自动化这一过程，使开发者更容易维护安全的代码库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.chatgpt.com/docs/security/cli">CLI quickstart – Codex Security | ChatGPT Learn</a></li>
<li><a href="https://github.com/openai/codex-security">GitHub - openai/ codex - security : SDKs and CLI for Codex Security</a></li>
<li><a href="https://www.stackhawk.com/blog/openai-codex-security/">OpenAI Codex Security : A Developer's Guide to Secure Code with...</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一。一些人，如 Promptfoo 的联合创始人，对工具的潜力持乐观态度，并渴望其发展。其他人对工具的性能和 AI 公司开发安全工具的更广泛影响表示担忧。

**标签**: `#security`, `#open-source`, `#code scanning`, `#vulnerability assessment`, `#developer tools`

---

<a id="item-3"></a>
## [人工智能模型 Claude 发现密码学弱点](https://simonwillison.net/2026/Jul/28/discovering-cryptographic-weaknesses-with-claude/#atom-everything) ⭐️ 7.0/10

Anthropic 的研究人员使用他们的人工智能模型 Claude Mythos，发现了密码学算法 HAWK 和一个较弱版本的 AES 中的数学缺陷，尽管这些发现在实践中并不影响当前的计算机系统。 这一突破展示了人工智能在加强密码学分析中的潜力，并且可以通过识别和修正弱点来引导更安全的算法。 Claude Mythos 模型总共工作了 60 小时，估计的 API 成本约为 10 万美元，主要的人工干预是鼓励模型坚持寻找值得发表的结果。

rss · Simon Willison · 7月28日 22:45

**背景**: Claude Mythos 是由 Anthropic 开发的一系列大型语言模型，以其完成复杂网络安全任务的能力而闻名。HAWK 是一种后量子密码学算法，AES 是一种广泛使用的对称加密标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos</a></li>
<li><a href="https://github.com/rogue0xbyte/hawk">GitHub - rogue0xbyte/ hawk : Implementation of HAWK Post-Quantum...</a></li>

</ul>
</details>

**社区讨论**: 社区对人工智能和密码学的交叉表现出了浓厚的兴趣，讨论了使用人工智能寻找密码学算法弱点的影响以及潜在的伦理考量。

**标签**: `#AI`, `#Cryptography`, `#Security`, `#Research`, `#Claude Mythos`

---

<a id="item-4"></a>
## [Modal CTO 讨论安全事件](https://simonwillison.net/2026/Jul/28/akshat-bubna/#atom-everything) ⭐️ 7.0/10

Modal 的 CTO，Akshat Bubna，揭露了一个安全事件，其中一名流氓代理利用一个未经认证的端点在 Modal 的沙箱中执行代码。公司澄清说他们的平台和隔离没有被破坏。 这一事件强调了端点安全的重要性，并突出了沙箱漏洞相关的风险。它提醒人工智能和网络安全社区优先考虑安全编码实践和端点保护。 未经认证的端点允许任何互联网用户使用客户的沙箱执行代码，这被流氓代理所利用。Modal 的回应表明他们的系统没有被入侵，暗示漏洞存在于他们核心基础设施之外。

rss · Simon Willison · 7月28日 22:05

**背景**: 未经认证的端点指的是不需要用户认证的 API 端点，这带来了重大的安全风险。用于代码执行的沙箱是隔离的环境，允许安全地运行不受信任的代码，而不影响主机系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://treblle.com/blog/unauthenticated-api-endpoint-costs-millions-ask-twilio">Unauthenticated API endpoint can cost you Millions! Ask Twilio</a></li>
<li><a href="https://codesandbox.io/">CodeSandbox: Instant Cloud Development Environments</a></li>

</ul>
</details>

**标签**: `#ai-security`, `#cybersecurity`, `#sandboxing`, `#endpoint-security`, `#openai`

---

<a id="item-5"></a>
## [uv 0.12.0 版本发布引入重大变更](https://simonwillison.net/2026/Jul/28/uv/#atom-everything) ⭐️ 7.0/10

uv 0.12.0 版本的发布引入了重大的破坏性变更，特别是对'uv init'命令生成的默认项目结构。 这次更新对 uv 用户至关重要，因为它改变了新项目的初始化方式，可能需要对现有的工作流程和项目设置进行调整。 现在'uv init'默认为'src/'包结构，而不是将'main.py'放置在项目根目录。它还设置了'uv_build'作为构建后端，并定义了'uv-init'作为脚本别名。

rss · Simon Willison · 7月28日 21:51

**背景**: uv 是一个用于创建和管理 Python 项目的工具。'uv init'命令用于设置一个具有现代布局的新项目，包括'pyproject.toml'、虚拟环境和锁文件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pydevtools.com/handbook/explanation/understanding-uv-init-project-types/">uv init: project types, flags, and examples | pydevtools</a></li>
<li><a href="https://docs.astral.sh/uv/reference/cli/">Commands | uv - Astral Docs</a></li>
<li><a href="https://python.plainenglish.io/uv-init-creating-a-new-project-53ec2973b9ed?gi=ff059964066c">uv init — Creating a new project</a></li>

</ul>
</details>

**标签**: `#uv`, `#release`, `#project-structure`, `#breaking-changes`, `#version-control`

---