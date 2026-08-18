---
layout: default
title: "Horizon Summary: 2026-08-18 (ZH)"
date: 2026-08-18
lang: zh
---

> 从 37 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [Qwen 3.8 27B 在人工智能分析指数中获得 52 分，性能媲美大型模型](#item-tech-news-1) ⭐️ 9.0/10
2. [macOS 26.7 代码揭示 Apple 智能在中国大陆的审查机制](#item-tech-news-2) ⭐️ 9.0/10
3. [修复变砖的 Framework 笔记本电脑](#item-tech-news-3) ⭐️ 8.0/10
4. [Linux 7.3 改进 VRAM 耗尽时的性能](#item-tech-news-4) ⭐️ 8.0/10
5. [实地测量证实数据中心导致周边气温小幅升高](#item-tech-news-5) ⭐️ 8.0/10
6. [Mojo🔥 编程语言现已根据 Apache 2 许可开源，开放编译器和工具链](#item-tech-news-6) ⭐️ 8.0/10
7. [在 264KB RAM 微控制器上运行扩散模型](#item-tech-news-7) ⭐️ 8.0/10
8. [苹果开发带摄像头 AirPods，macOS Tahoe 26.7 RC 演示视觉智能](#item-tech-news-8) ⭐️ 8.0/10
9. [企业微信 5.0.10 开放 CLI 与 MCP，支持主流 AI Agent 接入十大办公模块](#item-tech-news-9) ⭐️ 8.0/10
10. [中国要求部分政府机构提前卸载定制版 Windows 10](#item-tech-news-10) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Qwen 3.8 27B 在人工智能分析指数中获得 52 分，性能媲美大型模型](https://simonwillison.net/2026/Aug/17/qwen-38-27b-scores-52/) ⭐️ 9.0/10

270 亿参数的 AI 模型 Qwen 3.8 27B 在 Artificial Analysis Intelligence Index 上获得了 52 分，这一成绩与参数量远大于它的模型相当。具体来说，它与 GPT-5.6 Luna（max）得分相同，仅比 7530 亿参数的 GLM-5.2（max）和 1.7 万亿参数的 DeepSeek V4 Pro 0813（max）低一分。Qwen 3.8 27B 的这一表现表明了在高效且强大的语言模型方面取得了重大进展，预示着高性能大型语言模型可能变得更易于访问。

rss · Simon Willison · 8月17日 23:58

**「背景」** Artificial Analysis Intelligence Index 是由 Artificial Analysis 开发的一项综合指标，旨在评估大型语言模型的“智能”水平。该指数通过整合多种基准测试，包括问答数据集、代理能力、长上下文推理和特定用例评估，来衡量模型的性能。它还考虑了运行这些评估的成本，以提供一个全面的模型效率和能力视图。

**「影响」** Qwen 3.8 27B 以显著更小的参数量实现了与超大型模型相近的性能，这为开发者和组织提供了在计算资源有限的情况下部署高性能大型语言模型的潜力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/">AI Model &amp; API Providers Analysis | Artificial Analysis</a></li>
<li><a href="https://artificialanalysis.ai/models">Comparison of AI Models across Intelligence , Performance, and Price</a></li>
<li><a href="https://summify.io/discover/artificial-analysis-the-independent-llm-analysis-house-with--v5mBje/">Artificial Analysis : The Independent LLM Analysis House... | Summify</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Large Language Models`, `#Model Efficiency`, `#Qwen`, `#Benchmarking`

---

<a id="item-tech-news-2"></a>
### [macOS 26.7 代码揭示 Apple 智能在中国大陆的审查机制](https://www.macrumors.com/2026/08/17/macos-26-7-unreleased-apple-devices/) ⭐️ 9.0/10

据报道，macOS 26.7 的代码揭示了 Apple 计划在中国大陆地区为其“Apple 智能”写作工具集成一套独立的、云端控制的内容审查和处罚机制。代码显示，若多次触发安全警报，“写作工具”将暂时受限，并且对于某些无法编辑的内容，系统会显示相应提示。这表明中国版 Apple 智能的写作功能将拥有独立的内容安全过滤、拦截和处罚系统，其审查规则可通过云端远程下发。

telegram · zaihuapd · 8月18日 02:16

**「背景」** Apple Intelligence 是苹果公司推出的一套人工智能功能，旨在集成到其设备操作系统中，提供包括写作辅助在内的多种智能服务。macOS 26.7 是苹果近期发布的操作系统更新版本，其中包含了对未来产品和功能的引用。

**「影响」** 中国大陆的 Apple 智能写作工具用户将受到一套独立的、云端控制的内容审查和处罚机制的约束。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.macrumors.com/2026/08/17/macos-26-7-unreleased-apple-devices/">macOS Tahoe 26.7 is Full of References to Unreleased Apple ... - MacRumors</a></li>
<li><a href="https://www.macrumors.com/2026/08/18/apple-just-leaked-more-than-10-new-products/">Apple Just Leaked More Than 10 New Products - MacRumors</a></li>
<li><a href="https://www.macrumors.com/2026/03/30/apple-intelligence-china-mistake/">Apple Intelligence Accidentally Goes Live in China Before ... - MacRumors</a></li>

</ul>
</details>

**标签**: `#Apple Intelligence`, `#Censorship`, `#AI Ethics`, `#Software Engineering`, `#China`

---

<a id="item-tech-news-3"></a>
### [修复变砖的 Framework 笔记本电脑](https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/) ⭐️ 8.0/10

一篇关于修复因固件更新失败而“变砖”的 Framework 笔记本电脑的文章引发了广泛讨论。该文章详细描述了如何使用 20 美元的工具修复一台 AMD 7040 系列 Framework 13 笔记本电脑，强调了固件更新故障、制造商责任以及维修权等关键问题。这凸显了技术行业中消费者在面对软件导致硬件故障时的困境。

hackernews · jp\_sc · 8月18日 13:18 · [社区讨论](https://news.ycombinator.com/item?id=49345220)

**「背景信息」** Framework 笔记本电脑由 Framework Computer, Inc. 生产，以其模块化和易于维修的设计而闻名，旨在支持维修权运动。当设备（例如配备 AMD 7040 系列处理器的 Framework 笔记本电脑）因固件更新失败而变得完全无法操作时，通常被称为“变砖”。

**「影响」** 官方固件更新可能导致设备“变砖”，迫使受影响的用户进行复杂维修或面临设备报废，这凸显了消费者在面对制造商软件缺陷时的脆弱性。

**「社区讨论」** 社区普遍认为，制造商应对其提供的有缺陷的固件更新负责，这些更新可能导致设备“变砖”，并建议通过小额索赔法庭追究责任。评论者指出，PC 制造商对因 BIOS 更新导致的设备故障漠不关心，并呼吁如果安装自定义固件会使保修失效，那么官方更新应延长保修期，以应对更新导致设备性能下降的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Framework_Laptop">Framework Laptop</a></li>
<li><a href="https://grokipedia.com/page/Framework_Laptop_13">Framework Laptop 13</a></li>
<li><a href="https://en.wikipedia.org/wiki/Template:AMD_Ryzen_Mobile_7040_series">Template:AMD Ryzen Mobile 7040 series - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Hardware Repair`, `#Firmware Updates`, `#Consumer Rights`, `#Tech Industry Practices`, `#Laptop Hardware`

---

<a id="item-tech-news-4"></a>
### [Linux 7.3 改进 VRAM 耗尽时的性能](https://pixelcluster.dev/VRAM-Overcommit/) ⭐️ 8.0/10

即将发布的 Linux 内核 7.3 版本预计将显著提升图形内存 \(VRAM\) 完全利用时的系统性能。此次更新旨在解决内存密集型应用程序（如 AI/ML、游戏和图形工作负载）的关键瓶颈，从而在 VRAM 耗尽时提供更流畅的用户体验。这一核心内核增强功能对广泛的应用程序具有高度相关性和影响力。

hackernews · flaburgan · 8月18日 07:51 · [社区讨论](https://news.ycombinator.com/item?id=49342719)

**「背景」** VRAM overcommit（显存超额分配）是 GPU 驱动中的一种机制，允许应用程序请求超出显卡物理显存容量的内存，由驱动程序管理哪些数据驻留在物理 VRAM 中。此前，Natalie Vock 的补丁已显著提升了 AMD GPU 在显存有限情况下的性能，而即将发布的 Linux 7.3 内核将继续推进这项显存管理优化工作。

**「影响」** 这项改进将直接缓解 AI/ML、游戏和图形等内存密集型应用程序在 VRAM 资源紧张时遇到的性能瓶颈，为用户带来更稳定的系统响应。

**「社区讨论」** 社区普遍对 Linux 7.3 带来的 VRAM 性能改进表示兴奋和期待，有用户提到当前在使用 Nvidia 显卡时仍面临 VRAM 分页支持不足的问题，并希望未来能有针对主内存耗尽导致系统冻结的类似改进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.phoronix.com/news/Linux-7.3-Improving-vRAM-Mgmt">Linux 7 . 3 To Land Initial Code Improving vRAM ... - Phoronix</a></li>
<li><a href="https://www.osnews.com/story/145846/beyond-the-limits-of-physical-vram/">Beyond the limits of physical VRAM – OSnews</a></li>
<li><a href="https://imasters.com.br/noticia/o-linux-7-3-melhora-a-performance-quando-falta-vram-na-gpu">Linux 7 . 3 : melhor gerenciamento de VRAM em GPUs AMD | iMasters</a></li>

</ul>
</details>

**标签**: `#Linux Kernel`, `#Performance Optimization`, `#Memory Management`, `#VRAM`, `#Computer Systems`

---

<a id="item-tech-news-5"></a>
### [实地测量证实数据中心导致周边气温小幅升高](https://asmedigitalcollection.asme.org/sustainablebuildings/article/7/2/024501/1233035/Data-Center-Waste-Heat-as-an-Emerging-Urban) ⭐️ 8.0/10

一项经过同行评审的研究提供了实地测量数据，表明数据中心确实会导致周边区域气温升高，尽管增幅不大。研究发现，在数据中心园区下风向约 500 米范围内的邻近区域，平均气温从上风向的约 42.7 °C 升高至 43.5 °C，温差约为 0.8 °C。这项研究为评估关键技术基础设施的环境影响提供了具体的量化数据，有助于推动可持续发展努力和城市规划。

hackernews · cwwc · 8月18日 17:24 · [社区讨论](https://news.ycombinator.com/item?id=49349147)

**「背景信息」** 数据中心在运行过程中会消耗大量能源，其中很大一部分转化为废热。这些废热通常被排放到周围环境中，引发了对其局部环境影响的担忧，包括可能导致附近区域气温升高。因此，研究人员正在探索废热回收等技术，以提高能源效率并减轻这些环境影响。

**「影响」** 数据中心产生的废热会在其周围区域造成可测量的局部气温升高，形成“数据热岛效应”，平均可使气温升高约 2°C，并可能影响当地微气候。

**「社区讨论」** 社区成员对数据中心环境影响的讨论存在分歧，一些人对“数据中心恐慌”的真实性表示怀疑，并指出可能存在政治动机，而另一些人则引用了凤凰城数据中心导致气温升高高达 4 摄氏度的案例。然而，有评论指出本研究观察到的平均温升仅为 0.8 摄氏度，并质疑标题可能夸大了平均影响，同时也有人呼吁对该议题进行更客观的讨论，并将其与炼油厂等其他工业污染源进行比较。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1364032123006342">Waste heat recoveries in data centers: A review - ScienceDirect</a></li>
<li><a href="https://news.asu.edu/20260518-environment-and-sustainability-turning-down-heat-data-centers">Turning down the heat from data centers - ASU News</a></li>
<li><a href="https://www.mdpi.com/2071-1050/17/22/10101">Zero-Carbon Development in Data Centers Using Waste Heat ... - MDPI</a></li>
<li><a href="https://www.linkedin.com/posts/shaolei-ren-68557415_the-data-heat-island-effect-quantifying-activity-7444606068711936000-Vyzx">The data heat island effect : quantifying the impact of AI data centers ...</a></li>
<li><a href="https://hackaday.com/2026/04/07/the-heat-island-effect-is-warming-up-the-ai-data-center-controversy/">The Heat Island Effect Is Warming Up The AI Data Center ... | Hackaday</a></li>
<li><a href="https://www.from-the-grey.com/post/data-centers-create-heat-islands-and-change-local-weather-patterns">Data Centers Create Heat Islands and Change Local Weather Patterns</a></li>

</ul>
</details>

**标签**: `#Data Centers`, `#Environmental Impact`, `#Sustainability`, `#Infrastructure`, `#Computer Systems`

---

<a id="item-tech-news-6"></a>
### [Mojo🔥 编程语言现已根据 Apache 2 许可开源，开放编译器和工具链](https://simonwillison.net/2026/Aug/18/mojo-is-now-open-source/) ⭐️ 8.0/10

Mojo 编程语言已根据 Apache 2 许可开源，兑现了自 2023 年 5 月以来的承诺，并开放了其编译器和工具链。该语言此前已于上周发布了 1.0 版本。Mojo 最初旨在成为 Python 的超集，但其愿景在 2025 年 8 月左右发生变化，现在它是一个独立的语言，专注于优化 GPU 编程，并采用受 Python 启发的语法，但并非与现有 Python 代码 100% 兼容。Mojo 专为高性能 AI/ML 应用设计，旨在简化 GPU 编程。

rss · Simon Willison · 8月18日 21:39

**「背景」** Mojo 是一种编程语言，最初的目标是成为 Python 的超集，以便利用现有 Python 生态系统。然而，其发展方向已调整为一种独立的语言，专注于为人工智能和机器学习工作负载提供高性能，尤其是在 GPU 编程方面。

**「影响」** Mojo 的开源将使更广泛的开发者社区能够采用、贡献和利用其高性能 AI/ML 能力，从而加速相关领域的技术创新和应用。

**标签**: `#Programming Languages`, `#Open Source`, `#Artificial Intelligence`, `#Machine Learning`, `#Software Engineering`

---

<a id="item-tech-news-7"></a>
### [在 264KB RAM 微控制器上运行扩散模型](https://www.reddit.com/r/MachineLearning/comments/1vrk7t5/trained_an_diffusion_model_that_runs_on_264kb_of/) ⭐️ 8.0/10

一位开发者成功地在仅有 264KB SRAM 的微控制器上训练并部署了一个 32x32 像素的图像生成扩散模型。尽管利用板载 FPGA 加速器（包含两个 INT8 MAC 引擎）旨在提高计算速度，但由于高 I/O 操作导致内存瓶颈，FPGA 加速后的系统生成一张图像耗时约 220 秒，反而比仅使用 MCU 的 70 秒更慢。该项目展示了在极端资源受限环境下运行 AI 模型的挑战，其中大量量化和内存限制导致生成图像出现噪声，但仍有部分效果良好。

reddit · r/MachineLearning · /u/PandaBean18 · 8月18日 09:26

**「背景」** 扩散模型是一种生成模型，通过逐步去除噪声来从随机数据中生成清晰图像。TinyML 是指在资源受限的嵌入式设备上部署机器学习模型，旨在实现低功耗、低延迟的边缘 AI 应用。

**「影响」** 该项目具体展示了开发者在将扩散模型等高级 AI 模型部署到资源极其受限的 TinyML 设备上时，即使有专用硬件加速，也会面临严重的内存和 I/O 瓶颈，这与 TinyML 系统固有的挑战相符。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mdpi.com/1999-5903/17/6/257">Advancing TinyML in IoT: A Holistic System-Level Perspective for ... - MDPI</a></li>
<li><a href="https://arxiv.org/pdf/2003.04821">Benchmarking TinyML Systems: Challenges and Direction</a></li>
<li><a href="https://arxiv.org/pdf/2509.04721">Real-Time Performance Benchmarking of TinyML Models in Embedded Systems ...</a></li>

</ul>
</details>

**标签**: `#TinyML`, `#Embedded AI`, `#Hardware Acceleration`, `#Diffusion Models`, `#Model Quantization`

---

<a id="item-tech-news-8"></a>
### [苹果开发带摄像头 AirPods，macOS Tahoe 26.7 RC 演示视觉智能](https://www.macrumors.com/2026/08/17/camera-equipped-airpods-macos-26-7/) ⭐️ 8.0/10

苹果据报道正在开发代号为 B790 的配备摄像头的 AirPods，其视觉智能功能已在 macOS Tahoe 26.7 RC 的演示中亮相。该设备能够识别书名并保存信息，同时 Siri 也能基于佩戴者周围环境提供上下文回答和记录信息。据 Mark Gurman 透露，这款新产品最快可能于 9 月发布，标志着苹果在可穿戴设备中集成 AI 视觉技术的重要进展。

telegram · zaihuapd · 8月18日 02:00

**「背景」** AirPods 是苹果公司推出的无线耳机系列，以其便捷的连接和音频体验而闻名。此次报道的相机版 AirPods 则是在传统功能基础上，集成了摄像头和视觉智能技术，旨在扩展其在环境感知和信息交互方面的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.macrumors.com/2026/08/17/camera-equipped-airpods-macos-26-7/">Apple&#x27;s Camera-Equipped AirPods Confirmed: See Them in Action</a></li>
<li><a href="https://www.iclarified.com/101810/apple-accidentally-leaks-camera-airpods-demo-in-macos-tahoe-rc-video">Apple Accidentally Leaks Camera AirPods Demo in macOS Tahoe RC [Video ...</a></li>
<li><a href="https://gadgets.beebom.com/news/apple-airpods-with-camera-spotted-in-video">Apple&#x27;s Camera AirPods Spotted in a Video Hidden Inside macOS Tahoe 26. ...</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Hardware`, `#Wearable Technology`, `#Computer Vision`

---

<a id="item-tech-news-9"></a>
### [企业微信 5.0.10 开放 CLI 与 MCP，支持主流 AI Agent 接入十大办公模块](https://mp.weixin.qq.com/s/uJf57P15-FQL_u6jLHiGYA) ⭐️ 8.0/10

企业微信 5.0.10 版本已向所有企业开放 CLI（命令行界面）和 MCP（多云平台）能力，允许 WorkBuddy、DeepSeek Harness 等主流 AI Agent 以及企业自建 Agent 直接调用其十大核心办公模块。此次开放支持 AI 与人员权限隔离、关键操作人工审批、限时授权及完整审计等安全机制，并使 AI 能够读取文档和表格、分析数据，进而生成提案 PPT 或经营看板。

telegram · zaihuapd · 8月18日 06:22

**「背景信息」** 命令行界面（CLI）是一种通过文本命令与程序交互的方式，而管理控制平面（MCP）通常指用于管理和协调系统或服务的平台。WorkBuddy 是腾讯云代码助手推出的 AI Agent 办公工具，能够自主规划并交付多模态复杂任务结果，支持多 Agent 并行工作以提高效率。DeepSeek Harness 是 DeepSeek AI 推出的开源、基于插件的 AI Agent 框架，其所有功能，包括模型、工具、技能和界面等，都可作为插件进行替换或重组。

**「影响」** 此举显著提升了企业微信作为企业级协作平台的集成能力，使企业能够更安全、高效地将 AI 智能体引入日常办公流程，实现数据分析和内容生成等任务的自动化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://copilot.tencent.com/work/">WorkBuddy - AI Agent 办公新范式</a></li>
<li><a href="https://www.workbuddy.ai/">WorkBuddy - AI Agent for Everyday Office Work</a></li>
<li><a href="https://www.tencentcloud.com/act/pro/workbuddy">WorkBuddy · Your scenario-based AI All-in-one Package</a></li>
<li><a href="https://www.deepseek.com/harness/en/">DeepSeek Harness developer preview: Everything is a plugin</a></li>
<li><a href="https://www.scriptbyai.com/deepseek-harness/">DeepSeek Harness : Open-Source Plugin-Based AI Agent Harness</a></li>
<li><a href="https://deepseekv4guide.org/guides/harness-agent-capability">Why a Harness Makes AI Agents Better | DeepSeek V4 Guide</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Enterprise Software`, `#API Integration`, `#Automation`, `#Machine Learning`

---

<a id="item-tech-news-10"></a>
### [中国要求部分政府机构提前卸载定制版 Windows 10](https://www.bloomberg.com/news/articles/2026-08-18/china-axing-microsoft-windows-from-state-agencies-ahead-of-plan) ⭐️ 8.0/10

中国国家安全部已要求部分政府相关机构卸载定制版 Windows 10，将原定于 2027 年 2 月的停用计划提前了数月。此举源于对数据安全的担忧，但未具体说明任何漏洞。微软方面表示，未发现影响该产品的安全事件，并且该产品仍在定期接收安全更新。

telegram · zaihuapd · 8月18日 06:22

**「背景」** 中国政府此前一直在其机构中使用定制版的 Windows 10 操作系统。此举是其逐步转向使用国产替代方案的长期计划的一部分，原定于 2027 年 2 月完成停用。

**「影响」** 中国政府机构提前停用定制版 Windows 10，标志着中国在减少对外国技术依赖方面迈出了新的一步，尽管此举对微软全球收入的直接财务影响有限，因中国市场仅占其全球营收的约 1.5%。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tech.yahoo.com/computing/articles/china-finally-pulling-windows-10-112000903.html">China is finally pulling Windows 10 from government machines — and says ...</a></li>
<li><a href="https://www.techspot.com/news/113529-china-finally-pulling-windows-10-government-machines-ahead.html">China pulls the plug on Windows 10 for government machines ... - TechSpot</a></li>
<li><a href="https://www.yahoo.com/news/world/articles/china-reportedly-orders-state-agencies-101142646.html">China reportedly orders state agencies to uninstall its government-only ...</a></li>
<li><a href="https://www.tradingkey.com/analysis/stocks/us-stocks/262114664-win10-government-removal-microsoft-china-headwinds-tradingkey">Win10 Government Edition Phased Out Early as Microsoft&#x27;s China Business Faces New Headwinds</a></li>
<li><a href="https://www.chinatechnews.com/2026/08/18/127701-china-removes-microsoft-windows-at-state-users-ahead-of-plan">China removes Microsoft Windows at state users ahead of plan - ChinaTechNews.com</a></li>

</ul>
</details>

**标签**: `#Technology Industry`, `#Computer Systems`, `#National Security`, `#Operating Systems`, `#Geopolitics`

---