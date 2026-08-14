---
layout: default
title: "Horizon Summary: 2026-08-14 (ZH)"
date: 2026-08-14
lang: zh
---

> 从 40 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [GLM-5.3 模型展现出自主网络安全能力，可进行漏洞研究和利用](#item-tech-news-1) ⭐️ 9.0/10
2. [开发者将《毁灭战士》渲染器编译成 210 亿参数 Transformer，无需训练](#item-tech-news-2) ⭐️ 9.0/10
3. [Vivodyne 利用 AI 机器人实验室规模化人体组织实验，旨在取代动物测试](#item-tech-news-3) ⭐️ 9.0/10
4. [PostgreSQL 修复 to\_char 高危漏洞，允许低权限用户执行任意代码](#item-tech-news-4) ⭐️ 9.0/10
5. [苹果自研中国专属 AI 大模型，联手阿里或成首个获批外企](#item-tech-news-5) ⭐️ 9.0/10
6. [小红书开源 dots3-note：280B MoE 模型，16B 激活参数，支持多模态](#item-tech-news-6) ⭐️ 8.5/10
7. [Qwen 3.8 27B 发布：增强推理与图像生成能力](#item-tech-news-7) ⭐️ 8.0/10
8. [Claude Opus 5 使用体验下降引社区讨论](#item-tech-news-8) ⭐️ 8.0/10
9. [Firefox 成为唯一仍完全支持 uBlock Origin 的主流浏览器](#item-tech-news-9) ⭐️ 8.0/10
10. [Doug Turnbull 创新方法：LLM &\#x27;幻觉&\#x27; 结合向量嵌入实现内容标签](#item-tech-news-10) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [GLM-5.3 模型展现出自主网络安全能力，可进行漏洞研究和利用](https://z.ai/blog/glm-5.3) ⭐️ 9.0/10

GLM-5.3 是一款新兴的 AI 模型，在网络安全领域展现出先进的自主能力，包括漏洞研究和漏洞利用生成。该模型能够自主发现零日漏洞、远程代码执行（RCE）和内核漏洞，并对开源软件进行大规模漏洞扫描。这标志着人工智能在软件工程和安全应用方面取得了重大突破，可能对漏洞发现和防御方式产生行业变革性的影响。

hackernews · pella · 8月14日 05:19 · [社区讨论](https://news.ycombinator.com/item?id=49294997)

**「背景」** GLM 系列模型是由 Z.ai 开发的人工智能助手，主要用于代码编写、网站建设和处理复杂任务。GLM-5.3 是该系列的最新版本，在 GLM-5.2 的基础上进行了后训练，显著提升了编码能力，并在网络安全领域展现出前沿的自主研究和漏洞利用生成能力。

**「影响」** GLM-5.3 能够大规模扫描开源和流行软件并披露其发现的漏洞，其中许多被认为是关键或高危级别，这预示着漏洞发现和防御的范式可能发生转变。

**「社区讨论」** 有用户报告称，GLM 模型在红队场景中表现出色，能够无缝执行零日漏洞利用和内核漏洞适应，甚至能与另一个 GLM 代理进行防御对抗。社区成员还指出，该模型正在大规模扫描开源软件并披露大量关键或高危漏洞，并讨论了其与现有模型的性能对比以及潜在的经济影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://z.ai/blog/glm-5.3">GLM-5.3: Frontier Coding with Emergent Cyber Capabilities</a></li>
<li><a href="https://www.reddit.com/r/singularity/comments/1vnz30c/glm_53_released_frontier_coding_with_emergent/">r/singularity on Reddit: GLM 5.3 released: Frontier Coding with Emergent Cyber Capabilities</a></li>
<li><a href="https://x.com/Zai_org/status/2088132965922476159">Introducing GLM-5.3: Built to Code. Ready for Cyber ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Cybersecurity`, `#Large Language Models`, `#Software Engineering`, `#Vulnerability Research`

---

<a id="item-tech-news-2"></a>
### [开发者将《毁灭战士》渲染器编译成 210 亿参数 Transformer，无需训练](https://www.reddit.com/r/MachineLearning/comments/1voazhm/i_compiled_dooms_renderer_into_a_21bparameter/) ⭐️ 9.0/10

一位开发者成功地将《毁灭战士》的渲染算法编译成一个 210 亿参数的 Transformer 模型，完全绕过了传统的机器学习训练过程。该方法利用一个定制编译器将计算图直接转换为标准的 Transformer 权重，这些权重可直接通过 Hugging Face 加载。渲染过程涉及将场景数据作为 3,614 个 token 的提示输入，然后生成 53,747 个包含像素绘制命令的 token，最终由一个 43 行的 Python 宿主程序解析并渲染出图像。尽管这种方法展示了在 Transformer 架构中部署复杂算法的新颖途径，但其性能远低于原始游戏，在 NVIDIA B200 GPU 上渲染一帧大约需要 40 分钟，而原始《毁灭战士》在 486 电脑上可达到每秒 35 帧。

reddit · r/MachineLearning · /u/notforrob · 8月14日 15:50

**「背景」** Transformer 是一种神经网络架构，以其在自然语言处理任务中的成功而闻名，能够通过权衡输入不同部分的权重来处理序列数据。传统上，它们通过大量数据集的训练来学习模式。然而，本项目将 Transformer 用作确定性算法的直接计算引擎，而非用于学习推理。

**「影响」** 该项目为在 Transformer 架构中直接部署复杂的确定性算法提供了一个开创性的范例，且无需传统的机器学习训练。它表明 Transformer 可能作为通用计算引擎运行，从而将其应用范围从学习任务扩展到直接执行编译代码。

**标签**: `#Transformers`, `#Compilers`, `#Machine Learning`, `#Computer Graphics`, `#Novel Architectures`

---

<a id="item-tech-news-3"></a>
### [Vivodyne 利用 AI 机器人实验室规模化人体组织实验，旨在取代动物测试](https://www.fastcompany.com/91589344/the-worlds-largest-biological-datacenter-could-help-make-animal-testing-obsolete) ⭐️ 9.0/10

Vivodyne 公司正在旧金山南部利用 AI 驱动的机器人实验室，大规模培养人体组织并设计实验，以更准确地预测新药的疗效和安全性。该系统目前拥有 12 个“蜂巢”机器人实验室，每年能够进行超过 300 万个人体组织受控实验，其容量是美国所有临床试验总和的两倍。此举旨在提高药物研发效率，并有望取代传统的动物测试，鉴于目前约 90% 的临床试验在通过动物测试后仍以失败告终。

telegram · zaihuapd · 8月14日 01:48

**「背景信息」** Vivodyne 是一家利用人工智能和机器人技术进行药物测试的公司。他们通过在体外培养逼真的人体组织，并利用自动化实验室对这些组织进行大规模药物实验，旨在更准确地预测新药的疗效和安全性，从而在临床试验前提供关键数据。

**「影响」** Vivodyne 的 AI 驱动人体组织测试平台有望使制药公司更准确地预测药物疗效和安全性，从而可能降低目前高达 90-95% 的临床试验失败率，并与美国 FDA 旨在取代动物测试的目标相符。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.vivodyne.com/">Vivodyne | Make biology computable</a></li>
<li><a href="https://www.vivodyne.com/platform">Vivodyne - Our Platform</a></li>
<li><a href="https://www.linkedin.com/company/vivodyne">Vivodyne | LinkedIn</a></li>
<li><a href="https://www.businesswire.com/news/home/20250528498236/en/Vivodyne-to-Replace-Animal-Testing-With-$40-Million-Funding-to-Reverse-95-Clinical-Trial-Failure-Rate">Vivodyne to Replace Animal Testing With $40 Million Funding to Reverse 95% Clinical Trial Failure Rate</a></li>
<li><a href="https://www.helena.org/projects/vivodyne/">Vivodyne | Helena</a></li>
<li><a href="https://longevity.technology/investment/vivodyne-lands-40m-to-replace-animal-testing-in-drug-development/">Vivodyne lands $40m to replace animal testing in drug development</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Robotics`, `#Biotechnology`, `#Drug Discovery`, `#Machine Learning`

---

<a id="item-tech-news-4"></a>
### [PostgreSQL 修复 to\_char 高危漏洞，允许低权限用户执行任意代码](https://www.postgresql.org/support/security/CVE-2026-14669/) ⭐️ 9.0/10

PostgreSQL 项目发布紧急安全更新，修复了 \`to\_char\(timestamptz\)\` 函数中一个高危堆缓冲区溢出漏洞 \(CVE-2026-14669\)。该漏洞在处理超长 POSIX 时区缩写时触发，允许拥有设置时区权限的低权限数据库用户以 PostgreSQL 服务进程的操作系统权限执行任意代码。此漏洞的 CVSS 评分为 8.8，影响 PostgreSQL 18.5、17.11、16.15、15.19 及 14.24 之前的版本。用户应分别升级至 18.6（针对 18 系列）、17.11、16.15、15.19 或 14.24，此次更新仅需更新程序文件并重启服务，无需转储数据库或运行 \`pg\_upgrade\`。

telegram · zaihuapd · 8月14日 14:35

**「背景」** \`to\_char\` 是 PostgreSQL 中用于将各种数据类型（如日期/时间）格式化为字符串的函数，而 \`timestamptz\` 是一种带有时区信息的日期时间数据类型。堆缓冲区溢出是一种常见的内存安全漏洞，当程序尝试向固定大小的内存区域（堆缓冲区）写入超出其容量的数据时发生，可能导致数据损坏或允许攻击者执行恶意代码。

**「影响」** 受影响的 PostgreSQL 数据库管理员和用户必须立即应用补丁，以防止低权限数据库账户利用此漏洞获取服务器的操作系统权限，从而造成数据泄露或系统破坏。

**标签**: `#PostgreSQL`, `#Security`, `#Vulnerability`, `#Database`, `#Open Source`

---

<a id="item-tech-news-5"></a>
### [苹果自研中国专属 AI 大模型，联手阿里或成首个获批外企](https://www.reuters.com/business/retail-consumer/apple-trains-its-own-ai-model-china-market-with-alibabas-support-sources-say-2026-08-14/) ⭐️ 9.0/10

苹果据报正专门为中国市场训练一款大型语言模型，并获得阿里巴巴的支持，此举标志着其放弃了此前依赖第三方模型的策略。此自研模型将使苹果能更好地掌控其在华的 AI 体验，并预计在未来数月随 iOS 更新上线 Apple Intelligence。中国国家互联网信息办公室已于上月备案了苹果的生成式 AI 服务。若最终获批，苹果有望成为首家获北京批准在中国提供自有 AI 模型的外国公司，这将开创重要的行业和监管先例。

telegram · zaihuapd · 8月14日 14:47

**「背景信息」** 中国已实施生成式人工智能服务管理规定，其中《生成式人工智能服务管理暂行办法》于 2023 年 8 月 15 日生效，由国家互联网信息办公室（网信办）等机构发布。这些规定旨在监管面向公众的生成式人工智能服务，并要求在华提供此类服务的外国公司遵守相关法律法规。

**「影响」** 苹果此举可能使其成为首家在中国获得监管批准、提供自有专有 AI 服务的外国公司，从而为其在中国市场推出 Apple Intelligence 铺平道路。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Interim_Measures_for_the_Management_of_Generative_AI_Services">Interim Measures for the Management of Generative AI Services - Wikipedia</a></li>
<li><a href="https://www.whitecase.com/insight-our-thinking/ai-watch-global-regulatory-tracker-china">AI Watch: Global regulatory tracker - China | White &amp; Case LLP</a></li>
<li><a href="https://www.dwt.com/blogs/artificial-intelligence-law-advisor/2023/07/china-issues-generative-ai-regulations">China&#x27;s Cyberspace Administration Releases &quot;Interim&quot; Rules Regulating the Use of Generative AI | Davis Wright Tremaine</a></li>
<li><a href="https://superintelligencenews.com/ai-fields/large-language-models/apple-intelligence-china-alibaba-custom-model/">Apple Intelligence China : Apple Teams With Alibaba</a></li>
<li><a href="https://www.china-briefing.com/news/china-standards-2035-strategy-recent-developments-and-their-implications-foreign-companies/">The China Standards 2035 Strategy: Analyzing Recent Developments</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Technology Industry`, `#China Market`, `#Regulatory Affairs`, `#Mobile Technology`

---

<a id="item-tech-news-6"></a>
### [小红书开源 dots3-note：280B MoE 模型，16B 激活参数，支持多模态](https://x.com/dotsstudioai/status/2088083314855018521) ⭐️ 8.5/10

小红书 dots 实验室已开源其 dots3 系列的首个开放权重模型 dots3-note preview，该模型总参数达 280B，每次激活仅需 16B 参数，并支持 512K 的超长上下文窗口。dots3-note 是一款多模态模型，能够处理文字、图片、视频和音频数据。此外，该模型引入了名为 TEMPO 的新型强化学习方法，通过自批判和测试时价值估计来训练长程智能体，其权重已在 Hugging Face 上发布，并同步推出了 VibeSearchBench 和 VibeLifeBench 两个真实场景智能体基准。

telegram · zaihuapd · 8月14日 08:27

**「背景」** MoE（Mixture-of-Experts）模型是一种神经网络架构，它通过让不同的“专家”子网络专注于输入数据的不同部分，并在推理时仅激活部分专家，从而在保持模型规模的同时提高计算效率。多模态人工智能是指能够理解和处理多种数据类型（如文本、图像、音频和视频）的 AI 系统。强化学习则是一种机器学习范式，智能体通过与环境交互并接收奖励或惩罚来学习如何做出决策。

**「影响」** dots3-note 的开源及其附带的新型强化学习方法和真实场景智能体基准，为人工智能研究人员和开发者提供了宝贵的工具和资源，有望推动高效大型模型、多模态理解以及长程智能体训练等领域的研究进展。

**标签**: `#Artificial Intelligence`, `#Multimodal AI`, `#Mixture of Experts \(MoE\)`, `#Open Source`, `#Reinforcement Learning`

---

<a id="item-tech-news-7"></a>
### [Qwen 3.8 27B 发布：增强推理与图像生成能力](https://huggingface.co/Qwen/Qwen3.8-27B-FP8) ⭐️ 8.0/10

Qwen 3.8 27B 是一款新发布的大型语言模型，因其增强的推理能力和详细的图像生成能力而受到社区赞扬，尤其适用于本地部署。该模型在基准测试中展现出强大的推理能力，并在生成式 AI 性能方面表现出色，代表了本地运行大型语言模型的显著进步，引起了 AI 开发者的广泛兴趣。

hackernews · erdaltoprak · 8月14日 15:00 · [社区讨论](https://news.ycombinator.com/item?id=49299605)

**「背景」** Qwen（通义千问）是阿里巴巴开发的一系列大型语言模型。Qwen 3.8 27B 是该系列中一个拥有 270 亿参数的新模型，它是一个原生的视觉语言模型，能够理解图像和视频。该模型旨在通过灵活的思维控制，更可靠地完成复杂的、多步骤的任务。

**「影响」** Qwen 3.8 27B 为本地部署的 AI 开发者提供了更强大的推理和图像生成能力，尤其在复杂基准测试和细节丰富的图像创作方面表现突出。

**「社区讨论」** 社区普遍认可 Qwen 3.8 27B 在本地模型中展现出的卓越推理和图像生成能力，尤其在复杂基准测试和细节丰富的图像创作方面表现突出。然而，也有用户指出其显存使用效率低于其他模型，并对模型独特的“思考”过程及其对性能的潜在影响表示关注，同时寻求关闭或调整此功能的方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B-FP8">Qwen/Qwen3.8-27B-FP8 · Hugging Face</a></li>
<li><a href="https://sourceforge.net/software/product/Qwen3.8-27B/">Qwen3.8-27B Reviews in 2026</a></li>

</ul>
</details>

**标签**: `#Large Language Models`, `#AI Reasoning`, `#Local Inference`, `#Generative AI`

---

<a id="item-tech-news-8"></a>
### [Claude Opus 5 使用体验下降引社区讨论](https://mun-logadan.github.io/why-does-opus-5-feel-worse/) ⭐️ 8.0/10

社区对 Claude Opus 5 的沟通风格和可用性进行了深入讨论，许多用户认为其输出变得“晦涩难懂”且“抽象”。有观点推测，该模型可能已将优化重心转向 AI 间的交互，而非人类可读性，导致其生成内容充斥着“代理语言”和不必要的冗余。用户反映 Opus 5 常使用非生命名词作主语，并频繁“坦白”错误，使得交流过程令人疲惫。尽管其能力可能有所提升，但这种沟通方式显著降低了用户体验。

hackernews · numeri · 8月14日 10:12 · [社区讨论](https://news.ycombinator.com/item?id=49296740)

**「Claude Opus 5 简介」** Claude Opus 5 是由美国软件公司 Anthropic 开发的 Claude 大型语言模型系列中的一个版本，该系列旨在帮助用户解决复杂问题、分析数据和编写代码。在 Claude 3 系列中，Opus 是能力最强的模型，而 Opus 5 则被定位为一款深思熟虑且积极主动的模型，其智能水平接近 Claude Fable 5，但价格仅为其一半。

**「影响」** 受影响的用户发现与 Claude Opus 5 协作变得“筋疲力尽”，导致部分用户转而使用 OpenAI Sol 或回退到旧版本如 Claude 4.8 以寻求更友好的交互体验。

**「社区讨论」** 社区普遍认为 Opus 5 的写作风格过于“晦涩”和“抽象”，常偏离主题，且存在不必要的冗余表达，例如频繁“坦白”错误。有用户分享了 Opus 5 生成的难以理解的抽象语句作为例证，并指出这种变化可能源于模型优化目标转向了“代理间对话”，而非人类可读性。因此，一些用户选择切换到 OpenAI Sol 或旧版模型以获得更好的使用感受。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Opus">Claude Opus</a></li>
<li><a href="https://www.anthropic.com/news/claude-opus-5">Introducing Claude Opus 5 \ Anthropic</a></li>
<li><a href="https://claude.com/product/overview">The AI for Problem Solvers | Claude by Anthropic</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Large Language Models`, `#User Experience`, `#AI Development`

---

<a id="item-tech-news-9"></a>
### [Firefox 成为唯一仍完全支持 uBlock Origin 的主流浏览器](https://www.pcworld.com/article/3212428/firefox-is-now-the-last-major-browser-that-still-supports-ublock-origin.html) ⭐️ 8.0/10

Firefox 现已成为唯一仍完全支持 uBlock Origin 等强大广告拦截器的主流浏览器。这一变化凸显了 Google Chrome 的 Manifest V3 政策对广告拦截功能和用户选择的重大影响。Manifest V3 限制了扩展程序的能力，导致 uBlock Origin 等工具在 Chrome 浏览器中无法像以前那样高效运行。此举对用户隐私、网络开发和开源生态系统产生了深远影响，促使技术社区密切关注。

hackernews · DemiGuru · 8月14日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=49303202)

**「背景」** Manifest V3 是 Google Chrome 浏览器扩展程序的一套新规则，旨在限制扩展程序的功能和权限。这些规则对广告拦截器等功能强大的扩展程序产生了显著影响，因为它们限制了这些扩展程序拦截广告和跟踪器的能力。因此，像 uBlock Origin 这样依赖更广泛 API 访问的全面广告拦截器，在采用 Manifest V3 的浏览器中将无法正常运行。

**「社区讨论」** 社区讨论指出，Firefox 会对 uBlock Origin 等热门扩展程序进行代码审查以确保安全性，而许多用户则批评 Google 的 Manifest V3 限制了扩展程序的自由和 API 功能，认为其在普遍反对下仍被强行推行。Manifest V3 已导致一些广告拦截工具停止服务，并使得在 Google 搜索中移除广告仅在 Firefox 中可行，促使部分用户呼吁支持 Firefox。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ghostery.com/blog/ublock-origin-stopped-working-manifestv3">Ublock Origin Stopped Working | Manifest V 3 uBlock ... | Ghostery</a></li>
<li><a href="https://factually.co/fact-checks/technology/manifest-v3-impact-ublock-origin-chromium-blocking-workarounds-4c8757">How Does Manifest V 3 Change What uBlock Origin Can Blo...</a></li>
<li><a href="https://www.gamermarkt.com/blog/chrome-ad-blockers-manifest-v3-alternatives/">Chrome Ad Blockers Are Done: Manifest V 3 Explained</a></li>

</ul>
</details>

**标签**: `#Browser Technology`, `#Web Extensions`, `#Open Source`, `#Privacy`, `#Ad Blocking`

---

<a id="item-tech-news-10"></a>
### [Doug Turnbull 创新方法：LLM &\#x27;幻觉&\#x27; 结合向量嵌入实现内容标签](https://simonwillison.net/2026/Aug/14/dont-classify-hallucinate/) ⭐️ 8.0/10

Doug Turnbull 提出了一种创新的内容标签方法，旨在解决大型标签词汇表难以直接输入大型语言模型（LLM）的问题。该方法不要求 LLM 从现有标签中进行分类，而是让模型“幻觉”出（即生成）与内容相关的全新标签。随后，这些“幻觉”标签通过向量嵌入技术与现有标签库进行匹配，找到最接近的具体标签。这种方法有效管理了庞大的标签系统，例如 Simon Willison 博客拥有的 1,856 个标签，通过提供标签格式示例来引导 LLM 生成更准确的猜测。

rss · Simon Willison · 8月14日 21:54

**「背景信息」** 大型语言模型（LLM）是能够理解和生成类人文本的先进人工智能系统。向量嵌入将文本转换为数值表示，从而可以衡量不同内容片段之间的语义相似性。内容标签是将描述性关键词分配给信息的过程，传统上在处理庞大、预定义的标签词汇表时面临挑战。

**「影响」** 这种方法为面临庞大且难以管理的标签集合的信息检索和内容管理系统提供了一个实用的解决方案，显著简化了新内容的标签过程，同时避免了用大量词汇表使 LLM 过载。

**标签**: `#Large Language Models`, `#Vector Embeddings`, `#Content Tagging`, `#Information Retrieval`, `#Software Engineering`

---