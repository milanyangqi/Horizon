---
layout: default
title: "Horizon Summary: 2026-06-24 (ZH)"
date: 2026-06-24
lang: zh
---

> 从 12 条内容中筛选出 4 条重要资讯。

---

1. [FUTO Swipe – 一种新的滑动输入模型](#item-1) ⭐️ 7.0/10
2. [Swift Package Index 被苹果收购](#item-2) ⭐️ 7.0/10
3. [Datasette 1.0a35 版本发布，引入新的数据库管理功能](#item-3) ⭐️ 7.0/10
4. [OPFS + Pyodide 测试框架发布](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [FUTO Swipe – 一种新的滑动输入模型](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO Swipe 推出了一种新的键盘布局，旨在最小化单词重叠，优化滑动输入，实现更快的单手打字。 引入旨在优化速度和减少单词重叠的新滑动输入模型是输入方法中的一个重要发展，可能会改善用户的打字体验。 FUTO Swipe 的新模型与 FUTO Keyboard 集成，这是一个注重隐私、离线的 Android 键盘应用。该模型解决了滑动输入的常见问题，如难以区分单个和双个字母以及最小化单词重叠。

hackernews · futohq · 6月23日 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48648619)

**背景**: 滑动输入是在智能手机上输入文本的一种方式，通过在键盘上滑动手指而不是敲击每个字母。它旨在提高打字速度和效率。FUTO Keyboard 以其对隐私的关注而闻名，提供如不需要互联网连接的滑动输入等功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://keyboard.futo.org/">FUTO Keyboard</a></li>

</ul>
</details>

**社区讨论**: 社区对 FUTO Swipe 的反馈褒贬不一，但总体上是积极的。用户对滑动优化和单手打字更快的潜力表示赞赏，同时也指出了需要改进的领域，如上下文感知的单词建议和同音异义词的处理。

**标签**: `#input methods`, `#keyboard layout`, `#swipe typing`, `#ergonomics`, `#text input`

---

<a id="item-2"></a>
## [Swift Package Index 被苹果收购](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 7.0/10

Swift 编程语言广泛使用的包索引 Swift Package Index 已正式成为苹果的一部分。 此次收购意义重大，因为它可能会导致 Swift Package Manager 的改进，并可能影响 Swift 生态系统中包管理的未来方向。 尽管被收购，Swift Package Index 承诺继续保持开源，这对于维护社区信任和参与至关重要。

hackernews · JDevlieghere · 6月23日 18:00 · [社区讨论](https://news.ycombinator.com/item?id=48648779)

**背景**: Swift Package Index 是一个社区运行的 Swift 包搜索引擎和元数据索引，为开发者提供了一个全面的目录来发现和管理依赖项。由苹果开发的 Swift 是一种强大直观的编程语言，用于开发苹果平台的应用程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://swiftpackageindex.com/">Swift Package Index</a></li>
<li><a href="https://www.swift.org/packages/">Packages | Swift.org</a></li>
<li><a href="https://9to5mac.com/2026/06/23/swift-package-index-joins-apple-pledges-to-remain-open-source/">Swift Package Index joins Apple, pledges to remain open source</a></li>

</ul>
</details>

**社区讨论**: 社区对此次收购反应不一。一些人对 Swift Package Manager 可能的改进持乐观态度，而其他人则对苹果在开源和开发者服务方面的记录表示担忧。

**标签**: `#Swift`, `#Apple`, `#Open Source`, `#Package Management`, `#Developer Services`

---

<a id="item-3"></a>
## [Datasette 1.0a35 版本发布，引入新的数据库管理功能](https://simonwillison.net/2026/Jun/23/datasette/#atom-everything) ⭐️ 7.0/10

Datasette 1.0a35 版本引入了新的“创建表”界面和“修改表”操作，增强了该工具的数据库管理能力。 这些更新通过提供用户友好的界面和 API 来创建和修改表，可以显著提高使用 datasette 的开发者的工作效率。 “创建表”界面允许定义列、主键、自定义列类型和约束。“修改表”功能可以添加、重命名、重新排序和删除列，以及更改列类型和约束，从而修改现有表。

rss · Simon Willison · 6月23日 21:34

**背景**: Datasette 是一个为探索和发布数据而设计的开源多工具。它允许用户将数据转换为交互式网站和 API。该工具对于需要为各种应用程序管理和操作数据库的开发者特别有用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and publishing data</a></li>

</ul>
</details>

**标签**: `#datasette`, `#database`, `#API`, `#data management`, `#software release`

---

<a id="item-4"></a>
## [OPFS + Pyodide 测试框架发布](https://simonwillison.net/2026/Jun/23/opfs-pyodide/#atom-everything) ⭐️ 7.0/10

推出了一个新的测试框架，它允许使用 OPFS（Origin Private File System）和 Pyodide 在浏览器中编辑持久的 SQLite 文件。 这一发展意义重大，因为它使得基于浏览器的应用程序能够执行更复杂的数据操作任务，可能会导致更强大和多功能的网络应用程序。 该测试框架是为了探索 Datasette Lite（一个 Python 应用程序）编辑存储在用户计算机上的 SQLite 文件的可能性，利用 OPFS 和 Pyodide 的功能。

rss · Simon Willison · 6月23日 18:58

**背景**: Datasette Lite 是 Datasette 的一个版本，Datasette 是一个可以从 SQLite 数据库即时提供 JSON API 的工具。Pyodide 是一个将 Python 运行时环境通过 WebAssembly 带到浏览器中的项目。OPFS 允许网络应用程序访问用户设备的文件系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pyodide.org/en/stable/console.html">pyodide .org/en/stable/console.html</a></li>
<li><a href="https://puter.com/app/pyodide">Pyodide</a></li>

</ul>
</details>

**标签**: `#browsers`, `#pyodide`, `#datasette-lite`, `#web-development`, `#sqlite`

---