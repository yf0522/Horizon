---
layout: default
title: "Horizon Summary: 2026-08-05 (ZH)"
date: 2026-08-05
lang: zh
---

> 从 46 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [Keyv 及其相关 npm 包遭遇“Shai-Hulud”供应链攻击，凭证被盗](#item-tech-news-1) ⭐️ 9.0/10
2. [我国首部 L3/L4 自动驾驶强制性国标发布](#item-tech-news-2) ⭐️ 9.0/10
3. [白宫开源 AI 监管急转弯，硅谷就中国模型限制分歧加剧](#item-tech-news-3) ⭐️ 9.0/10
4. [Mistral 发布 Shieldstral：3B 多模态开源模型，用于内容审核](#item-tech-news-4) ⭐️ 8.0/10
5. [DeepSeek V4 Flash 在单颗 AMD MI300X 上运行](#item-tech-news-5) ⭐️ 8.0/10
6. [官方通信与网络钓鱼混淆：用户安全面临挑战](#item-tech-news-6) ⭐️ 8.0/10
7. [Oxide Computer 获得 4.45 亿美元 D 轮融资](#item-tech-news-7) ⭐️ 8.0/10
8. [Xbox 服务中断导致光盘游戏无法运行，凸显数字版权管理问题](#item-tech-news-8) ⭐️ 8.0/10
9. [MiniMax-H3 全模态生成系统现已移植至 MLX，可在 Apple Silicon 上运行](#item-tech-news-9) ⭐️ 8.0/10

**财经新闻**
1. [谷歌为 Anthropic 搭建 2000 亿美元融资架构](#item-finance-news-1) ⭐️ 9.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Keyv 及其相关 npm 包遭遇“Shai-Hulud”供应链攻击，凭证被盗](https://www.aikido.dev/blog/keyv-and-friends-compromised-in-npm-supply-chain-attack) ⭐️ 9.0/10

活跃的“Shai-Hulud”供应链攻击已成功入侵 Keyv 及其相关 npm 包，利用恶意预安装脚本窃取开发者凭证。此次攻击对开发者构成重大安全风险，并揭示了依赖管理中存在的根本性漏洞。鉴于其广泛影响和凭证窃取的性质，该事件凸显了软件工程生态系统面临的严峻安全挑战，需要立即关注和采取缓解措施。

hackernews · cimi\_ · 8月4日 11:01 · [社区讨论](https://news.ycombinator.com/item?id=49166874)

**「背景信息」** 软件供应链攻击是指针对软件开发过程或第三方库等组件的攻击，旨在向用户分发恶意软件。npm 是 JavaScript 的包管理器，开发者经常将大量外部包作为依赖项引入项目，这些包可以包含自动执行的预安装脚本。在此次攻击中，恶意版本通过 GitHub Actions 以有效的来源证明发布，使其看起来是合法的。

**「影响」** 此次 Shai-Hulud 供应链攻击已通过 Keyv 和 cacheable 等 npm 包传播了窃取凭证的蠕虫，影响了超过 400 个不同的 npm 包（具体为 428 个包的 1700 多个版本），对这些受影响包的开发者和用户造成了凭证被盗的重大风险。

**「社区讨论」** 社区讨论中，有开发者分享了用于检测此类供应链攻击的开源工具 Packj，该工具通过静态和动态分析来识别妥协指标。另有评论建议开发者应普遍采用开发容器（devcontainers）以增强保护，并呼吁对 npm 包的预安装/后安装钩子采取更严格的限制，甚至考虑取消它们。此外，有用户对当前依赖系统的脆弱性表示担忧，并质疑 GitHub 为何不能检测并阻止此类攻击中用于数据外泄的仓库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aikido.dev/blog/keyv-and-friends-compromised-in-npm-supply-chain-attack">Keyv and friends compromised in npm supply chain attack</a></li>
<li><a href="https://www.aikido.dev/blog/keyv-and-friends-compromised-in-npm-supply-chain-attack">Keyv and friends compromised in npm supply chain attack</a></li>
<li><a href="https://www.wiz.io/blog/keyv-and-cacheable-npm-supply-chain-attack">keyv and cacheable npm Package Hijacked in Supply Chain Attack | Wiz Blog</a></li>
<li><a href="https://research.jfrog.com/post/shai-hulud-is-back-august/">Major Shai Hulud campaign strikes npm again, affecting keyv and 400+ packages - JFrog Security Research</a></li>

</ul>
</details>

**标签**: `#Software Engineering`, `#Cybersecurity`, `#Supply Chain Attack`, `#npm`, `#Open Source`

---

<a id="item-tech-news-2"></a>
### [我国首部 L3/L4 自动驾驶强制性国标发布](https://wap.miit.gov.cn/jgsj/zbys/qcgy/art/2026/art_a1d2072374884287b67048a77560014e.html) ⭐️ 9.0/10

中国工业和信息化部组织制定的《智能网联汽车 自动驾驶系统安全要求》（GB 44721—2026）强制性国家标准已正式获批发布，并将于 2027 年 7 月 1 日起实施。这是中国首部针对 L3 级有条件自动驾驶和 L4 级高度自动驾驶系统的强制性国家标准，适用于搭载 L3、L4 级系统的 M 类（载客）和 N 类（载货）车辆，但不包括自动泊车系统。该标准是对 2024 年推荐性国标的系统性升级，从企业全生命周期安全保障、系统动态驾驶能力、人机交互与用户告知、多维度检验检测四个方面构建安全要求体系，旨在确保自动驾驶系统达到合格且专注驾驶人的安全水平。

telegram · zaihuapd · 8月4日 13:06

**「背景」** L3 级自动驾驶，即有条件自动驾驶，指在特定条件下系统可执行全部动态驾驶任务，但驾驶员仍需准备好随时接管。L4 级自动驾驶，即高度自动驾驶，意味着在特定运行设计域内，系统能够完成所有动态驾驶任务，且在系统失效时能执行最小风险操作，无需驾驶员干预。

**「影响」** 该强制性国家标准将要求中国 L3/L4 级自动驾驶系统的开发商和制造商必须遵守严格的安全要求，从而直接影响其车辆的设计、测试和部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://chinaevhome.com/2026/08/04/china-issues-first-mandatory-l3-l4-ad-standard-effective-july-2027/">China Issues First Mandatory L 3 / L 4 AD Standard ... | ChinaEVHome</a></li>
<li><a href="https://rareearthexchanges.com/news/china-releases-mandatory-autonomous-driving-safety-standard-with-july-2027-implementation-deadline/">China Releases Mandatory Autonomous Driving Safety Standard ...</a></li>
<li><a href="https://eu.36kr.com/en/p/3864289821644039">Automakers Banned from Exaggerated Marketing as National ...</a></li>

</ul>
</details>

**标签**: `#Autonomous Driving`, `#AI Regulation`, `#Vehicle Safety Standards`, `#Software Engineering`, `#China Tech Policy`

---

<a id="item-tech-news-3"></a>
### [白宫开源 AI 监管急转弯，硅谷就中国模型限制分歧加剧](https://www.nytimes.com/2026/08/04/technology/ai-washington-regulation-whiplash.html) ⭐️ 9.0/10

白宫在开源人工智能（AI）监管问题上立场出现摇摆，尤其是在如何应对中国开源 AI 模型方面。最初，特朗普政府内部曾考虑对中国 AI 公司实施制裁或贸易限制，但因硅谷的强烈反对，转而将重点放在提升美国自身 AI 竞争力上。8 月 4 日，白宫邀请科技公司讨论新的监管框架，计划在 AI 模型发布前进行网络安全审查，此举的导火索是中国开源模型 Kimi 在性能上已能与 OpenAI 的顶级模型相媲美。硅谷内部对此存在严重分歧，OpenAI 和 Anthropic 以国家安全为由主张限制中国竞争对手，而 Nvidia 和 Meta 等公司则力挺开放生态系统，Nvidia CEO 黄仁勋甚至为此组建了一个拥有 230 多家成员的安全联盟。

telegram · zaihuapd · 8月4日 15:22

**「背景」** 开源 AI 模型是指其源代码、数据和训练方法公开可用的 AI 系统，允许任何人查看、修改和分发。这种开放性促进了快速创新和广泛应用，但也引发了关于国家安全和潜在滥用风险的担忧。美国政府长期以来一直关注中国在关键技术领域的发展，并采取措施限制其获取先进技术。

**「影响」** 此次政策摇摆和潜在的新监管框架，特别是模型发布前的网络安全审查，可能显著影响美国及全球开源 AI 模型的开发、部署和国际合作，尤其对那些依赖开放生态系统进行创新的公司构成新的合规挑战。

**标签**: `#AI Policy`, `#Open Source AI`, `#Industry Regulation`, `#National Security`, `#Tech Industry`

---

<a id="item-tech-news-4"></a>
### [Mistral 发布 Shieldstral：3B 多模态开源模型，用于内容审核](https://mistral.ai/news/shieldstral/) ⭐️ 8.0/10

Mistral 发布了 Shieldstral，这是一个 30 亿参数的开源多模态模型，专门用于内容审核。该模型旨在为平台提供一个潜在的经济高效且可定制的解决方案，以应对内容审核的挑战。作为一款开放权重模型，Shieldstral 允许开发者和平台根据自身需求进行调整和部署，从而降低了对专有解决方案的依赖。此举为需要处理图像和文本等多种内容形式的平台，提供了一个实用的内容安全工具。

hackernews · riadsila · 8月4日 16:36 · [社区讨论](https://news.ycombinator.com/item?id=49171268)

**「背景信息」** 内容审核是监控和过滤用户生成内容以确保其符合平台准则和法律标准的过程，通常涉及处理文本和图像等多种数据类型。多模态模型能够同时处理和理解不同类型的数据，例如文本和图像。开源权重模型则意味着模型的内部参数是公开的，允许开发者自由使用、修改和部署。Mistral 的 Shieldstral 模型将内容审核视为一项策略自适应的问答任务，旨在提供一个可定制且高效的解决方案。

**「影响」** Mistral Shieldstral 的发布为开发者和平台提供了一个潜在的经济高效且可定制的多模态内容审核解决方案，降低了构建需要此类功能的系统的门槛，并为现有专有服务（如 OpenAI 的 Omni Moderation）提供了开源替代方案。

**「社区讨论」** 社区成员对 Shieldstral 的可定制性表示关注，特别是它是否能支持任意规则集而非预设的“大厂”审核风格，以及在不重新训练的情况下模型的可调范围。尽管如此，许多人认为它是一个现实且经济高效的解决方案，可以作为内容分享或社交平台的第一道防线，并有用户将其与 OpenAI 的审核 API 进行比较。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mistral.ai/news/shieldstral/">Introducing Shieldstral. | Mistral AI</a></li>
<li><a href="https://docs.mistral.ai/models/model-cards/shieldstral-1-0">Shieldstral 1.0 - Mistral AI | Mistral Docs</a></li>
<li><a href="https://x.com/MistralAI/status/2084684737554141253">Mistral AI on X: &quot;State-of-the-art on multimodal moderation, Shieldstral boasts industry-leading efficiency, running on a single 16GB NVIDIA GPU and gives enterprises customized control of what’s deemed safe.&quot; / X</a></li>
<li><a href="https://developers.openai.com/api/docs/guides/moderation">Moderation | OpenAI API</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2026/05/openai-omni-moderation/">OpenAI Omni Moderation : How to Filter Text &amp; Images for Free</a></li>
<li><a href="https://medium.com/codetodeploy/openai-omni-moderation-how-to-filter-text-images-for-free-466ea3d0ecd9">OpenAI Omni Moderation : How to Filter Text &amp; Images for... | Medium</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Open Source`, `#Content Moderation`, `#Software Engineering`

---

<a id="item-tech-news-5"></a>
### [DeepSeek V4 Flash 在单颗 AMD MI300X 上运行](https://github.com/ryanzhou/deepseek-v4-flash-mi300x) ⭐️ 8.0/10

该内容详细介绍了 DeepSeek V4 Flash 大型语言模型在单颗 AMD MI300X GPU 上的高效部署。通过保留完整的推理权重，该部署实现了超过 150 tokens/秒的高推理速度，同时将上下文窗口从原始的 1M 缩减至 256k，这被认为是一个实用的权衡。此项工作展示了在特定硬件上优化大型模型性能和内存管理的可行性，对 AI/ML 从业者和硬件优化具有重要意义。

hackernews · zhoutong · 8月4日 10:00 · [社区讨论](https://news.ycombinator.com/item?id=49166386)

**「背景」** DeepSeek V4 Flash 是一种大型语言模型，它是 DeepSeek V4 的低延迟优化变体，采用了稀疏混合专家（MoE）架构，并以其最初的 1M 上下文窗口而闻名。AMD MI300X 是一款专为 AI 工作负载设计的高性能 GPU 加速器，它基于 AMD CDNA™ 3 架构，并配备了高达 192 GB 的 HBM3 内存，使其非常适合内存密集型 AI 应用。

**「影响」** 对于寻求在 AMD MI300X 硬件上加速 AI 推理的 AI/ML 从业者而言，这项工作提供了一个在保持推理质量和高吞吐量的同时，通过实用权衡（如上下文窗口大小）来有效部署 DeepSeek V4 Flash 模型的具体案例。

**「社区讨论」** 社区讨论关注了 AMD MI300X 的可用性（通常作为 OAM 模块以 8 颗为单位出售，成本约 25 万欧元）和替代方案（如 PCIe 接口的 MI350P），并提及了其他可能在更少内存中运行相同模型的项目（如 DwarfStar）。尽管存在硬件获取的挑战，但社区普遍认可该部署在保留推理权重和实现高吞吐量方面的成就，认为上下文窗口的缩减是一个实用的折衷。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepseek.ai/deepseek-v4">DeepSeek V 4 Explained: V 4 -Pro 1.6T vs V 4 - Flash 284B (2026)</a></li>
<li><a href="https://www.amd.com/en/products/accelerators/instinct/mi300/mi300x.html">AMD Instinct™ MI300X Accelerators</a></li>
<li><a href="https://lenovopress.lenovo.com/lp1943-thinksystem-amd-mi300x-192gb-750w-8-gpu-board">ThinkSystem AMD MI300X 192GB 750W 8-GPU Board Product Guide &gt; Lenovo Press</a></li>
<li><a href="https://www.techpowerup.com/gpu-specs/radeon-instinct-mi300x.c4179">AMD Radeon Instinct MI300X Specs | TechPowerUp GPU Database</a></li>

</ul>
</details>

**标签**: `#AI Inference`, `#Large Language Models`, `#AMD MI300X`, `#Hardware Acceleration`, `#Performance Optimization`

---

<a id="item-tech-news-6"></a>
### [官方通信与网络钓鱼混淆：用户安全面临挑战](https://www.troyhunt.com/thanks-fedex-this-is-why-we-keep-getting-phished/) ⭐️ 8.0/10

大型公司（如联邦快递）的官方通信设计不佳且令人困惑，使其与网络钓鱼尝试难以区分，从而加剧了持续的网络安全漏洞。这种现象削弱了用户信任和安全教育的效果，导致用户难以辨别真实信息与诈骗。这一系统性问题对信息安全和用户体验设计产生了重大影响，使得用户更容易受到实际网络钓鱼攻击的侵害。

hackernews · stymaar · 8月4日 21:09 · [社区讨论](https://news.ycombinator.com/item?id=49175192)

**「背景」** 网络钓鱼是一种欺诈行为，攻击者伪装成可信实体，通过电子邮件、短信或网站等方式诱骗用户泄露敏感信息，如用户名、密码和信用卡详细信息。当联邦快递等大型公司的合法通信设计不佳，与网络钓鱼尝试相似时，用户就难以区分真假，从而削弱了他们识别真正威胁的能力，并加剧了网络安全漏洞。

**「影响」** 由于官方通信与诈骗信息外观相似，用户在识别真实信息方面面临巨大挑战，从而增加了他们遭受实际网络钓鱼攻击的风险。

**「社区讨论」** 社区讨论指出，许多用户曾遇到过看似可疑但实为合法的公司通信，例如联邦快递的报关通知或谷歌的存储空间提醒，这些通信因其不规范的格式或模糊的域名而难以验证。此外，IRS 使用与诈骗者相同的文本转语音系统，以及新通用顶级域名（如.xyz）的泛滥，都进一步模糊了合法与非法通信之间的界限，加剧了用户的困惑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.troyhunt.com/thanks-fedex-this-is-why-we-keep-getting-phished/">Troy Hunt : Thanks FedEx , This is Why we Keep Getting Phished</a></li>

</ul>
</details>

**标签**: `#Cybersecurity`, `#Phishing`, `#Information Security`, `#User Experience`, `#Social Engineering`

---

<a id="item-tech-news-7"></a>
### [Oxide Computer 获得 4.45 亿美元 D 轮融资](https://www.sec.gov/Archives/edgar/data/1795071/000179507126000002/xslFormDX01/primary_doc.xml) ⭐️ 8.0/10

Oxide Computer 宣布获得 4.45 亿美元的 D 轮融资，这笔巨额投资表明投资者对其为现代数据中心提供集成硬件和软件解决方案的愿景充满信心。该公司旨在通过其独特的方法革新云计算基础设施和计算机系统，此次融资是其在这一领域持续发展的重要里程碑。

hackernews · depr · 8月4日 20:13 · [社区讨论](https://news.ycombinator.com/item?id=49174407)

**「背景信息」** Oxide Computer Company 致力于为现代数据中心提供集成式硬件和软件解决方案，旨在将公共云的弹性、可编程性和统一控制带到本地基础设施中。该公司通过设计计算、存储、网络和软件的整合平台，提供类似云的按需资源体验，同时保持本地部署的经济性和治理优势。

**「影响」** Oxide Computer 获得 4.45 亿美元 D 轮融资，为其推进数据中心软硬件集成解决方案提供了充足资金，但社区反馈显示，潜在客户对其产品实际上市和客户服务互动仍存疑问。

**「社区讨论」** 社区评论指出，Oxide Computer 在短时间内完成了多轮融资，包括 2023 年的 A 轮 4400 万美元、2025 年的 B 轮 1 亿美元、2026 年的 C 轮 2 亿美元以及同年的 D 轮 4.45 亿美元，显示出其快速的资金增长。然而，有用户反映在销售咨询方面未得到回应，并质疑该公司是否已实际出货硬件产品，尽管也有用户对其产品理念和团队成员表示高度期待和信任。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://oxide.computer/">Oxide Computer Company</a></li>
<li><a href="https://www.inspoweb.com/item/oxide-computer-company">Oxide Computer Company - InspoWeb</a></li>
<li><a href="https://vmblog.com/bylines/oxide-computer-rethinking-data-centers-as-cloud-computers/">Oxide Computer : Rethinking Data Centers as Cloud... - VMblog</a></li>

</ul>
</details>

**标签**: `#Computer Systems`, `#Hardware`, `#Technology Industry`, `#Cloud Infrastructure`, `#Funding`

---

<a id="item-tech-news-8"></a>
### [Xbox 服务中断导致光盘游戏无法运行，凸显数字版权管理问题](https://birchtree.me/blog/xbox-goes-down-you-cant-play-games-you-own-on-disc/) ⭐️ 8.0/10

Xbox 服务中断导致用户无法玩其拥有的光盘游戏，这暴露了数字版权管理（DRM）、系统可靠性以及技术行业中消费者所有权方面的根本性问题。此次事件凸显了主要游戏平台 DRM 系统的关键漏洞，即使是物理介质游戏也可能因在线服务中断而无法访问。这引发了关于数字所有权、系统稳定性及消费者权利的行业讨论，对软件工程和计算机系统设计具有重要影响。

hackernews · surprisetalk · 8月4日 12:01 · [社区讨论](https://news.ycombinator.com/item?id=49167448)

**「背景」** 数字版权管理（DRM）是一种技术，旨在控制数字媒体和硬件的使用、修改和分发。在游戏行业中，即使是光盘版游戏，也可能需要通过在线许可检查来验证用户是否拥有该游戏的合法使用权，以防止盗版并确保符合使用条款。这种机制意味着，即使拥有实体光盘，如果 DRM 服务器出现故障，玩家也可能无法启动游戏。

**「影响」** 此次事件最直接的后果是，即使是合法购买并拥有光盘版 Xbox 游戏的用户，也可能因平台服务中断而无法访问和游玩这些游戏，从而削弱了消费者对“拥有”数字内容的传统理解。

**「社区讨论」** 社区讨论普遍表达了对现代游戏行业趋势的不满，许多用户认为强制在线登录和数字版权管理（DRM）限制了他们对已购买游戏的实际所有权。评论者回忆起 GameCube 和 PS3 等旧世代主机，当时游戏可以离线运行并支持局域网联机，认为那时的所有权和可玩性体验更佳。大家普遍呼吁，无论游戏格式如何，消费者都应享有永久保留、离线使用、设备间转移、备份、转售和传承数字内容的权利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://birchtree.me/blog/xbox-goes-down-you-cant-play-games-you-own-on-disc/">Xbox goes down. You can&#x27;t play games you own on disc.</a></li>
<li><a href="https://www.bbc.com/news/articles/cq5637p7qpno">Xbox tech boss says &#x27;unacceptable&#x27; outage should not have affected disc games</a></li>
<li><a href="https://www.theverge.com/games/972416/xbox-outage-game-disc-entitlement-check-issue">Xbox outage shouldn’t have affected games on disc, Microsoft confirms | The Verge</a></li>

</ul>
</details>

**标签**: `#Digital Rights Management`, `#Computer Systems`, `#Consumer Rights`, `#Online Services`, `#Gaming Industry`

---

<a id="item-tech-news-9"></a>
### [MiniMax-H3 全模态生成系统现已移植至 MLX，可在 Apple Silicon 上运行](https://simonwillison.net/2026/Aug/4/minimax-h3-mlx/#atom-everything) ⭐️ 8.0/10

MiniMaxAI 近期发布的 MiniMax-H3 全模态生成系统，现已通过 \`PipeNetwork/minimax-h3-mlx\` Python 包移植到 MLX 框架，使其能够在 Apple Silicon 设备上运行。该系统被描述为一个通用型全模态生成系统，能够接受文本、图像、音频和视频输入，并生成长达 15 秒的带音频视频片段。作者在 M5 Max MacBook Pro 上成功运行，下载了约 115 GB 的模型文件，视频生成耗时不到 45 分钟。值得注意的是，若未提供明确的音频提示指导，生成的音频质量可能不佳。

rss · Simon Willison · 8月4日 19:10

**「背景」** MiniMax-H3 是由中国上海人工智能公司 MiniMax Group 开发的一种通用、全模态生成系统，能够接受文本、图像、音频和视频输入，并生成最长 15 秒的带音频视频片段。MLX 是由 Apple 机器学习研究团队开发的一个开源数组框架，专为在 Apple Silicon 芯片上高效灵活地进行机器学习而设计，提供类似 NumPy 的 API。

**「影响」** 此移植使得拥有 Apple Silicon 设备的开发者和研究人员能够本地运行 MiniMax-H3 这一强大的全模态生成 AI 系统，从而降低了访问和实验先进生成式 AI 技术的门槛。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MiniMax_Group">MiniMax Group - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/MLX_machine_learning_framework">MLX (machine learning framework)</a></li>
<li><a href="https://mlx-framework.org/">MLX</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Generative AI`, `#Apple Silicon`, `#MLX`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [谷歌为 Anthropic 搭建 2000 亿美元融资架构](https://www.ft.com/content/549f2e23-5aa2-49c7-9ea6-a9784ab7087c) ⭐️ 9.0/10

据《金融时报》报道，谷歌已为人工智能公司 Anthropic 搭建了一个约 2000 亿美元的融资架构，以支持其采购超过 1500 亿美元的 AI 芯片，其中约八成合同与芯片直接相关。

telegram · zaihuapd · 8月4日 10:52

**「背景」** Anthropic 是一家专注于人工智能安全研究的公司，以其大型语言模型 Claude 闻名；博通则是一家半导体公司，为大型人工智能系统提供定制芯片和高速网络解决方案。

**「影响」** 这种创新的厂商融资模式，通过分散风险，减轻了参与的科技公司和金融机构在资产负债表上承担巨额 AI 硬件投资的压力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic - Wikipedia</a></li>
<li><a href="https://www.anthropic.com/company">Company \ Anthropic</a></li>
<li><a href="https://research.contrary.com/company/anthropic">Report: Anthropic Business Breakdown &amp; Founding Story | Contrary Research</a></li>
<li><a href="https://www.appeconomyinsights.com/p/broadcom-ai-at-the-center">Broadcom : AI at the Center - by App Economy Insights</a></li>
<li><a href="https://www.equiti.com/sc-en/news/stock-market/broadcom-ai-story-strengthens-after-expansion-with-google/">Broadcom ’s AI Growth Driven by Google TPU &amp; Anthropic Expansion</a></li>
<li><a href="https://www.ainvest.com/news/broadcom-ai-infrastructure-momentum-implications-long-term-growth-2509/">Broadcom &#x27;s AI Infrastructure Momentum and Its Implications for...</a></li>

</ul>
</details>

**标签**: `#AI Infrastructure`, `#Corporate Finance`, `#Semiconductor Industry`, `#Tech Investment`

---