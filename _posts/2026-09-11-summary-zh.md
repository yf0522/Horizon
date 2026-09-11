---
layout: default
title: "Horizon Summary: 2026-09-11 (ZH)"
date: 2026-09-11
lang: zh
---

> 从 41 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [Calif Research 展示 WeWorm：首个零点击微信蠕虫，AI 加速开发](#item-tech-news-1) ⭐️ 10.0/10
2. [Rust 成为微软一级语言](#item-tech-news-2) ⭐️ 9.0/10
3. [蚂蚁国际、Visa 和 Mastercard 合作制定 AI 代理支付标准](#item-tech-news-3) ⭐️ 9.0/10
4. [Shopify 从 React Native 转向 Swift 和 Kotlin](#item-tech-news-4) ⭐️ 8.0/10
5. [研究人员质疑 OpenAI 处理未发表数学研究的信任问题](#item-tech-news-5) ⭐️ 8.0/10
6. [卫星图像处理技术揭示古代遗迹](#item-tech-news-6) ⭐️ 8.0/10
7. [索尼 PlayStation 数字游戏所有权诉讼引发消费者权利和许可模式争议](#item-tech-news-7) ⭐️ 8.0/10
8. [trynix.dev 允许在浏览器中运行过去 13 年的任何 Nix 软件包](#item-tech-news-8) ⭐️ 8.0/10
9. [数据中心表后供电的挑战：第一部分](#item-tech-news-9) ⭐️ 8.0/10
10. [348M 参数模型通过展示计算步骤在多位数算术上超越 GPT-3 175B](#item-tech-news-10) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Calif Research 展示 WeWorm：首个零点击微信蠕虫，AI 加速开发](https://simonwillison.net/2026/Sep/10/calif-research/) ⭐️ 10.0/10

Calif Research 近日展示了 WeWorm，这是首个能够通过微信通话在 iOS 和 Android 设备间传播的零点击蠕虫。受害者无需接听电话或与手机互动，漏洞即可成功利用。该团队利用人工智能在约两天内发现了漏洞并编写了远程代码执行 \(RCE\) 漏洞利用程序，随后在一周内构建了蠕虫，显著缩短了通常需要数月才能完成的开发时间。

rss · Simon Willison · 9月10日 00:56

**「背景信息」** 零点击蠕虫是一种恶意软件，无需用户任何交互即可传播，例如受害者无需点击链接或接听电话。远程代码执行（RCE）漏洞允许攻击者在远程设备上执行任意代码，从而可能完全控制该系统。

**「影响」** 这一突破性进展表明，微信的 iOS 和 Android 用户面临无需任何交互即可被零点击攻击的风险，同时凸显了人工智能在加速漏洞利用开发方面的强大能力，预示着网络安全领域可能出现新的威胁范式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.calif.io/p/weworm">WeWorm - Calif Newsletter</a></li>
<li><a href="https://cybersecuritynews.com/weworm-first-0-click-worm/">WeWorm – First 0-Click Worm Spreading Through WeChat Calls ...</a></li>
<li><a href="https://letsdatascience.com/news/calif-demonstrates-ai-assisted-wechat-zero-click-worm-a2453cdd">Calif Demonstrates AI-Assisted WeChat Zero-Click Worm</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#artificial intelligence`, `#exploit development`, `#mobile security`, `#zero-click exploit`

---

<a id="item-tech-news-2"></a>
### [Rust 成为微软一级语言](https://rustfoundation.org/media/guest-post-rust-is-tier-1-language-at-microsoft/) ⭐️ 9.0/10

微软已将 Rust 宣布为一级（Tier-1）语言，这标志着其在公司内部的战略重要性和广泛采用。此举预示着系统编程领域将向内存安全语言进行重大转变，并可能推动大规模代码迁移。微软设定了到 2030 年将十亿行代码转换为 Rust 的宏伟目标，并有 DARPA 参与自动化 C 到 Rust 迁移项目，这进一步巩固了 Rust 作为未来软件开发中成熟且关键语言的地位。

hackernews · mmastrac · 9月10日 13:39 · [社区讨论](https://news.ycombinator.com/item?id=49643546)

**「背景」** Rust 是一种以内存安全和并发性著称的系统编程语言，常被视为 C 和 C++的现代替代品。微软已公开表示其长期目标是到 2030 年将 C 和 C++代码库迁移到 Rust，并计划利用 AI 和算法实现大规模自动化代码转换，例如“一名工程师、一个月、一百万行代码”的愿景。

**「影响」** 这一决策对微软而言，意味着其庞大的产品组合将通过采用 Rust 的内存安全设计来减少大量的 CVE（常见漏洞和暴露），其中约 70% 的漏洞与内存安全问题相关。

**「社区讨论」** 社区普遍认为这是“非常重大的新闻”，表明 Rust 已成为 C++ 和 C\# 等成熟语言的“严肃竞争者”，且比 Zig 和 Odin 等新语言更成熟。评论指出，微软此举具有战略意义，有助于通过 Rust 的内存安全设计改善其产品组合中大量与内存安全相关的 CVE 问题，并提及微软计划到 2030 年将十亿行代码转换为 Rust 的目标，以及 DARPA 在自动化 C 代码到 Rust 转换方面的工作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thenewstack.io/microsofts-bold-goal-replace-1b-lines-of-c-c-with-rust/">Microsoft&#x27;s Bold Goal: Replace 1B Lines of C/C++ With Rust - The New Stack</a></li>
<li><a href="https://www.itpro.com/software/development/microsoft-rust-programming-language-modernization-ai">‘1 engineer, 1 month, 1 million lines of code’: Microsoft wants to replace C and C++ code with Rust by 2030 – but a senior engineer insists the company has no plans on using AI to rewrite Windows source code | IT Pro</a></li>
<li><a href="https://www.thurrott.com/dev/330980/microsoft-to-replace-all-c-c-code-with-rust-by-2030">Microsoft to Replace All C/C++ Code With Rust by 2030 - Thurrott.com</a></li>
<li><a href="https://markaicode.com/legacy-code-migration-c-to-rust-tools-2025/">C to Rust Migration in 2025: Tools, Strategies, and What... | Markaicode</a></li>
<li><a href="https://byteiota.com/microsoft-ai-rust-migration-research-vs-1m-lines-month-hype/">Microsoft AI Rust Migration : Research vs 1M Lines/Month... | byteiota</a></li>

</ul>
</details>

**标签**: `#Rust`, `#Microsoft`, `#Programming Languages`, `#Systems Programming`, `#Software Engineering`

---

<a id="item-tech-news-3"></a>
### [蚂蚁国际、Visa 和 Mastercard 合作制定 AI 代理支付标准](https://www.cnbc.com/2026/09/10/ant-international-visa-mastercard-ai-agent-payment-standard.html) ⭐️ 9.0/10

蚂蚁国际、Visa 和 Mastercard 宣布合作，共同为 AI 代理支付制定通用标准，旨在提升不同支付系统间的互操作性和安全性。此次合作将建立“了解你的代理”（Know Your Agent）机制，以关联 AI 代理与有效实体、评估其行为并监测风险。三方援引麦肯锡预测，到 2030 年，AI 代理有望处理全球 3 万亿至 5 万亿美元的消费者商业交易。

telegram · zaihuapd · 9月10日 03:00

**「背景」** 支付行业长期以来依赖标准化来确保不同金融机构和技术平台之间的顺畅交易与信任。随着人工智能技术的发展，AI 代理开始在商业交易中扮演角色，因此，为这些新兴的 AI 驱动支付模式建立统一标准，对于保障其在全球范围内的安全与高效运行至关重要。

**「影响」** 这项合作将为未来数万亿美元规模的 AI 代理支付市场奠定基础，显著提升 AI 驱动金融交易的互操作性和安全性，从而直接影响全球消费者和商业实体。

**标签**: `#Artificial Intelligence`, `#Payment Systems`, `#Industry Standards`, `#Financial Technology`, `#Security`

---

<a id="item-tech-news-4"></a>
### [Shopify 从 React Native 转向 Swift 和 Kotlin](https://shopify.engineering/back-to-native) ⭐️ 8.0/10

Shopify 正在将其移动开发从 React Native 转向原生的 Swift 和 Kotlin，这一重大的架构决策引发了业界对跨平台与原生方法权衡的讨论。此举也凸显了人工智能在促进大规模迁移中日益增长的作用。Shopify 重新评估了其 2020 年的决策，指出大型语言模型（LLMs）改变了其核心假设之一。

hackernews · fnthawar2 · 9月10日 14:09 · [社区讨论](https://news.ycombinator.com/item?id=49643982)

**「背景」** React Native 是一个允许开发者使用 JavaScript 编写跨平台移动应用的框架，而 Swift 和 Kotlin 分别是苹果 iOS 和谷歌 Android 平台的原生开发语言。Shopify 曾积极采用 React Native 进行移动应用开发，甚至为其开源库做出了贡献，但现在正将其移动开发策略转向使用 Swift 和 Kotlin 进行原生开发。

**「影响」** Shopify 正在将其移动应用从 React Native 迁移回原生 Swift 和 Kotlin，这一由 AI 辅助的重大战略转变，直接影响了其产品技术栈和开发流程，并可能重塑行业对跨平台与原生开发成本效益的看法。

**「社区讨论」** 社区讨论普遍支持 Shopify 的决定，有 iOS 工程师表示其反对共享代码库的立场得到验证。一些评论者分享了利用 AI 工具（如 Codex 和 Maestro）成功将小型应用从 React Native 迁移到原生平台的经验，甚至在短时间内完成。然而，也有人指出，并非所有原生迁移都依赖于 LLMs，一些大型项目在 LLM 普及前已完成，尽管后期功能可能使用了 AI 辅助。普遍观点认为，随着模型在生成原生 iOS 应用方面日益成熟，React Native 曾有的吸引力（利用 Web 开发人员进行移动开发）正在减弱，建议直接开始原生开发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://shopify.engineering/back-to-native">Native is now the future of mobile at Shopify (2026) - Shopify</a></li>
<li><a href="https://shopify.engineering/migrating-our-largest-mobile-app-to-react-native">Migrating our Largest Mobile App to React Native - Shopify</a></li>
<li><a href="https://shopify.engineering/back-to-native">Native is now the future of mobile at Shopify (2026) - Shopify</a></li>
<li><a href="https://genztech.blog/p/shopify-react-native-back-to-native/">Shopify Ditches React Native , Rebuilds Apps in Swift and Kotlin</a></li>
<li><a href="https://news.ycombinator.com/item?id=49643982">Shopify moves back to Native from React Native | Hacker News</a></li>

</ul>
</details>

**标签**: `#Mobile Development`, `#Software Architecture`, `#Cross-platform Development`, `#AI in Software Engineering`

---

<a id="item-tech-news-5"></a>
### [研究人员质疑 OpenAI 处理未发表数学研究的信任问题](https://mathstodon.xyz/@andreasthom/117240535270608201) ⭐️ 8.0/10

研究人员正在质疑他们是否能信任 OpenAI 处理未发表的数学研究工作，这引发了一场关于数据归属、知识产权以及 AI 在科学研究中伦理合作界限的重要辩论。这一讨论对 AI 工具如何融入科学发现以及管理数据使用和归属的政策具有深远影响。核心问题在于，当研究人员与 AI 模型分享未公开的想法时，AI 公司是否会以不归属的方式利用这些信息，从而引发了对学术诚信和数据保护的担忧。

hackernews · pred\_ · 9月10日 06:49 · [社区讨论](https://news.ycombinator.com/item?id=49639408)

**「背景」** OpenAI 近期宣布其人工智能模型在数学领域取得了重大突破，甚至有报道称其解决了千禧年大奖难题之一。然而，这一消息很快引发了争议，多位数学家公开指责 OpenAI 在其模型训练中使用了他们未发表的研究成果，从而引发了关于数据归属和知识产权的激烈讨论。

**「影响」** 关于 OpenAI 处理未发表数学作品的持续争议直接影响了学术研究人员与 AI 开发者之间的信任，凸显了在科学研究中制定更清晰的知识产权归属和伦理 AI 合作指南的紧迫性。

**「社区讨论」** 社区成员将 OpenAI 比作不道德的人类合作者，质疑其在利用研究人员共享的想法后却不进行归属的行为，即使 OpenAI 声称模型未在特定聊天记录上进行训练。讨论还指出，OpenAI 模型可能通过聊天记录隐式提升其直觉，同时也能通过大规模计算和强化学习独立发现新方法，并对公司保护用户数据以谋取自身利益的能力表示普遍不信任。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_priority_controversy">Navier–Stokes priority controversy - Wikipedia</a></li>
<li><a href="https://www.aichatdaily.com/ai-security/mathematicians-accuse-openai-using-unpublished-work-math-breakthroughs">Mathematicians accuse OpenAI of using unpublished work in ...</a></li>
<li><a href="https://www.technologyreview.com/2026/09/08/1143747/what-openais-latest-controversy-tells-us-about-the-future-of-math/">What OpenAI’s latest controversy tells us about the future of ...</a></li>
<li><a href="https://unesdoc.unesco.org/in/rest/annotationSVC/DownloadWatermarkedAttachment/attach_import_fa6f4b4a-9298-4a92-ba07-8108ac513153?_=380455eng.pdf&amp;from=1&amp;to=21">Recommendation on the ethics of artificial intelligence</a></li>
<li><a href="https://gipresearch.com/patent-attorney/ai-intellectual-property-protection-india/">AI Intellectual Property Protection in India: The Comprehensive Guide...</a></li>
<li><a href="https://www.leenlee.com.sg/news-publications/9th-tiip-international-forum-global-ai-intellectual-property-summit">9th TIIP International Forum - Global AI Intellectual Property Summit...</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Research Ethics`, `#Intellectual Property`, `#Machine Learning`, `#AI Governance`

---

<a id="item-tech-news-6"></a>
### [卫星图像处理技术揭示古代遗迹](https://spinoff.nasa.gov/Manipulating_Satellite_Photos_Now_Reveals_Ancient_Images) ⭐️ 8.0/10

NASA 开发的一种名为“去相关拉伸”（Decorrelation Stretch）的图像处理技术，现正应用于卫星照片，以揭示此前未被发现的古代考古遗址。这项技术通过增强图像中不同光谱带之间的微小颜色差异，使得肉眼难以察觉的地面特征变得清晰可见。它展示了遥感和信号处理在考古学领域的重要实际应用，为研究人员提供了识别和分析历史地貌的新工具。

hackernews · gumby · 9月10日 15:29 · [社区讨论](https://news.ycombinator.com/item?id=49645437)

**「背景」** 去相关拉伸（Decorrelation Stretch）是一种由美国国家航空航天局（NASA）开发并应用于数字图像的技术。该技术通过增强图像中的对比度，使细微的差异更加清晰，从而更容易识别图像中的特征。它最初可能用于其他目的，但现在被应用于卫星照片以揭示古代考古遗址。

**「影响」** 这项技术直接赋能考古学家和研究人员从卫星图像中识别并研究新的古代遗址，从而扩展了对人类历史和文化遗产的理解。

**「社区讨论」** 社区讨论显示，许多用户对假彩色合成和信号处理的概念很熟悉，并分享了在 GIMP 中实现类似效果的具体步骤。有用户曾尝试使用多波段滤镜寻找隐藏的岩画但未成功，并对该技术在 ImageMagick 中的实现表示兴趣。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spinoff.nasa.gov/Manipulating_Satellite_Photos_Now_Reveals_Ancient_Images">Technique for Manipulating Satellite Photos Now Reveals Ancient Images | NASA Spinoff</a></li>
<li><a href="https://phys.org/news/2026-09-nasa-technique-satellite-photos-reveals.html">NASA technique for manipulating satellite photos now reveals ancient images</a></li>
<li><a href="https://www.nasa.gov/technology/tech-transfer-spinoffs/nasa-technique-for-manipulating-satellite-photos-now-reveals-ancient-images/">NASA Technique for Manipulating Satellite Photos Now Reveals Ancient Images - NASA</a></li>

</ul>
</details>

**标签**: `#Image Processing`, `#Remote Sensing`, `#Signal Processing`, `#Computer Vision`, `#Geospatial Data`

---

<a id="item-tech-news-7"></a>
### [索尼 PlayStation 数字游戏所有权诉讼引发消费者权利和许可模式争议](https://consumerrights.wiki/w/Sony_PlayStation_digital_game_ownership_lawsuit) ⭐️ 8.0/10

针对索尼 PlayStation 的诉讼挑战了数字游戏所有权的定义，引发了关于消费者权利、许可模式以及整个科技行业平台服务条款可执行性的关键问题。诉讼引用了 PlayStation 服务条款第 14 节中的约束性仲裁协议和集体诉讼豁免条款，并提及了用户在接受协议后 30 天内书面通知索尼即可选择退出的条款。索尼辩称，如果玩家拥有数字游戏，那么不同玩家将无法在不同日期购买同一款游戏，例如原告 Edward Heycock 和 Jason Mendoza 分别于 2026 年 2 月 25 日和 2026 年 2 月 14 日以 69.99 美元购买《生化危机：安魂曲》的情况。此案对数字内容所有权的法律和商业格局具有广泛影响。

hackernews · haunter · 9月10日 12:18 · [社区讨论](https://news.ycombinator.com/item?id=49642531)

**「背景」** 一项针对索尼 PlayStation 的集体诉讼指控其在数字游戏销售中使用“购买”等所有权语言，但实际上只提供了可撤销的许可。索尼对此回应称，数字游戏无法真正“拥有”，并且其结账流程已明确告知消费者他们购买的是许可而非所有权，因此驳回了这些指控。此案引发了关于数字内容所有权、许可模式以及平台服务条款可执行性的广泛讨论。

**「影响」** 此诉讼直接影响加州的 PlayStation 购买者，他们声称因误以为自己拥有数字游戏而支付了过高的费用，而实际上他们只获得了有限的、可撤销的许可，这可能违反了加州要求明确披露的消费者保护法。

**「社区讨论」** 社区讨论主要围绕 PlayStation 服务条款中的约束性仲裁协议和集体诉讼豁免条款展开，有评论认为此类协议剥夺了消费者的权利。针对索尼关于“如果玩家拥有游戏，则无法重复购买”的辩护，有用户通过类比实体书的购买，指出拥有的是内容的“副本”而非内容本身，质疑索尼的论点可能适得其反。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybernews.com/tech/sony-digital-game-ownership-lawsuit/">Sony Digital Game Ownership Fight: You Can’t Own Games, It ...</a></li>
<li><a href="https://openclassactions.com/lawsuits/consumer-protection/sony-playstation-digital-game-license-class-action-lawsuit.php">Do You Own Digital Games You Buy? Sony Lawsuit Explained</a></li>
<li><a href="https://www.digitaltrends.com/gaming/sonys-defense-against-a-digital-ownership-lawsuit-is-that-you-know-you-dont-own-your-games/">Sony&#x27;s defense against a digital ownership lawsuit is that ...</a></li>
<li><a href="https://consumerrights.wiki/w/Sony_PlayStation_digital_game_ownership_lawsuit">Sony PlayStation digital game ownership lawsuit - Consumer Rights Wiki</a></li>
<li><a href="https://fortune.com/2026/09/01/sony-playstation-dont-actually-own-digital-games-grand-theft-auto-analog-media-gen-z/">Once a champion for physical media, Sony is now telling PlayStation customers they don’t actually own the digital video games they paid $70 for | Fortune</a></li>
<li><a href="https://www.findlaw.com/legalblogs/consumer-protection/do-you-really-own-your-digital-games-sony-lawsuit-highlights-the-fine-print-of-licensing/">Do You Really ‘Own’ Your Digital Games? Sony Lawsuit Highlights the Fine Print of Licensing - FindLaw</a></li>

</ul>
</details>

**标签**: `#Digital Rights`, `#Consumer Rights`, `#Platform Policy`, `#Legal Tech`, `#Software Licensing`

---

<a id="item-tech-news-8"></a>
### [trynix.dev 允许在浏览器中运行过去 13 年的任何 Nix 软件包](https://simonwillison.net/2026/Sep/10/trynix/) ⭐️ 8.0/10

一个名为 trynix.dev 的新平台现已推出，它利用 qemu-wasm 技术，通过 WebAssembly 在浏览器中直接运行一个 x86\_64 Linux 虚拟机。该平台能够启动过去 13 年中的任何 Nix 软件包，例如用户可以访问 \`https://trynix.dev/?pkg=python3%403.6.2\` 来运行 2017 年的 Python 3.6.2 交互式 shell。这项创新为可重现的开发和测试提供了强大工具，并且通过 trynix-preview GitHub Action，开发者甚至可以在浏览器中直接审查拉取请求的构建。

rss · Simon Willison · 9月10日 23:44

**「背景」** Nix 是一个纯函数式包管理器，以其可重现和声明式构建环境的能力而闻名。WebAssembly \(Wasm\) 是一种为浏览器提供高性能的二进制指令格式，允许在 Web 上运行接近原生速度的代码，从而使得在浏览器中运行复杂的应用程序（如虚拟机）成为可能。

**「影响」** 这项技术显著简化了软件测试、共享和代码审查流程，使开发者能够无需本地设置即可快速验证任何 Nix 软件包或拉取请求的构建。

**标签**: `#WebAssembly`, `#Virtualization`, `#Nix`, `#Software Development`, `#Reproducibility`

---

<a id="item-tech-news-9"></a>
### [数据中心表后供电的挑战：第一部分](https://newsletter.semianalysis.com/p/what-is-so-hard-about-behind-the) ⭐️ 8.0/10

文章《数据中心表后供电的挑战：第一部分》探讨了数据中心管理表后供电解决方案所面临的重大技术和运营难题。鉴于表后供电对现代计算基础设施至关重要，该文深入分析了这些复杂性。文章旨在阐明这些电力系统与简单的科学实验之间的区别，强调它们在商业运营中作为“印钞机”的关键作用。

rss · Semianalysis · 9月10日 14:28

**「背景」** 数据中心语境下的“表后供电”（Behind-the-Meter, BTM）指的是发电资产位于数据中心现场或与其并置，电力直接从发电机组输送给设施负载，不经过公用电网。这种模式标志着数据中心不再仅仅是电网的消费者，而是正在演变为独立的电力系统架构，对数据中心开发策略具有重要意义。

**「影响」** 数据中心正日益采用计量表后电源解决方案，例如燃气轮机和燃料电池，以在现场自行发电，这主要是受公共电网限制以及对持续可靠电力需求增长的推动。这一转变使得大型数据中心在能源供应管理上发生根本性变化，使其有效地成为独立的电力供应商。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/behind-the-meter-power-changes-data-center-equation-diego-sarmiento-8uzye">Behind - the - meter power changes the data center equation</a></li>
<li><a href="https://www.enverus.com/blog/why-data-centers-are-looking-to-natural-gas-for-behind-the-meter-power/">Natural Gas Behind - the - Meter Power for Data Centers</a></li>
<li><a href="https://build.inc/insights/behind-the-meter-power-data-centers">Behind - the - Meter Power for Data Centers : Why Gas Turbines... | Build</a></li>
<li><a href="https://www.rvninc.com/post/the-future-of-behind-the-meter-power-in-the-ai-and-data-center-era">The Future of Behind - the - Meter Power in the AI and Data Center Era</a></li>
<li><a href="https://www.partgenie.ai/insights/us-grid-constraints-towards-40gw-of-behind-the-meter-datacenter-by-2028-2">US Grid Constraints Drive Datacenter Shift to On-Site Power ...</a></li>
<li><a href="https://www.linkedin.com/pulse/why-behind-the-meter-power-becoming-non-negotiable-ai-shane-lawlor-ffgoe">Why Behind - the - Meter Power Is Becoming Non-Negotiable for AI and...</a></li>

</ul>
</details>

**标签**: `#Datacenters`, `#Energy Management`, `#Computer Systems`, `#Hardware`, `#Infrastructure`

---

<a id="item-tech-news-10"></a>
### [348M 参数模型通过展示计算步骤在多位数算术上超越 GPT-3 175B](https://www.reddit.com/r/MachineLearning/comments/1wc7hmu/i_trained_a_348m_model_trained_from_scratch_on/) ⭐️ 8.0/10

一个 348M 参数的语言模型，从零开始在 22.7B tokens 上训练，通过明确生成中间计算步骤（如列式加法、借位链、部分积乘法），在多位数算术任务上取得了优异表现。该模型在九项 GPT-3 算术子任务中平均达到 99.4%的准确率，显著优于直接给出答案的 GPT-3 175B 模型，例如在 2-5 位加减法和 2 位乘法上均达到 100%。研究发现，该模型能清晰地处理高达 14 位数的加法，其此前限制在于词汇表（位值名称）而非算术能力本身，通过将位值名称列表从 6 项扩展到 19 项，将清晰处理上限从 8 位数提升至 14 位数。尽管该模型在解决词语问题（GSM8K 4%）和除法方面表现不佳，但其“展示工作”的方法为提高大型语言模型在符号推理任务上的可靠性和效率提供了有价值的途径。

reddit · r/MachineLearning · /u/nkthebass · 9月10日 03:28

**「背景」** GPT-3 是由 OpenAI 开发的一个拥有 1750 亿参数的大型语言模型，以其在多种自然语言处理任务上的强大能力而闻名。LLaMA 架构是一种基于 Transformer 的解码器专用架构，由 Meta AI 设计，旨在提高大型语言模型的效率和可访问性。

**「影响」** 这一成果表明，通过训练模型显式地展示其推理过程，相对较小的语言模型也能在复杂的符号推理任务上取得超越大型模型的性能，为开发更高效、更可靠的 AI 系统提供了新的方向。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gitlab.com/GCABC123/magnetron-gpt-3-brain/-/blob/master/175b_samples.jsonl">175 b _samples.jsonl · master... / magnetron- gpt - 3 -brain · GitLab</a></li>
<li><a href="https://hackernoon.com/introducing-dalle-inspired-by-gpt-3-and-image-gpt-from-openai-oj3131ft">Introducing DALL·E: Inspired by GPT - 3 and Image-GPT... | HackerNoon</a></li>
<li><a href="https://medium.com/@anilAmbharii/demystifying-deepseek-ai-llama-and-openai-8d28c7857bda?ref=torment-nexus.mathewingram.com">Demystifying Deepseek AI, LLaMA and OpenAI: | by Anil... | Medium</a></li>
<li><a href="https://mbrenndoerfer.com/writing/llama-architecture-design-training-efficiency">LLaMA Architecture : Design Philosophy and Training - Interactive</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Large Language Models`, `#Arithmetic Reasoning`, `#Model Efficiency`, `#AI Systems`

---