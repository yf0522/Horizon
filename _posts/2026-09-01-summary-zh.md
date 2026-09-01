---
layout: default
title: "Horizon Summary: 2026-09-01 (ZH)"
date: 2026-09-01
lang: zh
---

> 从 45 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [Google 从 Chrome 网上应用店下架 MV2 扩展，包括 UBO](#item-tech-news-1) ⭐️ 8.0/10
2. [将安防摄像头改造为 AI 驱动的自动鸟类识别系统](#item-tech-news-2) ⭐️ 8.0/10
3. [NAT 与互联网中心化的原罪](#item-tech-news-3) ⭐️ 8.0/10
4. [Wrapture：Python 统一测试与追踪的新库](#item-tech-news-4) ⭐️ 8.0/10

**财经新闻**
1. [厄尔尼诺预计达超级强度，全球粮食航运承压](#item-finance-news-1) ⭐️ 9.0/10
2. [美联储主席讲话后市场加息预期上升](#item-finance-news-2) ⭐️ 8.0/10
3. [怡安以 170 亿美元收购 USI 保险服务](#item-finance-news-3) ⭐️ 8.0/10
4. [习近平主席将进行多次国事访问，美国对印度关税调整](#item-finance-news-4) ⭐️ 8.0/10
5. [中国法院冻结安世半导体资产](#item-finance-news-5) ⭐️ 8.0/10
6. [欧盟认定 ChatGPT、Reddit、Roblox 为超大型服务，三者面临更严数字监管](#item-finance-news-6) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Google 从 Chrome 网上应用店下架 MV2 扩展，包括 UBO](https://webiterate.dev/google-removed-extensions-ublock-origin-108/) ⭐️ 8.0/10

谷歌已正式从 Chrome 网上应用店下架所有 Manifest V2 \(MV2\) 扩展程序，其中包括广受欢迎的广告拦截工具 UBlock Origin。此举标志着浏览器扩展政策和功能发生了重大转变，直接影响了数百万用户的网络隐私、广告拦截能力以及更广泛的浏览器扩展生态系统。这一政策调整引发了对用户控制和网络开放性的担忧。

hackernews · twapi · 8月31日 21:10 · [社区讨论](https://news.ycombinator.com/item?id=49514878)

**「背景」** Manifest V2 是 Google Chrome 浏览器扩展平台的旧版本，它允许扩展程序拥有广泛的功能和权限。Google 逐步淘汰了对 Manifest V2 扩展的支持，并计划用 Manifest V3 取代它，后者引入了更严格的权限模型和功能限制。此举对依赖 Manifest V2 的流行扩展（如 uBlock Origin 广告拦截器）产生了重大影响，因为 Chrome 139 终止了对其支持，而 Chrome 150 和 151 则移除了相关的代码路径和开发者标志。

**「影响」** 此举直接削弱了 Chrome 用户通过 MV2 扩展（如 UBlock Origin）增强网络隐私和有效拦截广告的能力，可能导致用户面临更多恶意广告和跟踪。

**「社区讨论」** 社区普遍认为，鉴于谷歌对扩展政策的控制以及对广告拦截的担忧，用户应转向 Firefox 浏览器，许多评论者指出 UBlock Origin 在 Firefox 上表现更佳，且 Firefox 提供了更好的隐私保护。一些用户还表达了对谷歌在互联网上日益增长的单边控制权的不满，并回忆起 Chrome 早期对网络的积极影响与当前状况的对比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://winaero.com/how-to-restore-manifest-v2-and-ublock-origin-in-google-chrome-139/">How to Restore Manifest V2 and uBlock Origin in Google Chrome ... - Winaero</a></li>
<li><a href="https://www.gblock.app/articles/chrome-151-manifest-v2-removed-ublock-origin-2026">Chrome 151 Kills Manifest V2 — uBlock Origin Is Done</a></li>
<li><a href="https://www.digitaltrends.com/computing/chrome-is-removing-the-last-workaround-keeping-popular-ad-blockers-alive/">Chrome is removing the last workaround keeping Manifest V2 ad blockers ...</a></li>

</ul>
</details>

**标签**: `#Browser Extensions`, `#Web Privacy`, `#Ad Blocking`, `#Google Chrome`, `#Open Source`

---

<a id="item-tech-news-2"></a>
### [将安防摄像头改造为 AI 驱动的自动鸟类识别系统](https://jasontucker.blog/how-i-turned-my-security-cameras-into-an-automatic-bird-identification-system-with-birdnet-go/) ⭐️ 8.0/10

一篇文章详细介绍了一个创新项目，该项目利用 AI 驱动的音频分析工具 BirdNet-Go，将标准安防摄像头转变为自动鸟类识别系统。该方案通过巧妙整合软件与现有硬件，实现了对鸟类声音的实时监测与分类。此举不仅展示了人工智能在家庭自动化领域的实际应用潜力，也为自然爱好者提供了一种低成本、高效的鸟类监测方法。该项目在技术社区引发了广泛兴趣，并就其实现细节和面临的挑战展开了深入讨论。

hackernews · speckx · 8月31日 16:47 · [社区讨论](https://news.ycombinator.com/item?id=49511856)

**「背景」** BirdNET-Go 是一个自托管的实时声景分析器，它利用 BirdNET AI 进行本地多模型分类，能够全天候识别鸟类、蝙蝠及其他野生动物的声音。它通常运行在树莓派等设备上，可以接收声卡输入或网络音频流，并将检测结果呈现在快速的网页用户界面中。BirdNET 本身是一个由康奈尔大学开发的、基于严谨研究的 AI 驱动声音识别系统，旨在将原始音频转化为经过同行评审的生态数据。

**「影响」** AI 驱动的鸟类识别系统，如 BirdNet-Go 和康奈尔大学的 Merlin Bird ID 应用，使用户能够将现有安全摄像头或专用硬件改造为自动鸟类识别系统，从而激发了对鸟类学的兴趣并提供了实用的应用。

**「社区讨论」** 社区成员积极分享了他们使用 BirdNet-Go 与安防摄像头（如 Unifi 门铃摄像头）的成功经验，并讨论了将检测结果显示在电子墨水屏上的扩展想法。然而，也有用户指出在实际操作中遇到的挑战，例如某些摄像头麦克风的抗风噪能力差和采样率（如 16kHz）低于 BirdNET-Go 推荐的 48kHz，这促使他们通过外接高质量麦克风和树莓派来优化音频输入，甚至构建便携式系统用于户外使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://birdnet.cornell.edu/">BirdNET – AI-Powered Sound ID</a></li>
<li><a href="https://github.com/BirdNET-Team/BirdNET-Analyzer">BirdNET-Analyzer - GitHub</a></li>
<li><a href="https://birdnet.cornell.edu/birdnet-pi/">BirdNET-Pi</a></li>
<li><a href="https://github.com/tphakala/birdnet-go">GitHub - tphakala/birdnet-go: Self-hosted realtime soundscape analyser ...</a></li>
<li><a href="https://github.com/tphakala/birdnet-go/wiki/BirdNET%E2%80%90Go-Guide">Home · tphakala/birdnet-go Wiki · GitHub</a></li>
<li><a href="https://www.birds.cornell.edu/home/merlin/">Merlin | Birds , Cornell Lab of Ornithology</a></li>
<li><a href="https://alumni.cornell.edu/cornellians/merlin-bird-app/">What’s that Bird ? Like Magic, ‘ Merlin ’ Can Tell You - Cornellians</a></li>
<li><a href="https://nc.inverse.com/tech/merlin-bird-id-app-cornell-university-ai">I Can&#x27;t Stop Using Cornell &#x27;s Free AI-Powered Merlin Bird ID App</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Audio Processing`, `#Home Automation`, `#Open Source`

---

<a id="item-tech-news-3"></a>
### [NAT 与互联网中心化的原罪](https://dreamstation.systems/personal/ntppost.html) ⭐️ 8.0/10

Hacker News 上的一场讨论深入探讨了网络地址转换（NAT）如何从根本上塑造了互联网架构，导致了中心化并改变了个人服务器的运行模式。Linux NAT 系统的主要实现者之一 Rusty Russell 解释说，为了将更多连接压缩到一个 IP 地址，避免端口预留导致来自不同地址的入站流量无法路由，从而消除了公共端点。这种“穷人防火墙”虽然解决了特定问题，却侵蚀了用户像过去那样运行服务器的能力，使得“我的设备与云端通信”的客户端-服务器模式成为常态。

hackernews · robinpie · 8月31日 02:23 · [社区讨论](https://news.ycombinator.com/item?id=49504905)

**「背景」** 网络地址转换（NAT）是一种网络技术，它允许一个私有网络中的多台设备共享一个公共 IP 地址来访问互联网。NAT 于 1994 年在 RFC 1631 中首次被正式提出，旨在解决当时 IP 互联网面临的 IP 地址耗尽和路由扩展性问题。

**「影响」** NAT 的广泛应用，特别是运营商级 NAT（CGNAT），限制了用户运行个人服务器和拥有公共端点的能力，从而将互联网推向了中心化的客户端-服务器模型，削弱了用户的自由度。

**「社区讨论」** 社区讨论中，NAT 的实现者 Rusty Russell 对该技术导致公共端点消失表示遗憾，而其他评论者则认为 NAT 是扼杀开放互联网的早期因素，因为它使运行服务器变得复杂并推广了客户端-服务器范式。不过，也有观点认为将 NAT 称为“原罪”是夸大其词，并指出常规 NAT 在可控情况下是可接受的，且它在一定程度上保护了不安全的设备。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dreamstation.systems/personal/ntppost.html">Internet centralization and the original sin of NAT</a></li>

</ul>
</details>

**标签**: `#Networking`, `#Internet Architecture`, `#Computer Systems`, `#Decentralization`, `#History of Technology`

---

<a id="item-tech-news-4"></a>
### [Wrapture：Python 统一测试与追踪的新库](https://simonwillison.net/2026/Aug/31/introducing-wrapture/) ⭐️ 8.0/10

Graham Dumpleton 发布了名为 Wrapture 的 Python 新库，它扩展了其广受欢迎的\`wrapt\`库的猴子补丁概念，旨在为测试和追踪提供一个统一的解决方案。Wrapture 可作为\`unittest.mock\`的替代品，并提供了一种非侵入式的方法来观察现有项目的代码执行，支持 OpenTelemetry 并可通过配置文件进行追踪。该项目虽然仅有数周历史，但由 AI 辅助开发并在 Dumpleton 的严格指导下完成，展示了其在代码观察和测试方面的潜力。

rss · Simon Willison · 8月31日 23:59

**「背景」** \`wrapt\`是一个 Python 库，以其强大的函数包装和猴子补丁能力而闻名，常用于装饰器和代理模式。\`unittest.mock\`是 Python 标准库的一部分，主要用于单元测试中模拟或替换对象，以便隔离测试目标并控制其行为。Wrapture 旨在结合两者的优势，提供更灵活的测试和追踪机制。

**「影响」** 对于 Python 软件工程师而言，Wrapture 提供了一个强大的新工具，可以简化测试中的模拟操作并实现对代码的非侵入式运行时观察，从而提高开发效率和代码可维护性。

**标签**: `#Software Engineering`, `#Python`, `#Testing`, `#Observability`, `#Open Source`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [厄尔尼诺预计达超级强度，全球粮食航运承压](https://m.thepaper.cn/newsDetail_forward_33846426) ⭐️ 9.0/10

热带太平洋厄尔尼诺正在迅速增强，预计最迟 2026 年 10 月达到“超级厄尔尼诺”强度，年底有近 70% 概率成为现代观测以来最强事件。巴拿马运河已计划限制每日通航量，世界粮食计划署警告到 2027 年底可能新增约 5000 万人陷入严重急性粮食不安全。

telegram · zaihuapd · 8月31日 04:01

**「背景」** 厄尔尼诺是一种自然气候现象，指赤道太平洋东部和中部海面温度持续异常变暖。此次事件可能刷新现代观测以来的最强纪录，并使 2027 年成为有记录以来最热年份。

**「影响」** 此次厄尔尼诺现象可能通过农作物减产、航运受阻以及粮食不安全人口增加，对全球粮食安全、国际航运和农业生产造成直接影响。

**标签**: `#Climate Risk`, `#Agricultural Commodities`, `#Supply Chain Disruption`, `#Food Prices`, `#Global Economy`

---

<a id="item-finance-news-2"></a>
### [美联储主席讲话后市场加息预期上升](https://www.cnbc.com/2026/08/31/markets-see-warsh-endorsing-a-rate-hike-in-september-not-everyone-is-convinced.html) ⭐️ 8.0/10

美联储主席凯文·沃什发表讲话后，市场对美联储在 9 月加息的预期显著上升，根据芝加哥商品交易所集团的 FedWatch 工具，9 月会议加息的概率从讲话前的约 33%跃升至 66.1%。

rss · CNBC Finance · 8月31日 19:38

**「背景」** 沃什在杰克逊霍尔年度研讨会上的讲话被市场解读为对通胀持鹰派立场，此前市场普遍预计美联储在 12 月前加息的可能性很小。

**「影响」** 受此影响，周一黄金价格下跌，亚洲股市也出现下滑。

**标签**: `#Monetary Policy`, `#Interest Rates`, `#Federal Reserve`, `#Market Expectations`, `#Inflation`

---

<a id="item-finance-news-3"></a>
### [怡安以 170 亿美元收购 USI 保险服务](https://www.cnbc.com/2026/08/31/aon-ceo-says-usi-deal-seeks-to-build-premiere-middle-market-insurance-platform.html) ⭐️ 8.0/10

保险经纪公司怡安（Aon）宣布将以 170 亿美元收购竞争对手 USI 保险服务公司，旨在建立“美国首屈一指的中端市场平台”，该交易预计在第四季度完成，尚待监管批准。

rss · CNBC Finance · 8月31日 15:15

**「背景」** 中端市场指的是美国约 20 万家公司及其 4800 万员工的保险需求，分析师认为该市场比大型企业保险业务增长更快。USI 是美国第十大保险经纪公司，年收入超过 30 亿美元。

**「影响」** 消息公布后，怡安的股价下跌了 7%，反映了投资者对此次大规模收购的初步反应。

**标签**: `#Mergers and Acquisitions`, `#Insurance Industry`, `#Corporate Strategy`, `#Financial Services`, `#Middle Market`

---

<a id="item-finance-news-4"></a>
### [习近平主席将进行多次国事访问，美国对印度关税调整](https://www.cnbc.com/2026/08/31/china-xi-us-trump-visit-sco-brics-modi-india.html) ⭐️ 8.0/10

中国国家主席习近平将在 9 月下旬预计访问美国之前，对埃及和印度进行罕见的国事访问；此前，美国已于今年 2 月宣布将对印度的关税从 50%下调至 18%。

rss · CNBC Finance · 8月31日 04:57

**「背景」** 习近平主席近年来大幅减少了出访，今年此前仅在 6 月访问过朝鲜，因此他繁忙的行程预示着中国外交优先事项的转变。

**「影响」** 美国将密切关注上海合作组织和金砖国家峰会，因为华盛顿正寻求改善与印度和中国的关系，但同时可能通过格雷厄姆法案对购买俄罗斯石油的国家施加最高达 100%的关税。

**标签**: `#Geopolitics`, `#Trade Policy`, `#International Relations`, `#Tariffs`, `#Emerging Markets`

---

<a id="item-finance-news-5"></a>
### [中国法院冻结安世半导体资产](https://www.reuters.com/world/asia-pacific/chinese-court-freezes-dutch-chipmaker-nexperia-bvs-stakes-four-china-units-2026-08-31/) ⭐️ 8.0/10

中国法院在闻泰科技提起的诉讼中，冻结了荷兰芯片制造商安世半导体及其设备子公司最高 21.4 亿元人民币（约 3 亿美元）的资产。闻泰科技指控安世半导体执行歧视性荷兰限制，并索赔 80 亿元人民币。

telegram · zaihuapd · 8月31日 12:26

**「背景」** 此前，荷兰政府因技术安全担忧，剥夺了中国闻泰科技对荷兰芯片制造商安世半导体的控制权。

**「影响」** 此次资产冻结和巨额索赔可能对安世半导体及其中国业务的运营和财务状况产生直接影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dutchtimes.nl/news/netherlands/dutch-government-seizes-control-of-nexperia-amid-rising-tech-tensions-with-china/">Dutch Government Seizes Control of Nexperia Amid Rising Tech ...</a></li>

</ul>
</details>

**标签**: `#Semiconductor Industry`, `#Legal Dispute`, `#Asset Freeze`, `#Cross-border Investment`, `#China`

---

<a id="item-finance-news-6"></a>
### [欧盟认定 ChatGPT、Reddit、Roblox 为超大型服务，三者面临更严数字监管](https://www.euronews.com/next/2026/08/31/eu-places-chatgpt-reddit-and-roblox-under-strictest-digital-safety-rules) ⭐️ 8.0/10

欧盟委员会于 8 月 31 日根据《数字服务法》将 ChatGPT 认定为超大型在线搜索引擎，并将 Reddit 和 Roblox 列为超大型在线平台，因为这三项服务在欧盟的月均活跃用户均超过 4500 万人。它们将有四个月的过渡期，之后须进行年度系统性风险评估、接受独立审计，并向监管机构及经审核的研究人员共享数据。

telegram · zaihuapd · 8月31日 14:39

**「背景」** 《数字服务法》（DSA）是欧盟于 2022 年生效的一项法规，旨在为数字服务建立一个关于问责制、内容审核和平台透明度的全面法律框架，其中对在欧盟拥有超过 4500 万月活跃用户的超大型在线平台和搜索引擎有最严格的要求。

**「对公司运营的影响」** 这一认定意味着 ChatGPT、Reddit 和 Roblox 将面临更严格的数字监管，包括年度系统性风险评估、独立审计以及向监管机构共享数据等要求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EU_Digital_Services_Act">EU Digital Services Act</a></li>
<li><a href="https://digital-strategy.ec.europa.eu/en/news/commission-designates-chatgpt-reddit-roblox-under-digital-services-act">Commission designates ChatGPT, Reddit, Roblox under Digital Services Act | Shaping Europe’s digital future</a></li>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/986682/openai-chatgpt-eu-dsa">ChatGPT to face tougher regulation in the EU | The Verge</a></li>
<li><a href="https://www.euronews.com/next/2026/08/31/eu-places-chatgpt-reddit-and-roblox-under-strictest-digital-safety-rules">EU places ChatGPT, Reddit and Roblox under strictest digital safety rules | Euronews</a></li>

</ul>
</details>

**标签**: `#EU Regulation`, `#Digital Services Act`, `#Tech Industry`, `#Online Platforms`, `#Policy Change`

---