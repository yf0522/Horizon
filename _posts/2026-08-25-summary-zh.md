---
layout: default
title: "Horizon Summary: 2026-08-25 (ZH)"
date: 2026-08-25
lang: zh
---

> 从 45 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [OpenAI 自研推理芯片 Jalapeño 测试结果公布，性能超越英伟达 GB300](#item-tech-news-1) ⭐️ 9.0/10
2. [英伟达 Vera Rubin NVL72 首测，AI 智能体吞吐量暴涨 30 倍](#item-tech-news-2) ⭐️ 9.0/10
3. [GPT-5.6 Sol 设计定制 CPU 成功运行《毁灭战士》](#item-tech-news-3) ⭐️ 9.0/10
4. [FDA 批准首款可同时监测酮体和血糖水平的可穿戴设备](#item-tech-news-4) ⭐️ 8.0/10
5. [Apple 推出 M6 和 M5 Ultra 芯片，大幅提升性能和 AI 计算](#item-tech-news-5) ⭐️ 8.0/10
6. [Apple 发布搭载 M5 Max 和 M5 Ultra 芯片的新款 Mac Studio](#item-tech-news-6) ⭐️ 8.0/10
7. [Apple 发布搭载 M6 和 M5 Pro 芯片的新款 Mac mini](#item-tech-news-7) ⭐️ 8.0/10
8. [Nitter 项目收到停止并终止函](#item-tech-news-8) ⭐️ 8.0/10
9. [Firefox 157 将默认在所有平台上支持 JPEG XL](#item-tech-news-9) ⭐️ 8.0/10

**财经新闻**
1. [美国制裁威胁下中国加速金融系统多元化](#item-finance-news-1) ⭐️ 9.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [OpenAI 自研推理芯片 Jalapeño 测试结果公布，性能超越英伟达 GB300](https://newsletter.semianalysis.com/p/openai-jalapeno-better-than-nvidia) ⭐️ 9.0/10

OpenAI 公布了其首款自研推理芯片“Jalapeño”的初步测试数据，声称在 GPT-OSS 120B、DeepSeek R1 670B 和 Kimi K2.5 1T 等模型上，其单位功耗 AI 工作量是英伟达 GB300 的 1.5 至 1.9 倍，端到端延迟低 1.7 至 3.6 倍，高交互场景性能高 2.1 至 4.1 倍。这款与博通合作开发的芯片额定功耗 700 瓦，实测持续功耗不高于 550 瓦，主要用于模型推理而非训练，并计划于今年底前在 OpenAI 自有算力设施中部署，同时第二代和第三代芯片已在开发设计中。

hackernews · Semianalysis · 8月25日 14:06 · [社区讨论](https://news.ycombinator.com/item?id=49434378)

**「背景」** 专用集成电路（ASIC）是为特定应用设计的芯片，相较于通用 GPU，通常能在特定任务上提供更高的能效比和性能。OpenAI 开发自研 ASIC 旨在降低其日益增长的 AI 模型推理成本，并减少对现有硬件供应商（如英伟达）的依赖，以优化其 AI 基础设施。

**「影响」** OpenAI 自研芯片的成功部署可能挑战英伟达在 AI 硬件市场的主导地位，并有望显著降低未来 AI 模型的推理成本和能耗，从而加速 AI 技术的普及和应用。

**「社区讨论」** 社区讨论认为，OpenAI 和 Anthropic 等公司已达到可将 LLM 权重固化到芯片中的规模，并指出 Deepseek 和 Kimi 作为基准模型的重要性。有评论将当前推理芯片的发展比作早期 3dfx 等显卡竞争，并预测硬件持续改进将导致 token 价格持续下降，同时注意到 AI 效率与人类语言效率的差距正在缩小。

**标签**: `#Artificial Intelligence`, `#Hardware`, `#Custom Silicon`, `#Industry Competition`, `#Machine Learning Infrastructure`

---

<a id="item-tech-news-2"></a>
### [英伟达 Vera Rubin NVL72 首测，AI 智能体吞吐量暴涨 30 倍](https://blogs.nvidia.com/blog/vera-rubin-nvl72-efficiency-ai-agents/) ⭐️ 9.0/10

英伟达首次公布了其下一代 Vera Rubin NVL72 AI 机柜的片上实测数据，显示在运行 DeepSeek-V4-Pro 的智能体编码任务时，其每兆瓦吞吐量较 GB300 最高提升 30 倍，每百万 Token 成本最高下降 35 倍。同期，英伟达还宣布量产推理加速芯片 Groq 3 LPX，该芯片在运行 Gemma 4 31B 时可达到每秒 3400 Token 的输出速度，并发布了专为智能体设计的 Vera CPU。马斯克的 SpaceXAI 已宣布部署 Vera CPU，并计划在 2028 年将优化版机柜送入太空，预示着该技术在未来 AI 应用中的巨大潜力。

telegram · zaihuapd · 8月25日 14:48

**「背景」** 英伟达是全球领先的 AI 硬件供应商，持续推出高性能计算平台以满足人工智能模型日益增长的计算需求，例如其先前的 GB300 系列。AI 智能体是能够理解、推理并执行复杂任务的自动化程序，其高效运行对底层计算硬件的性能和成本效益有着极高要求。

**「影响」** 对于开发和部署 AI 智能体应用的组织而言，Vera Rubin NVL72 系统有望大幅降低运营成本并显著提升处理能力，从而加速 AI 智能体技术的实际落地和普及。

**标签**: `#AI Hardware`, `#Machine Learning`, `#NVIDIA`, `#Performance`, `#AI Agents`

---

<a id="item-tech-news-3"></a>
### [GPT-5.6 Sol 设计定制 CPU 成功运行《毁灭战士》](https://www.tomshardware.com/tech-industry/artificial-intelligence/ai-coder-gets-doom-running-on-a-custom-cpu-designed-by-gpt-5-6-sol-game-viewport-is-overlaid-on-a-pulsing-schematic-of-the-cpu-in-turing-completes-sandbox-environment) ⭐️ 9.0/10

AI 爱好者 Angel 展示了由 GPT-5.6 Sol 设计的定制 CPU &quot;Codex-R32&quot;，该 CPU 在教育解谜游戏 Turing Complete 的沙盒模式中成功启动并运行了经典游戏《毁灭战士》\(1993\)。这个完整的 CPU 是从基础逻辑元件搭建而成，游戏画面叠加在处理器门级电路的实时脉冲示意图上。它运行的是基于 C 语言的 PureDOOM 移植版，该版本被编译为 RV32IM 机器码，直接在仿真硬件上执行。此次演示突显了 AI 在复杂硬件设计方面的先进能力。

telegram · zaihuapd · 8月25日 15:23

**「背景」** Turing Complete 是一款教育解谜游戏，允许玩家从逻辑门等基础元件构建虚拟计算机。而《毁灭战士》\(1993\) 是一款经典的 FPS 游戏，常被用作衡量计算系统能力的标志性测试。RV32IM 是一种基于 RISC-V 架构的 32 位指令集，支持整数和乘除法操作。

**「影响」** 此次演示具体展现了 AI 在从底层逻辑门设计功能性 CPU 方面的突破性能力，预示着未来硬件工程和系统设计可能由 AI 辅助甚至主导，从而加速新硬件的开发进程。

**标签**: `#Artificial Intelligence`, `#Hardware Design`, `#Computer Architecture`, `#Software Engineering`

---

<a id="item-tech-news-4"></a>
### [FDA 批准首款可同时监测酮体和血糖水平的可穿戴设备](https://www.fda.gov/news-events/press-announcements/fda-authorizes-first-wearable-device-continuously-monitors-both-ketone-levels-and-blood-sugar) ⭐️ 8.0/10

美国食品药品监督管理局（FDA）已批准首款能够持续监测酮体和血糖水平的可穿戴设备。这一授权标志着健康技术领域的显著进步，为个人健康管理和未来的自动化健康系统带来了新的可能性。该设备通过提供双重生物标记物的实时数据，有望帮助用户更有效地管理其代谢健康状况。

hackernews · sunnynagra · 8月25日 19:07 · [社区讨论](https://news.ycombinator.com/item?id=49439017)

**「背景」** 糖尿病是一种影响身体处理血糖（葡萄糖）的慢性疾病，需要仔细监测以预防并发症。酮体是身体燃烧脂肪而非葡萄糖获取能量时产生的化学物质，其积累可能导致糖尿病酮症酸中毒（DKA），这是糖尿病患者的一种危及生命的并发症。因此，同时持续监测葡萄糖和酮体水平，特别是对于有 DKA 风险的个体，能提供更全面的代谢健康视图。

**「影响」** 这款设备的获批为糖尿病患者及其他需要监测代谢健康的人群提供了一个新的重要工具，有助于更全面地了解和管理其生理指标，并可能推动自动化健康管理系统的发展。

**「社区讨论」** 社区讨论中，有用户对这项技术进步表示欣慰，并提及了糖尿病酮症酸中毒的悲剧，强调了此类设备的重要性。同时，也有人对非侵入式血糖监测的准确性表示怀疑，并关注设备报销问题以确保其广泛普及；另有评论指出，酮体监测对于血糖控制良好的普通糖尿病患者可能用处不大，主要适用于血糖管理极端情况。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.fda.gov/news-events/press-announcements/fda-authorizes-first-wearable-device-continuously-monitors-both-ketone-levels-and-blood-sugar">FDA Authorizes First Wearable Device That Continuously Monitors Both Ketone Levels and Blood Sugar | FDA</a></li>
<li><a href="https://www.patientcareonline.com/view/fda-authorizes-first-wearable-device-to-continuously-monitor-glucose-ketones">FDA Authorizes First Wearable Device to Continuously Monitor Glucose, Ketones | Patient Care Online</a></li>
<li><a href="https://www.upi.com/Top_News/US/2026/08/25/fda-oks-blood-sugar-ketone-monitor/5521787688375/">FDA approves first wearable device to monitor blood sugar, ketone levels - UPI.com</a></li>

</ul>
</details>

**标签**: `#Wearable Technology`, `#Medical Devices`, `#Health Tech`, `#Artificial Intelligence`, `#Hardware`

---

<a id="item-tech-news-5"></a>
### [Apple 推出 M6 和 M5 Ultra 芯片，大幅提升性能和 AI 计算](https://www.apple.com/newsroom/2026/08/apple-introduces-m6-and-m5-ultra-for-a-big-leap-in-performance-and-ai-compute/) ⭐️ 8.0/10

Apple 于 2026 年 8 月 25 日发布了新一代 M6 和 M5 Ultra 芯片，标志着其高性能处理器的一次重大更新。这些芯片承诺显著增强性能和 AI 计算能力，对软件工程师和 AI 从业者尤为重要。作为广泛采用的 M 系列芯片的最新迭代，此次更新预计将带来处理能力和 AI 计算方面的实质性改进。

hackernews · interpol\_p · 8月25日 13:01 · [社区讨论](https://news.ycombinator.com/item?id=49433292)

**「背景」** Apple M 系列芯片是苹果公司为其 Mac 电脑和 iPad 设备设计的基于 ARM 架构的片上系统 \(SoC\)。它们整合了中央处理器 \(CPU\)、图形处理器 \(GPU\)、神经网络引擎和其他组件，旨在提供高性能和高能效。

**「影响」** 这些新芯片的推出将直接提升软件开发和 AI/机器学习任务的执行效率，为相关专业人士提供更强大的计算平台。

**「社区讨论」** 社区讨论显示，用户对 M 系列芯片的性能印象深刻，但对内存升级的高昂定价表示担忧，例如 Mac Studio M5 Pro 从 36GB 升级到 256GB 内存价格大幅上涨。尽管如此，也有观点认为，考虑到通货膨胀调整后，新 Mac 的价值与历史产品相比仍令人难以置信。

**标签**: `#Hardware`, `#Processors`, `#Apple Silicon`, `#Artificial Intelligence`, `#Performance`

---

<a id="item-tech-news-6"></a>
### [Apple 发布搭载 M5 Max 和 M5 Ultra 芯片的新款 Mac Studio](https://www.apple.com/newsroom/2026/08/apple-introduces-new-mac-studio-with-m5-max-and-m5-ultra/) ⭐️ 8.0/10

Apple 于 2026 年 8 月发布了新款 Mac Studio，搭载 M5 Max 和 M5 Ultra 芯片，旨在显著提升本地 AI 工作负载的处理能力。此次更新对软件工程师和 AI 从业者具有重要意义，因其明确将“本地 AI”作为核心卖点，并有望推动 AI/ML 模型在硬件上的应用。新机型配备了 Thunderbolt 5 接口，提供 120Gb/s 的外部 IO 带宽，并宣称内部内存带宽最高可达 1.2TB/s。

hackernews · interpol\_p · 8月25日 13:03 · [社区讨论](https://news.ycombinator.com/item?id=49433316)

**「背景」** Mac Studio 是 Apple 推出的一款面向专业用户的桌面电脑，以其高性能和紧凑设计而闻名。它搭载 Apple 自研的 M 系列芯片，这些芯片集成了中央处理器 \(CPU\)、图形处理器 \(GPU\) 和神经网络引擎，旨在为各种计算密集型任务（包括人工智能工作负载）提供强大支持。此次发布的 M5 Max 和 M5 Ultra 芯片是该系列的最新版本，进一步提升了 Mac Studio 在 AI 性能和图形处理方面的能力。

**「影响」** 新款 Mac Studio 的推出，通过其 M5 Max 和 M5 Ultra 芯片，显著提升了本地 AI 工作负载的性能上限，这对于需要处理复杂 AI 模型的开发者和研究人员而言，提供了更强大的计算平台。然而，高昂的定价和对超大型参数模型（如大于 1T 参数）的潜在限制，可能会影响其在特定高端应用场景中的普及。

**「社区讨论」** 社区讨论普遍对新款 Mac Studio 的高昂定价表示担忧，例如 256GB 内存可能高达 1 万美元，并有用户抱怨新闻稿中频繁使用“高达”一词。尽管如此，用户普遍对 Apple 将“本地 AI”作为重点用例表示赞赏，认为这预示着未来的发展方向，但也有人指出其内存带宽可能不足以“面向未来”处理超过 1 万亿参数的模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.apple.com/newsroom/2026/08/apple-introduces-new-mac-studio-with-m5-max-and-m5-ultra/">Apple introduces new Mac Studio with M 5 Max and M 5 Ultra - Apple</a></li>
<li><a href="https://www.youtube.com/watch?v=3uAIqqg8ZHo">The New Mac Studio with M 5 Max and M 5 Ultra - YouTube</a></li>

</ul>
</details>

**标签**: `#Hardware`, `#Artificial Intelligence`, `#Machine Learning`, `#Computer Systems`, `#Apple Silicon`

---

<a id="item-tech-news-7"></a>
### [Apple 发布搭载 M6 和 M5 Pro 芯片的新款 Mac mini](https://www.apple.com/newsroom/2026/08/apple-unveils-a-more-powerful-mac-mini-featuring-the-all-new-m6-and-m5-pro/) ⭐️ 8.0/10

Apple 宣布推出搭载全新 M6 和 M5 Pro 芯片的 Mac mini 机型，为软件工程、人工智能及相关领域的专业人士带来了显著的性能提升。此次更新旨在满足对更高计算能力的需求，进一步巩固 Mac mini 在专业工作站领域的地位。

hackernews · runako · 8月25日 13:13 · [社区讨论](https://news.ycombinator.com/item?id=49433450)

**「背景」** Mac mini 是 Apple 推出的一款紧凑型桌面电脑，以其小巧的体积和强大的性能而闻名。Apple 的 M 系列芯片（如 M6 和 M5 Pro）采用统一内存架构，旨在为各种计算任务提供高效能。最近，Apple 通过 Thunderbolt 5 和 MLX 框架，使 Mac mini 能够支持分布式 AI 推理，允许用户将多台设备串联起来运行大型语言模型，从而为本地 AI 开发提供了一种替代传统专业 GPU 硬件的方案。

**「影响」** 搭载 M6 和 M5 Pro 芯片的新款 Mac mini，包括苹果首款 2 纳米 M6 芯片，为软件工程和 AI 领域的专业人士带来了显著的性能提升，尤其是在 AI 任务方面，尽管价格有所上涨。

**「社区讨论」** 社区用户对新款 Mac mini 的价格上涨表示关注，尤其是在欧洲市场，认为其不再像以往那样“超值”。有用户对苹果发布产品后需等待才能订购的策略表示不满，并质疑基准测试中 M6 与 M1 的对比实用性，同时也有用户对“始终在线的代理计算”这一宣传语感到不安。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/apple/2026/08/with-new-mac-studio-and-mac-mini-apple-leans-hard-into-local-ai-inference/">Apple&#x27;s new desktop computers are designed specifically for local AI development - Ars Technica</a></li>
<li><a href="https://macdailynews.com/2026/08/25/apples-new-mac-mini-and-mac-studio-are-designed-specifically-for-local-ai-development/">Apple&#x27;s new Mac mini and Mac Studio are designed specifically for local AI development - MacDailyNews</a></li>
<li><a href="https://www.forbes.com/sites/davidphelan/2026/08/25/apple-surprise-launches-new-mac-mini-mac-studio-m6-and-m5-ultra-chips-unexpectedly/">Apple Launches New Mac mini, Mac Studio, M6 And M5 Ultra ...</a></li>
<li><a href="https://9to5mac.com/2026/08/25/m6-mac-mini-vs-m4-mac-mini-here-are-all-the-new-features/">M6 Mac mini vs M4 Mac mini: Here are all the new features</a></li>
<li><a href="https://www.techradar.com/computing/macs/apples-new-mac-mini-looks-the-same-but-the-m6-inside-brings-a-major-performance-boost">Apple’s new Mac mini looks the same, but the M6 ... - TechRadar</a></li>

</ul>
</details>

**标签**: `#Hardware`, `#Apple Silicon`, `#Software Development`, `#Artificial Intelligence`, `#Computer Systems`

---

<a id="item-tech-news-8"></a>
### [Nitter 项目收到停止并终止函](https://github.com/zedeus/nitter/issues/1442) ⭐️ 8.0/10

Nitter 项目，一个专注于隐私的 X 平台开源前端，已收到停止并终止函。此举引发了关于平台控制、数据访问以及替代技术解决方案所面临法律挑战的广泛讨论。目前，该项目正在等待法律建议，并预计所有 Nitter 实例在可预见的未来将保持关闭状态。这一事件凸显了与主要平台交互的开源项目所面临的重大法律困境，并对数据访问和平台控制提出了重要问题。

hackernews · Banditoz · 8月25日 17:08 · [社区讨论](https://news.ycombinator.com/item?id=49437283)

**「背景」** Nitter 是一个开源的、注重隐私的 X（前身为 Twitter）前端项目，允许用户在不直接访问 X 平台的情况下浏览内容，从而避免跟踪和广告。X Corp 于 2026 年 8 月 24 日向 Nitter 发送了停止并终止函，要求永久关闭 Nitter 实例及其项目代码库，理由是涉嫌抓取数据。此举导致 Nitter.net 下线，项目开发也已停止。

**「社区讨论」** 社区讨论主要围绕对 Nitter 项目的担忧及其对开源和隐私领域的影响，有评论呼吁中等强国应提供法律保护以支持此类项目，并探讨了在其他司法管辖区托管 Nitter 实例以规避停止并终止函的可能性。此外，一些用户表达了对 X 平台作为官方沟通渠道的依赖，并担心 Nitter 的关闭将影响他们获取重要信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nitter">Nitter - Wikipedia</a></li>
<li><a href="https://techcrunch.com/2026/08/25/x-sends-cease-and-desist-to-open-source-project-nitter-over-alleged-scraping/">X sends cease-and-desist to open-source project Nitter over ...</a></li>
<li><a href="https://onejailbreak.com/blog/nitter-hit-by-x-lawsuit/">X Corp Cease and Desist Kills Nitter Project - ONE Jailbreak</a></li>

</ul>
</details>

**标签**: `#Open Source`, `#Privacy`, `#Legal Tech`, `#Platform Control`, `#Web Scraping`

---

<a id="item-tech-news-9"></a>
### [Firefox 157 将默认在所有平台上支持 JPEG XL](https://groups.google.com/a/mozilla.org/g/dev-platform/c/3YMV4MS34KA?pli=1) ⭐️ 8.0/10

Firefox 157 版本将默认在所有平台上集成 JPEG XL 图像格式，此举与 Chrome 浏览器的做法保持一致，标志着网络图像格式采纳的一个重要转变。JPEG XL 是一种现代图像格式，其广泛采用有望显著提升网络内容的性能和效率。这一默认集成将为网络开发者和用户带来更优化的图像处理体验，推动更高效的网络内容交付。

hackernews · yboris · 8月25日 17:55 · [社区讨论](https://news.ycombinator.com/item?id=49437946)

**「背景」** JPEG XL（通常缩写为 JXL）是一种由联合图像专家组（JPEG）、Google 和 Cloudinary 共同开发的图像格式，支持有损和无损压缩。它旨在提供比现有格式更好的压缩效率和功能，包括无损地将旧版 JPEG 文件转换为 JXL 的能力，同时保持图像质量。

**「影响」** 随着 Firefox 和 Chrome 浏览器默认支持 JPEG XL，网络内容创作者和用户将受益于更高效的图像处理和更快的网页加载速度，从而提升整体网络体验。

**「社区讨论」** 社区讨论关注 Firefox 和 Chromium 都采用基于 Rust 的 \`jxl-rs\` 实现，并对 Apple 已在其平台中使用的 C++ \`libjxl\` 的未来策略以及两种库的性能对比表示好奇。此外，有用户希望浏览器能提供更便捷的方式来处理网站或上传字段不支持 JPEG XL 的情况，例如自动转换或提供转换选项。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/JPEG_XL">JPEG XL - Wikipedia</a></li>
<li><a href="https://www.jnrt.online/en/blog/geschichte-jpeg-xl">The History of JPEG XL — From Cloudinary and Google to the ...</a></li>

</ul>
</details>

**标签**: `#Web Development`, `#Browser Technology`, `#Image Formats`, `#Open Source`, `#Computer Systems`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美国制裁威胁下中国加速金融系统多元化](https://www.cnbc.com/2026/08/25/china-iran-us-sanctions-banks-cips.html) ⭐️ 9.0/10

美国威胁将协助伊朗规避制裁的中国银行排除在美国金融系统之外，促使中国加速其跨境银行间支付系统（CIPS）建设并扩大双边货币互换，以对冲美元主导地位。

rss · CNBC Finance · 8月25日 16:00

**「背景」** 此举源于美国财政部指控部分中国实体协助伊朗进行洗钱或规避制裁，而中国曾是伊朗原油的最大买家。

**「影响」** 这一政策变化可能促使全球金融体系加速多元化，并影响中美关系以及国际货币体系的未来。

**标签**: `#U.S.-China Relations`, `#Financial Sanctions`, `#Global Currencies`, `#China&\#x27;s Financial System`

---