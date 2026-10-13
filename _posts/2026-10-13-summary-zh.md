---
layout: default
title: "Horizon Summary: 2026-10-13 (ZH)"
date: 2026-10-13
lang: zh
---

> 从 42 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [循环扩散 Transformer：通过重复利用模块显著提升生成 AI 效率](#item-tech-news-1) ⭐️ 9.0/10
2. [探讨使用 C 语言开发现代 Web 应用](#item-tech-news-2) ⭐️ 8.0/10
3. [欧洲超市冷柜遭黑客攻击，自动除霜功能被激活](#item-tech-news-3) ⭐️ 8.0/10
4. [将 WiFi 7 路由器改造为 320Msps 软件定义无线电接收器](#item-tech-news-4) ⭐️ 8.0/10
5. [Python 3.15 发布，引入显式惰性导入和采样分析器](#item-tech-news-5) ⭐️ 8.0/10
6. [关于当前 AI 系统能否产生通用人工智能的机制性论证](#item-tech-news-6) ⭐️ 8.0/10
7. [U-Space 和 U-Lens：无需标签即可高效评估开源语言模型不确定性](#item-tech-news-7) ⭐️ 8.0/10
8. [learnc 工具自动优化 C 代码常量，实现 JPEG 压缩和 WebRTC VAD 性能显著提升](#item-tech-news-8) ⭐️ 8.0/10

**财经新闻**
1. [中国调整新能源汽车出口退税率](#item-finance-news-1) ⭐️ 9.0/10
2. [税务处罚新裁量基准 11 月施行，社保欠缴最高罚 3 倍](#item-finance-news-2) ⭐️ 9.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [循环扩散 Transformer：通过重复利用模块显著提升生成 AI 效率](https://www.reddit.com/r/MachineLearning/comments/1x49d61/looped_diffusion_transformer_the_same_blocks_run/) ⭐️ 9.0/10

一项新的“循环扩散 Transformer”（Looped Diffusion Transformer）架构被提出，它通过在每个去噪步骤中多次运行一组共享的 Transformer 块来提高效率，并采用深度监督和自调制注意力机制解决了朴素循环的问题。作者报告称，一个 2.6 亿参数的循环模型在多个基准测试中超越了参数量大 6.5 倍的模型，同时推理计算量减少了 4.9 倍；在固定推理预算下，增加循环深度比增加去噪步数更有效。该架构允许在采样时选择循环深度，从而在计算量和图像精细度之间进行权衡，其 B/16 代码和权重已在 Hugging Face 上开源，并采用 MIT 许可。

reddit · r/MachineLearning · /u/Fit-Ant2238 · 10月12日 18:13

**「背景」** 扩散模型（Diffusion Models）是一种生成式人工智能模型，通过逐步去除噪声来生成图像。扩散 Transformer（DiT）是这类模型的一个分支，它将 Transformer 架构应用于扩散过程，特别是在文本到图像生成任务中展现出可扩展性。

**「影响」** 这项创新为生成式 AI 领域带来了显著的计算效率提升，使得开发者和研究人员能够以更低的计算成本实现高性能的文本到图像生成，从而降低了资源门槛并加速了模型部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2212.09748">[2212.09748] Scalable Diffusion Models with Transformers</a></li>
<li><a href="https://encord.com/blog/diffusion-models-with-transformers/">Scalability of Diffusion Models with Transformer Backbone | Encord</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Diffusion Models`, `#Transformer Architecture`, `#Computational Efficiency`, `#Generative AI`

---

<a id="item-tech-news-2"></a>
### [探讨使用 C 语言开发现代 Web 应用](https://prophitt.me/writing/a-modern-web-app-in-c) ⭐️ 8.0/10

一篇技术文章深入探讨了使用 C 语言开发现代 Web 应用程序的细节和优势。该方法强调了 C 语言在性能、资源效率和安全性方面的固有优势，特别提到了利用 \`pledge\` 和 \`chroot\` 等机制来降低权限。文章旨在展示 C 语言作为一种可行且高效的 Web 开发选择，尤其适用于对系统资源和执行速度有严格要求的场景。这种方法挑战了当前主流的 Web 开发范式，为追求极致优化的开发者提供了新的视角。

hackernews · prophittcorey · 10月12日 16:13 · [社区讨论](https://news.ycombinator.com/item?id=50058528)

**「背景」** 现代网络应用开发通常倾向于使用更高级的语言和框架，而本文探讨了使用 C 语言构建现代网络应用。这种方法利用了通用网关接口（CGI），这是一种允许网络服务器执行外部程序以生成动态内容的标准协议。文章中提到的技术栈是 BCHS，即 OpenBSD 操作系统、C 语言、httpd 服务器和 SQLite 数据库的组合。

**「影响」** 对于关注系统编程和 Web 架构的开发者而言，这篇文章提供了关于如何利用 C 语言实现高性能、高资源效率和高安全性 Web 应用的宝贵见解。

**「社区讨论」** 社区评论普遍认可 C 语言在 Web 开发中的性能和效率优势，有用户分享了使用 Busybox 内置 CGI 支持、C++ 结合 WebAssembly 以及 FastCGI 的实际经验。然而，也有开发者对每次请求都调用二进制文件的 CGI 模式表示担忧，并倾向于使用带有状态的后端服务和现代框架，如 Rust 结合 Tokio 和 Actix Web。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://daily.dev/posts/a-modern-web-app-in-c-vqni6kjep">A Modern Web App in C - daily.dev</a></li>
<li><a href="https://zeli.app/story/50058528">A Modern Web App in C · 153 HN comments | Zeli</a></li>

</ul>
</details>

**标签**: `#Web Development`, `#C Programming`, `#Systems Programming`, `#Performance Optimization`, `#Security`

---

<a id="item-tech-news-3"></a>
### [欧洲超市冷柜遭黑客攻击，自动除霜功能被激活](https://www.tomshardware.com/tech-industry/cyber-security/unprecedented-cyberattack-cripples-supermarket-fridges-across-europe-as-hackers-activate-automatic-defrosting-delivery-and-store-prices-also-impacted-by-incident) ⭐️ 8.0/10

2026 年 10 月，欧洲多家超市的冷柜遭遇网络攻击，导致其自动除霜功能被激活，造成了严重的运营中断。法国连锁超市 Intermarché有 150 家门店受到影响。此次事件凸显了工业控制系统（ICS）和物联网（IoT）安全方面的关键漏洞，特别是老旧硬件的防护挑战，以及网络安全故障对现实世界造成的具体影响。初步调查怀疑攻击利用了丹佛斯（Danfoss）SM800 和 SC355 等已停产多年的旧款制冷控制器漏洞。

hackernews · Zeekaas · 10月12日 12:16 · [社区讨论](https://news.ycombinator.com/item?id=50055304)

**「背景」** 工业控制系统（ICS）是用于管理和自动化工业流程的技术，例如超市冷柜的运行。物联网（IoT）安全涉及保护连接到互联网的物理设备。将这些系统连接到互联网可以实现远程诊断、控制和效率监控，但同时也引入了新的网络安全风险，尤其是在使用缺乏最新安全更新的遗留硬件时。

**「影响」** 此次攻击直接导致受影响超市的食品变质、配送中断以及商品价格上涨，对消费者和零售商造成了显著的经济损失和运营挑战。

**「社区讨论」** 社区讨论指出，此次攻击可能利用了丹佛斯 SM800 和 SC355 等 15-20 年前的旧款控制器漏洞，这些控制器早已停止支持，但因成本原因未被替换。评论者还提到，将冷柜连接到互联网是为了实现远程诊断和提高效率，这解释了其联网的动机，并有观点猜测此次攻击可能与 2026 年 8 月美国军事基地发生的类似事件有关。

**标签**: `#Cybersecurity`, `#Industrial Control Systems`, `#IoT Security`, `#Legacy Systems`, `#Operational Technology`

---

<a id="item-tech-news-4"></a>
### [将 WiFi 7 路由器改造为 320Msps 软件定义无线电接收器](https://github.com/h0m3us3r/w1700k-sdr) ⭐️ 8.0/10

一位开发者成功将一台 WiFi 7 路由器改造为 320 Msps 软件定义无线电 \(SDR\) 接收器。该项目利用现有硬件，在 5 GHz 频段实现了高速无线信号处理，为业余爱好者和研究人员提供了一种经济实惠且新颖的高级 SDR 解决方案。这一创新方法显著降低了获取高性能 SDR 功能的门槛。

hackernews · djfergus · 10月12日 12:41 · [社区讨论](https://news.ycombinator.com/item?id=50055593)

**「背景信息」** Wi-Fi 7 是最新、最先进的 Wi-Fi 标准，引入了多项革命性变革，主要在设备密集型家庭或高速宽带环境下发挥优势。软件定义无线电（SDR）是一种无线电通信系统，它将传统上由模拟硬件实现的组件（如混频器、滤波器、调制器等）通过软件在计算机或嵌入式系统上实现，从而使其能够灵活地通过软件进行调谐和解码，监测广泛的频率范围。

**「社区讨论」** 社区普遍认为该项目“非常棒”且“令人惊叹”，提供了一种经济实惠的方式来获得 5 GHz 频段的 320 Msps 接收器。有评论指出，由于芯片组相同，该技术可能适用于 Banana Pi R4，并表达了将类似功能推广到普通 Wi-Fi 网卡以实现更广泛 SDR 应用的期望。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.esquire.com/lifestyle/tech/a73874164/best-wi-fi-7-routers/">The Best WiFi 7 Routers , What That Means, and Why It Even Matters</a></li>
<li><a href="https://switcheroo.co.uk/guides/wifi-7-router-2026">WiFi 7 Router : 5 Simple Checks to Avoid Overpaying</a></li>
<li><a href="https://www.vigi.com/pk/blog/731/how-fast-are-wifi-7-routers-/">How Fast are WiFi 7 Routers ? | TP-Link Pakistan</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software-defined_radio">Software-defined radio - Wikipedia</a></li>
<li><a href="https://radio-hobbyist.com/what-is-software-defined-radio/">What Is Software Defined Radio (SDR)? Real World Examples</a></li>
<li><a href="https://scienceinsights.org/what-is-software-defined-radio-and-how-does-it-work/">What Is Software Defined Radio and How Does It Work?</a></li>

</ul>
</details>

**标签**: `#Software Defined Radio`, `#Hardware Hacking`, `#Computer Systems`, `#Wireless Communication`, `#Open Source`

---

<a id="item-tech-news-5"></a>
### [Python 3.15 发布，引入显式惰性导入和采样分析器](https://simonwillison.net/2026/Oct/12/python-3-15/) ⭐️ 8.0/10

Python 3.15 已正式发布，同时标志着对 Python 3.10 的支持结束。新版本引入了多项重要特性，包括通过 PEP 810 实现的显式惰性导入，允许模块在首次使用时才加载，从而显著降低了应用程序的启动成本。此外，PEP 798 带来了列表、集合和字典推导式中的解包语法，并新增了一个名为 Tachyon \(profiling.sampling\) 的低开销采样分析器，用于深入洞察运行时性能。尽管 Python 3.15 的整体速度与 3.14 相比变化不大，但其实验性的 JIT 编译器在特定测试中展现了 1.2 倍的性能提升。对于维护多版本兼容性的开发者而言，此发布意味着可以停止支持 Python 3.10，并开始利用 Python 3.11 及更高版本的新功能。

rss · Simon Willison · 10月12日 18:15

**「背景」** 惰性导入是一种编程模式，它将模块的实际加载推迟到代码首次引用该模块中的符号时，这对于减少应用程序启动时间，特别是当模块具有昂贵的依赖项时非常有用。采样分析器通过定期捕获运行中进程的堆栈跟踪来工作，从而以极低的开销识别出代码中耗时最多的部分，提供系统性能的深层视图。

**「影响」** 依赖大量库或追求启动速度的 Python 开发者现在可以利用 Python 3.15 的显式惰性导入功能来优化其应用程序的性能。同时，内置的采样分析器为诊断运行时瓶颈提供了一个标准且高效的工具，减少了对第三方性能分析工具的需求。

**标签**: `#Python`, `#Programming Languages`, `#Software Engineering`, `#Open Source`, `#New Release`

---

<a id="item-tech-news-6"></a>
### [关于当前 AI 系统能否产生通用人工智能的机制性论证](https://www.reddit.com/r/MachineLearning/comments/1x4awlk/what_is_the_strongest_mechanistic_argument_that/) ⭐️ 8.0/10

Reddit 上的一篇帖子提出了一个核心问题，寻求基于计算学习理论、信息论和第一性原理的机制性论证，以探讨当前 AI 系统（特别是基于下一词元预测和强化学习的系统）是否能够产生开放式通用智能（AGI）。发帖人强调这不是一个哲学问题，而是一个关于 AI 智能背后机制的工程问题，旨在理解现有系统持续发展能否催生通用智能。此讨论旨在超越对 AGI 必然性的假设，深入探究其理论基础和实际可行性。

reddit · r/MachineLearning · /u/Repulsive\_Twist\_9221 · 10月12日 19:09

**「背景」** 当前人工智能领域的主流范式包括“下一词元预测”（next token prediction），这是大型语言模型（LLM）的核心机制，以及“强化学习”（reinforcement learning），一种通过与环境交互学习最优行为的方法。通用人工智能（AGI）指的是一种能够像人类一样理解、学习和应用智能来解决任何问题的假设性 AI。

**「影响」** 此项探究对于指导人工智能研究方向、建立对 AI 理论极限和能力的严谨理解至关重要。

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#AGI`, `#Computational Learning Theory`, `#AI Theory`

---

<a id="item-tech-news-7"></a>
### [U-Space 和 U-Lens：无需标签即可高效评估开源语言模型不确定性](https://www.reddit.com/r/MachineLearning/comments/1x44f9m/uspace_uncovering_when_and_why_uncertainty_arises/) ⭐️ 8.0/10

研究人员开发了 U-Space 和 U-Lens，这是一种新颖、无需标签且高效的方法，用于识别和分类开源语言模型中的不确定性。该方法通过计算隐藏状态指向“疑问”方向的强度与推理词元平均熵的乘积来生成不确定性分数，无需正确性标签、训练或微调，并且只需单次通过。它能解释不确定性的类型，如歧义、信息缺失、证据冲突或一般不确定性，并在对 Gemma 4、Qwen3.5 和 Magistral 等模型的 3 种子、3 模型、4 基准评估中表现优于 5 次、10 次采样及监督基线。该方法仅需一个雅可比透镜（J-Lens），其预训练版本已在 Hugging Face 上提供，用户也可使用 Anthropic 的参考代码通过约 100 个未标记提示进行拟合，从而显著降低了部署大型语言模型的成本和复杂性。项目代码可在 GitHub 仓库 s2labres/U-Space 获取。

reddit · r/MachineLearning · /u/AdRevolutionary3242 · 10月12日 15:10

**「背景」** 雅可比透镜（Jacobian lens，简称 J-Lens）是 Anthropic 公司在其关于语言模型全局工作空间的研究中提出的一种可解释性工具。它通过将语言模型内部激活状态线性映射到最终输出层，并利用模型的词嵌入层进行解码，从而揭示模型内部激活倾向于生成哪些词汇。这一工具旨在帮助研究人员理解模型内部的推理过程和信息流，与神经科学中的全局工作空间理论相关联。

**「影响」** 这项技术为基于开源推理模型构建应用的开发者提供了低成本、可解释的模型置信度信号，使他们能够根据不确定性类型（如信息缺失或歧义）自动路由低置信度答案、触发信息检索或提出澄清问题，从而显著提升大型语言模型部署的可靠性和调试效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/global-workspace">A global workspace in language models \ Anthropic</a></li>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the ...</a></li>
<li><a href="https://unfinishablemap.org/research/anthropic-global-workspace-j-space-2026-07-07/">Research Notes - Anthropic&#x27;s Global Workspace / J-Space in ...</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Language Models`, `#Interpretability`, `#Uncertainty Quantification`

---

<a id="item-tech-news-8"></a>
### [learnc 工具自动优化 C 代码常量，实现 JPEG 压缩和 WebRTC VAD 性能显著提升](https://www.reddit.com/r/MachineLearning/comments/1x4dlbm/learnc_fit_the_constants_in_existing_c_code_to/) ⭐️ 8.0/10

\`learnc\` 是一款开源工具，能够根据用户编写的 C 语言评分函数，自动调整现有 C 代码中已命名的常量，并将优化后的值写回原文件。该工具在多个应用中展现了显著的性能提升，例如在 \`stb\_image\_write.h\` 的 JPEG 压缩中，实现了在相同 SSIM 下 9.1% 的 BD-rate 降低，优于 \`mozjpeg\` 的 2.7%。此外，它还将 Google WebRTC VAD \(\`vad\_core.c\`\) 的 F1 分数从 0.810 提升至 0.859。该工具适用于调整数十到数百个常量，但 JPEG 增益在 1 bpp 以下不明显，其代码已在 MIT 许可下开源。

reddit · r/MachineLearning · /u/keep\_up\_sharma · 10月12日 20:51

**「背景」** 许多 C 语言程序，特别是图像处理和音频算法，依赖于硬编码的常量来控制其行为和性能。这些常量通常是手动确定的，可能并非在所有数据集或使用场景下都达到最佳效果。\`learnc\` 工具通过自动化这一优化过程，旨在提升现有代码的效率和质量。

**「影响」** \`learnc\` 为 C 语言开发者提供了一种无需修改核心逻辑即可显著提升现有代码性能的实用方法，尤其在图像压缩和语音活动检测等领域，可实现高达 9.1% 的 JPEG 压缩效率提升和 4.9 F1 分数的 WebRTC VAD 准确度改进。

**标签**: `#Software Engineering`, `#Code Optimization`, `#Machine Learning`, `#Computer Systems`, `#Open Source`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [中国调整新能源汽车出口退税率](https://www.news.cn/20261012/9709731f470b42f9a84825c2e4eb914b/c.html) ⭐️ 9.0/10

中国财政部和税务总局宣布，自 2027 年 4 月 1 日起，新能源汽车的增值税出口退税率将从 13%下调至 9%，同时取消电子烟设备装置的出口退税。

telegram · zaihuapd · 10月12日 11:00

**「背景」** 中国此前对新能源汽车出口提供 13%的增值税出口退税，旨在通过退还国内税款来提高其在国际市场上的竞争力。

**「影响」** 此举可能导致中国新能源汽车和电子烟设备出口商的出口成本上升，进而影响其利润率和国际市场竞争力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://chinasourcingagent.com/sourcing-new-energy-vehicles-from-china/">Sourcing New Energy Vehicles From China : 2026 NEV Import Guide</a></li>
<li><a href="https://www.registrationchina.com/articles/china-battery-export-tax-rebates-cancellation/">China &#x27;s Battery Export Tax Rebates Cancellation in 2027: Impact on...</a></li>

</ul>
</details>

**标签**: `#New Energy Vehicles`, `#Export Policy`, `#Taxation`, `#China Economy`, `#Automotive Industry`

---

<a id="item-finance-news-2"></a>
### [税务处罚新裁量基准 11 月施行，社保欠缴最高罚 3 倍](https://fgk.chinatax.gov.cn/zcfgk/c100012/c5252754/content.html) ⭐️ 9.0/10

China&\#x27;s State Taxation Administration announced new national administrative penalty standards, effective November 2026, imposing fines of up to three times the owed amount for employers who underpay social security contributions.

telegram · zaihuapd · 10月13日 02:45

**标签**: `#Taxation Policy`, `#Social Security`, `#Regulatory Change`, `#China Economy`, `#Employer Obligations`

---