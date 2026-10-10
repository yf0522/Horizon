---
layout: default
title: "Horizon Summary: 2026-10-10 (ZH)"
date: 2026-10-10
lang: zh
---

> 从 42 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [Cloudflare 收购 Deno，一年后停止活跃开发](#item-tech-news-1) ⭐️ 9.0/10
2. [Telegram Desktop 曝一键窃取任意文件漏洞](#item-tech-news-2) ⭐️ 9.0/10
3. [Carrier-Explode：解码主流手机运营商设置，揭示网络控制细节](#item-tech-news-3) ⭐️ 8.0/10
4. [Matthew Green 警告 AI 可能动摇公钥加密信心](#item-tech-news-4) ⭐️ 8.0/10
5. [Talus：23M 参数扩散模型，用于游戏地形生成，WebGPU 浏览器运行](#item-tech-news-5) ⭐️ 8.0/10
6. [亚马逊完成第 1000 颗 Kuiper 卫星制造，太空互联网服务将上线](#item-tech-news-6) ⭐️ 8.0/10
7. [JetBrains 发布开源编程模型 Mellum2.1，赋能本地编码代理](#item-tech-news-7) ⭐️ 8.0/10

**财经新闻**
1. [电信竞争加剧、医疗保险评级变动及主要公司业绩](#item-finance-news-1) ⭐️ 8.0/10
2. [苹果削减 iPhone 订单，达美航空盈利不及预期](#item-finance-news-2) ⭐️ 8.0/10
3. [纳斯达克首席执行官称代币化可释放数百亿美元资金](#item-finance-news-3) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Cloudflare 收购 Deno，一年后停止活跃开发](https://deno.com/blog/cloudflare) ⭐️ 9.0/10

Cloudflare 已收购 Deno，并计划在提供一年的维护（包括错误修复和安全更新）后，停止对 Deno 运行时的活跃开发。此举意味着 Deno 项目的主要创新和支持将告一段落，对 JavaScript/TypeScript 生态系统及开源社区产生重大影响。尽管 Deno 将保持开源，但其未来发展将取决于社区是否接手。

hackernews · ilreb · 10月9日 13:03 · [社区讨论](https://news.ycombinator.com/item?id=50019911)

**「背景」** Deno 是一个由 Node.js 创建者开发的 JavaScript/TypeScript 运行时，旨在提供更安全、更现代的开发环境，并改进了模块系统，被视为 Node.js 的替代方案。

**「影响」** 对于依赖 Deno 运行时的开发者和项目而言，此举意味着该平台未来的创新和官方支持将面临不确定性，除非有其他实体或社区接手其持续开发。

**「社区讨论」** 社区普遍对 Deno 项目的未来表示失望和悲伤，许多用户认为此结局是可预见的，尤其是在 Deno 转向优先支持 npm 兼容性之后。评论者担心 Deno 将失去其创新动力，并将其描述为一次“收购式解散”，同时也有人希望 Cloudflare 的 Workerd 运行时能借鉴 Deno 的安全机制。

**标签**: `#Software Engineering`, `#JavaScript Runtimes`, `#Open Source`, `#Cloudflare`, `#Tech Industry`

---

<a id="item-tech-news-2"></a>
### [Telegram Desktop 曝一键窃取任意文件漏洞](https://telegram.me/zaihuapd/44307) ⭐️ 9.0/10

Telegram Desktop 7.2.9 以下版本被发现存在一个严重漏洞（CVE-2026-107181），允许攻击者通过恶意 \`tg://\` 链接实现一键式任意文件窃取。该漏洞源于链接中的分号未被转义，被错误地解析为独立的进程间通信（IPC）命令，从而配合 \`interpret:\` 处理器可悄悄窃取包括文档、浏览器会话、SSH 密钥和加密钱包等敏感文件。官方已在 7.2.9 版本中修复此问题，强烈建议用户尽快升级至最新版本，同时警惕异常的 \`tg://\` 链接并启用本地密码以增强安全性。

telegram · zaihuapd · 10月9日 09:51

**「背景」** tg:// 链接是一种自定义 URL 方案，允许外部应用或网页与 Telegram Desktop 客户端进行交互。此漏洞利用了进程间通信（IPC）机制中的一个缺陷，IPC 允许不同程序之间交换数据和指令。当链接中的分号未被正确转义时，它们会被错误地解析为独立的 IPC 命令，从而导致命令注入。

**「影响」** 此漏洞允许攻击者在用户不知情的情况下静默窃取高度敏感的用户数据，对受影响用户的个人数据安全构成重大风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://securityvulnerability.io/vulnerability/CVE-2026-107181">CVE - 2026 - 107181 : IPC Record-Separation Injection Vulnerability in...</a></li>
<li><a href="https://www.rapid7.com/db/vulnerabilities/cve-2026-107181/">CVE - 2026 - 107181 : Telegram ... | Rapid7 Vulnerability Database</a></li>

</ul>
</details>

**标签**: `#Cybersecurity`, `#Software Vulnerability`, `#Instant Messaging`, `#Data Security`, `#Computer Systems`

---

<a id="item-tech-news-3"></a>
### [Carrier-Explode：解码主流手机运营商设置，揭示网络控制细节](https://carrierexplode.com/) ⭐️ 8.0/10

Carrier-Explode 是一个持续归档并解码主流手机品牌（如 iPhone、Pixel 和 Galaxy）运营商设置的开源项目。它提供了常见基带配置的解码器和解释，揭示了网络运营商如何配置和控制移动设备功能。该工具已被证明对爱好者群体有用，能帮助理解网络锁定和功能禁用等实际问题，尽管其假设仍需进一步验证。通过揭示这些通常不透明的设置，Carrier-Explode 为理解移动网络行为提供了关键洞察。

hackernews · simplyalec · 10月9日 18:10 · [社区讨论](https://news.ycombinator.com/item?id=50024499)

**「背景」** 运营商设置是移动网络运营商通过配置文件对手机进行配置，以控制其网络连接、功能（如 5G、个人热点）和行为的一组参数。这些设置通常不透明，对用户而言难以访问和理解，但它们决定了设备在特定网络下的运行方式。

**「影响」** 该项目为用户和开发者提供了前所未有的透明度，使其能够深入了解运营商如何通过配置控制设备功能，例如在 AT&amp;T iPhone 18 Pro Max 锁定事件中禁用 5G 独立模式，或阻止个人热点功能。

**「社区讨论」** 社区讨论强调了该工具在解决实际问题中的价值，例如在 AT&amp;T iPhone 18 Pro Max 锁定事件中，它揭示了运营商为应对问题而禁用 5G 独立模式的尝试。用户还表达了对运营商禁用个人热点等“反用户”功能的担忧，并赞赏该项目提供了全球运营商的设置信息。

**标签**: `#Mobile Technology`, `#Reverse Engineering`, `#Computer Systems`, `#Networking`, `#Telecommunications`

---

<a id="item-tech-news-4"></a>
### [Matthew Green 警告 AI 可能动摇公钥加密信心](https://simonwillison.net/2026/Oct/9/matthew-green/) ⭐️ 8.0/10

著名密码学家 Matthew Green 警告称，人工智能（AI）有潜力迅速削弱人们对现有公钥加密算法的信心。他估计，我们有 15% 的可能性在功能上失去对当前公钥加密算法的信任，甚至有 1% 的可能性生活在 Russell Impagliazzo 提出的“Minicrypt”世界中，即公钥加密根本不可能实现。Green 强调，AI 产生意外的速度与人类更新安全标准的速度之间存在数量级的差异，这种速度不匹配是核心问题，并指出只有提前做好准备才能从这种意外中恢复。

rss · Simon Willison · 10月9日 15:02

**「背景」** 公钥加密是一种基础的密码学方法，广泛用于确保互联网上的安全通信，它依赖于一对密钥（公钥和私钥）进行加密和解密。Matthew Green 提到的“Minicrypt”是理论计算机科学家 Russell Impagliazzo 设想的一种计算宇宙，在该宇宙中，基于数学难题的公钥加密被认为是不可行的。

**「影响」** Matthew Green 的警告直接指向了未来网络安全领域的一个重大风险，即当前广泛依赖的公钥加密技术可能因 AI 的快速发展而面临信任危机，从而对全球数字通信和数据安全造成深远影响。

**标签**: `#Cryptography`, `#Artificial Intelligence`, `#Cybersecurity`, `#Computer Systems`, `#Future of Tech`

---

<a id="item-tech-news-5"></a>
### [Talus：23M 参数扩散模型，用于游戏地形生成，WebGPU 浏览器运行](https://www.reddit.com/r/MachineLearning/comments/1x1v71p/talus_a_23mparameter_diffusion_model_for_game/) ⭐️ 8.0/10

Talus 是一个 2300 万参数的扩散模型，专为生成游戏地形高度图而设计，能够生成 64x64 的高度图（覆盖 4 公里，海拔高达 1200 米）。该模型可在 WebGPU 支持的浏览器中运行，通过 ONNX 导出和 ONNX Runtime Web 实现，在 RTX 5060 上每张图生成约 3 秒。它支持基于地形类型和五种属性（平均海拔、起伏、平均坡度、水体比例和光谱坡度）进行详细条件控制，并在单个 RTX 5060 显卡上仅用约 4.5 小时完成训练。尽管在真实地图对比评估中，其 W1 度量为基准的 1.51 倍，光谱为 9.1 倍，坡度为 1.65 倍，但仍存在山脉过于平滑和平原过于粗糙等开放问题。

reddit · r/MachineLearning · /u/Old\_Cow\_6636 · 10月9日 19:52

**「背景信息」** 扩散模型是一种先进的生成式人工智能，能够通过学习数据分布来生成高度逼真的图像、音频或其他数据。WebGPU 是一个新兴的 Web 标准，旨在为 Web 开发者提供一个现代化的低级 API，以便在浏览器中直接利用底层系统的 GPU 进行高性能计算和图形渲染。ONNX Runtime Web 是一个用于在 Web 浏览器中运行 ONNX 格式机器学习模型的工具，它能够利用 WebGPU 的强大功能，实现客户端侧的 GPU 加速推理，从而提升 AI 应用的性能和效率。

**「影响」** Talus 模型在 Web 浏览器中通过 WebGPU 提供高效的游戏地形高度图生成能力，为游戏开发者和研究人员提供了一个易于访问且功能强大的 AI 工具，有望简化游戏开发流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://onnxruntime.ai/docs/tutorials/web/ep-webgpu.html">Using WebGPU | onnxruntime</a></li>
<li><a href="https://edgeruntimehq.pages.dev/">Edge AI Inference Leaderboard: WebGPU &amp; ONNX Runtime</a></li>
<li><a href="https://opensource.microsoft.com/blog/2024/02/29/onnx-runtime-web-unleashes-generative-ai-in-the-browser-using-webgpu/">ONNX Runtime Web unleashes generative AI in the browser using...</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Diffusion Models`, `#Game Development`, `#WebGPU`, `#AI Applications`

---

<a id="item-tech-news-6"></a>
### [亚马逊完成第 1000 颗 Kuiper 卫星制造，太空互联网服务将上线](https://arstechnica.com/space/2026/10/amazon-builds-1000th-satellite-is-weeks-away-from-space-internet-rollout/) ⭐️ 8.0/10

亚马逊近期在其位于华盛顿州柯克兰的工厂成功制造出第 1000 颗用于 Project Kuiper（又称 Amazon Leo）低轨卫星互联网项目的卫星。这一里程碑事件标志着亚马逊距离在年底前推出其商业太空互联网服务仅数周之遥。这些卫星将搭乘 Vulcan 火箭执行即将到来的复飞任务，并且另一枚 Vulcan 火箭也计划在 2026 年发射更多卫星，以进一步扩展其全球连接基础设施。

telegram · zaihuapd · 10月9日 04:30

**「背景」** 亚马逊的“柯伊伯计划”（Project Kuiper，也称 Amazon Leo）是一项旨在通过部署 3,236 颗低地球轨道（LEO）卫星，为全球未服务及服务不足地区提供宽带互联网连接的倡议。该计划于 2019 年公布，其卫星将由包括联合发射联盟（ULA）的“火神半人马座”（Vulcan Centaur）在内的火箭发射升空。

**「影响」** 亚马逊的 Kuiper 项目建成第 1000 颗卫星并即将推出商业服务，这加剧了低地球轨道卫星互联网市场的竞争，特别是与 Starlink 的竞争，可能加速全球连接解决方案的普及。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aboutamazon.com/what-we-do/devices-services/amazon-leo">Amazon Leo</a></li>
<li><a href="https://keeptrack.space/deep-dive/amazon-vs-spacex">Amazon vs SpaceX: The Battle for the Best Satellite... - KeepTrack</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_Vulcan_launches">List of Vulcan launches - Wikipedia</a></li>
<li><a href="https://synergia.themarzipan.com/race-global-connectivity/">The Race for Global Connectivity – synergia Blog</a></li>
<li><a href="https://vocal.media/01/amazon-s-project-kuiper-your-complete-guide-to-the-future-of-satellite-internet">&quot;Amazon&#x27;s Project Kuiper : Your Complete Guide to the Future of...&quot;...</a></li>

</ul>
</details>

**标签**: `#Satellite Internet`, `#Space Technology`, `#Amazon`, `#Computer Systems`, `#Telecommunications`

---

<a id="item-tech-news-7"></a>
### [JetBrains 发布开源编程模型 Mellum2.1，赋能本地编码代理](https://blog.jetbrains.com/ai/2026/10/mellum2-1-gets-to-work-a-fast-open-model-for-coding-agents/) ⭐️ 8.0/10

JetBrains 已发布开源编程模型 Mellum2.1，该模型采用 12B 参数的混合专家 \(Mixture-of-Experts\) 架构，其中激活参数为 2.5B。Mellum2.1 经过真实环境的强化学习训练，旨在支持本地运行的编程代理，使其能够探索代码库、编辑文件并检查修改。该模型遵循 Apache 2.0 许可，其权重已在 Hugging Face 上提供。

telegram · zaihuapd · 10月9日 07:30

**「背景」** 编程模型是为特定任务设计的机器学习模型，而混合专家 \(Mixture-of-Experts, MoE\) 架构是一种神经网络设计，它通过激活模型中特定部分的“专家”网络来处理不同的输入，从而在保持高参数量的同时提高计算效率。JetBrains 作为知名的开发者工具公司，此次发布旨在为软件开发自动化提供一个强大的开源基础。

**「影响」** Mellum2.1 的发布为开发者和组织提供了一个高性能、开源且可在本地运行的工具，以自动化代码探索、编辑和审查等任务，从而可能提高软件开发效率。

**标签**: `#Artificial Intelligence`, `#Software Engineering`, `#Open Source`, `#Machine Learning`, `#Coding Agents`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [电信竞争加剧、医疗保险评级变动及主要公司业绩](https://www.cnbc.com/2026/10/09/stocks-making-the-biggest-moves-midday-tmus-vz-t-cci-teva.html) ⭐️ 8.0/10

SpaceX 增强了其 Starlink 移动服务，加剧了对传统电信运营商的竞争担忧，导致 T-Mobile 股价下跌 13%，AT&amp;T 和 Verizon 股价各下跌 10%。同时，医疗保险和医疗补助服务中心（CMS）公布了 2027 年星级评定，Humana 股价飙升 12%，而 Alignment Healthcare 股价下跌近 14%。苹果公司股价下跌近 2%，此前《日经亚洲》报道称其因需求低于预期而削减了 iPhone 18 Pro 的生产订单。

rss · CNBC Finance · 10月9日 18:57

**「背景」** SpaceX 的 Starlink Mobile 服务通过卫星提供移动连接，对现有电信市场构成新的竞争。CMS 星级评定是美国联邦政府对医疗保险计划质量的评估，直接影响保险公司的市场份额和盈利能力。

**「影响」** 电信行业的竞争加剧导致传统运营商股价下跌，而为移动网络提供基础设施的蜂窝塔公司股价上涨。医疗保险星级评定的变化直接影响了相关保险公司的市场估值和未来业务前景。

**标签**: `#Telecommunications`, `#Healthcare`, `#Technology`, `#Corporate Earnings`, `#Market Analysis`

---

<a id="item-finance-news-2"></a>
### [苹果削减 iPhone 订单，达美航空盈利不及预期](https://www.cnbc.com/2026/10/09/stocks-making-the-biggest-moves-premarket-dal-spcx-tmus.html) ⭐️ 8.0/10

据日经亚洲报道，由于需求弱于预期，苹果公司将 10 月份 iPhone 18 Pro 和 Pro Max 的零部件订单从原计划削减了 15%。达美航空公布第三季度调整后每股收益为 1.72 美元，低于分析师预期的 1.75 美元，并下调了全年盈利展望。

rss · CNBC Finance · 10月9日 12:31

**「背景」** 苹果公司上月发布的 iPhone 18 Pro 起售价为 1199 美元，较上代上涨 100 美元；达美航空表示，燃油成本上涨持续对其业绩展望造成压力。

**「影响」** SpaceX 的频谱交易可能加剧竞争，导致 T-Mobile、AT&amp;T 和 Verizon 等电信公司股价下跌，而美国医保和医疗补助服务中心（CMS）的星级评定直接影响了 Humana 和 Alignment Healthcare 等管理式医疗服务提供商的股价，同时苹果公司因需求疲软削减 iPhone 18 Pro 订单，影响了其股价及其供应商。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qz.com/spacex-starlink-mobile-spectrum-grain-management-telecom-stocks-100926">SpaceX Starlink Mobile spectrum deal hits telecom stocks</a></li>
<li><a href="https://arstechnica.com/tech-policy/2026/10/starlink-spectrum-deal-boosts-musk-plan-to-beat-att-t-mobile-and-verizon/">Starlink spectrum deal boosts Musk plan to beat AT&amp;T, T- Mobile ...</a></li>
<li><a href="https://www.androidauthority.com/spacex-starlink-mobile-8-billion-spectrum-deal-3721430/">SpaceX &#x27;s $8 billion spectrum deal takes aim at US carriers</a></li>
<li><a href="https://finance.yahoo.com/healthcare/articles/humana-soars-alignment-plummets-2027-130519409.html">Humana soars, Alignment plummets in 2027 Medicare Advantage...</a></li>
<li><a href="https://www.tradingview.com/news/stocktwits:789660826094b:0-hum-stock-soars-alhc-sinks-as-cms-star-ratings-redraw-2028-bonuses/">HUM Stock Soars, ALHC Sinks As CMS Star Ratings Redraw 2028...</a></li>
<li><a href="https://www.tikr.com/blog/alignment-healthcare-sinks-20-as-medicare-plan-downgraded-humana-and-clover-soar">Alignment Healthcare Sinks 20% as Medicare Plan... | TIKR.com</a></li>
<li><a href="https://money.usnews.com/investing/news/articles/2026-10-09/apple-cuts-iphone-18-pro-orders-due-to-soft-demand-nikkei-asia-reports">Apple Cuts IPhone 18 Pro Orders Due to Soft Demand , Nikkei Asia...</a></li>
<li><a href="https://www.nampa.org/text/23035416">Apple Cuts Component Orders for iPhone 18 Pro , Pro Max Due to ...</a></li>
<li><a href="https://www.macrumors.com/2026/10/09/apple-cuts-iphone-18-pro-orders-price-demand/">Apple Reportedly Cuts iPhone 18 Pro Orders After... - MacRumors</a></li>

</ul>
</details>

**标签**: `#Telecommunications`, `#Airline Industry`, `#Healthcare Sector`, `#Technology Stocks`, `#Corporate Earnings`

---

<a id="item-finance-news-3"></a>
### [纳斯达克首席执行官称代币化可释放数百亿美元资金](https://www.cnbc.com/2026/10/09/nasdaq-ceo-tokenization-could-unleash-billions-in-trapped-capital-.html) ⭐️ 8.0/10

纳斯达克首席执行官阿德娜·弗里德曼表示，资产代币化有望在全球金融系统中释放数百亿美元被困资本，并促进全天候交易。

rss · CNBC Finance · 10月9日 06:30

**「背景」** 代币化是将股票和债券等金融资产表示为可使用区块链技术转移的数字代币，这可以使抵押品更具流动性。

**「影响」** 这一转变可能使全球金融市场的基础设施发生重大变革，为机构和散户投资者提供更强的流动性和更广泛的资本市场准入。

**标签**: `#Tokenization`, `#Capital Markets`, `#Financial Technology`, `#Blockchain`, `#AI in Finance`

---