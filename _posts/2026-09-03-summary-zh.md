---
layout: default
title: "Horizon Summary: 2026-09-03 (ZH)"
date: 2026-09-03
lang: zh
---

> 从 42 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [Paint.NET 开发者利用 AI 重写 Direct2D，实现 WINE 兼容性](#item-tech-news-1) ⭐️ 10.0/10
2. [Meta Muse Spark 1.3 模型发布，性能显著提升且定价极具竞争力](#item-tech-news-2) ⭐️ 8.0/10
3. [Google 发布 Gemini 3.8 Flash 和 3.8 Flash Cyber AI 模型](#item-tech-news-3) ⭐️ 8.0/10
4. [AI 搜索引用大量低质量 AI 生成内容，Perplexity 被点名](#item-tech-news-4) ⭐️ 8.0/10
5. [Mistral AI 数据训练选择退出政策变更引发用户隐私担忧](#item-tech-news-5) ⭐️ 8.0/10
6. [开发者发布 59.4 亿 TikTok 视频和 32.3 亿用户资料数据集](#item-tech-news-6) ⭐️ 8.0/10
7. [Jasper Research 发布从零构建文本到图像模型的详细指南](#item-tech-news-7) ⭐️ 8.0/10
8. [大多数开源 AI 检测器无法维持 0.5%的误报率，并存在偏见](#item-tech-news-8) ⭐️ 8.0/10
9. [CABiNet 与 YOLO26-sem 在 UAVid 数据集上的实时语义分割性能对比](#item-tech-news-9) ⭐️ 8.0/10
10. [Mac App Store 应用可弃用 Intel Mac，Tahoe 成最后支持版](#item-tech-news-10) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Paint.NET 开发者利用 AI 重写 Direct2D，实现 WINE 兼容性](https://simonwillison.net/2026/Sep/2/rick-brewster/) ⭐️ 10.0/10

Paint.NET 的开发者 Rick Brewster 利用 AI 工具 Claude，从零开始、以“洁净室”逆向工程的方式重写了 Direct2D 图形 API，生成了约 180,000 行代码。这一壮举使得 Paint.NET 首次能够在 WINE 环境下运行，解决了长期以来 Direct2D 兼容性不足的难题，并展示了 AI 在复杂系统级软件开发中的巨大潜力。新代码位于\`PaintDotNet.Windows.Direct2D1.Managed.dll\`，通过\`/wine\`参数激活，尽管代码量庞大且未经彻底审查，但 AI 在处理资源管理和逆向工程 Direct2D 内置效果库方面表现出色，尽管也需要开发者进行大量指导和修正。

rss · Simon Willison · 9月2日 05:50

**「背景」** Direct2D 是微软开发的一个 2D 图形 API，广泛应用于 Windows 应用程序，是 Paint.NET 的核心渲染组件。WINE 是一个兼容层，旨在允许 Windows 应用程序在类 Unix 操作系统（如 Linux）上运行，但由于其对 Direct2D 等复杂 Windows API 的支持不完善，Paint.NET 此前无法在 WINE 上正常运行。

**「影响」** 这一成就直接使得 Paint.NET 用户现在可以通过 WINE 在 Linux 等系统上运行该应用，同时为软件工程领域展示了 AI 在生成大规模、复杂系统级代码方面的可行性。

**标签**: `#Artificial Intelligence`, `#Code Generation`, `#Software Engineering`, `#Cross-platform Compatibility`, `#Graphics APIs`

---

<a id="item-tech-news-2"></a>
### [Meta Muse Spark 1.3 模型发布，性能显著提升且定价极具竞争力](https://developer.meta.com/ai/models/muse-spark/) ⭐️ 8.0/10

Meta 发布了 Muse Spark 1.3 模型，该模型在 DeepSWE 等基准测试中取得了 75.4 分的顶尖成绩，超越了 Google Gemini 3.8 Flash，并显著提升了输出质量。它提供了极具竞争力的低成本定价，使其成为开发者可负担的强大工具。这些改进使得 Muse Spark 1.3 成为大型语言模型市场中的有力竞争者，并加剧了生成式 AI 行业的竞争。

hackernews · bvaldivielso · 9月2日 19:35 · [社区讨论](https://news.ycombinator.com/item?id=49541256)

**「背景」** Muse Spark 是 Meta 开发的一系列大型语言模型，旨在为开发者提供高效且经济的生成式 AI 工具。这些模型以其在特定任务上的良好性能和成本效益而闻名，广泛应用于各种 AI 驱动的应用程序开发。

**「影响」** 对于开发者而言，Muse Spark 1.3 提供了一个性能接近最先进水平但成本极低的替代方案，尤其适用于不需要顶尖模型的工作负载，这有望推动整个大型语言模型市场的价格下降并促进更多创新应用。

**「社区讨论」** 社区用户普遍对 Muse Spark 1.3 的性能提升和极低定价表示赞赏，有用户通过实际测试发现其 SVG 生成质量优于前一版本，且 DeepSWE 跑分达到新高。同时，用户也讨论了 Meta 明确的数据训练政策，认为其揭示了模型提供商对用户数据训练的价值，并指出这种竞争将有助于降低市场价格。

**标签**: `#Artificial Intelligence`, `#Large Language Models`, `#Generative AI`, `#Benchmarking`, `#Technology Industry`

---

<a id="item-tech-news-3"></a>
### [Google 发布 Gemini 3.8 Flash 和 3.8 Flash Cyber AI 模型](https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/) ⭐️ 8.0/10

Google 发布了 Gemini 3.8 Flash 和 3.8 Flash Cyber 两款新型 AI 模型，显著提升了速度、成本效益和智能水平。这些模型在效率和能力上取得了重大进展，社区报告显示其性能可与领先的、更大的模型竞争，甚至在某些基准测试中超越了 Opus 5。Gemini 3.8 Flash 的智能得分达到 59，与 Opus 5 medium 持平，使其成为开发者和 AI 应用的强大工具。其多模态支持，包括接受音频和视频输入，也使其在媒体分析等领域具有独特优势。

hackernews · bratao · 9月2日 15:12 · [社区讨论](https://news.ycombinator.com/item?id=49537553)

**「背景」** Gemini 是 Google 开发的一系列多模态人工智能模型，旨在处理和理解文本、图像、音频和视频等多种数据类型。Flash 系列模型则专注于提供更快的推理速度和更高的成本效益，以满足对效率有严格要求的应用场景。

**「影响」** Gemini 3.8 Flash 和 3.8 Flash Cyber 的发布为开发者提供了更经济高效且功能强大的 AI 解决方案，尤其是在需要快速响应和处理多模态数据的应用中，例如生成 HTML/JavaScript 代码、旅行规划和媒体内容分析。

**「社区讨论」** 社区用户对 Gemini 3.8 Flash 的速度和成本效益表示兴奋，尤其是在生成 HTML/JavaScript 代码方面表现出色，有用户以 1.8 美分和 13 秒生成了代码。用户还指出，该模型在真实世界知识、照片排名和文档解析方面表现优异，并且在 DeepSWE 和 ArtificialAnalysis.ai 等基准测试中超越或持平于 Opus 5，尽管有用户观察到 3.8 版本在“低思考级别”的成本上可能相对于 3.7 版本有所退步。

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Large Language Models`, `#Software Engineering`, `#AI Models`

---

<a id="item-tech-news-4"></a>
### [AI 搜索引用大量低质量 AI 生成内容，Perplexity 被点名](https://trellner.com/reports/manufactured-sources-behind-ai-recommendations/) ⭐️ 8.0/10

一份报告揭示，Perplexity 等人工智能驱动的搜索引擎正在引用大量低质量、由人工智能生成的“最佳软件”页面。具体而言，有三个网站制造了 215,128 个此类页面，这些页面随后被 AI 系统引用。这一现象凸显了人工智能生态系统中内容污染和信息可靠性面临的严峻挑战，对 AI 系统的输出质量和数据来源的真实性提出了质疑。

hackernews · jakobgreenfeld · 9月2日 13:59 · [社区讨论](https://news.ycombinator.com/item?id=49536375)

**「背景」** Perplexity 等 AI 驱动的搜索引擎旨在通过整合和总结来自多个来源的信息来提供直接答案，而非仅仅列出链接。然而，随着大型语言模型（LLMs）生成内容的能力日益增强，互联网上充斥着大量低质量、由 AI 自动生成的文章，这些文章通常旨在操纵搜索引擎排名，导致信息生态系统受到污染。

**「影响」** 这一趋势导致人工智能系统输出的信息质量下降，用户可能因此接收到不准确或不可靠的推荐，从而损害对 AI 搜索工具的信任。

**「社区讨论」** 社区讨论指出，大型语言模型（LLM）可能偏爱自身生成的内容，甚至在搜索时包含虚构信息，例如一个不存在的“Foobar 广场”。有用户反映 Perplexity 的服务质量下降，响应速度虽快但结果却“一塌糊涂”，普遍认为当前模型缺乏对信息来源的批判性评估能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://trellner.com/reports/manufactured-sources-behind-ai-recommendations/">Three sites made 215,128 &quot;best software&quot; pages... | Trellner Research</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Data Quality`, `#AI Ethics`, `#Information Retrieval`

---

<a id="item-tech-news-5"></a>
### [Mistral AI 数据训练选择退出政策变更引发用户隐私担忧](https://help.mistral.ai/en/articles/455207-can-i-opt-out-of-my-input-or-output-data-being-used-for-training) ⭐️ 8.0/10

Mistral AI 对其数据训练选择退出政策进行了调整，引发了用户和组织对数据隐私和控制的日益增长的担忧。最初，其 Pro 层默认选择加入数据训练，随后 Team 层也变为默认选择加入，并似乎失去了集中禁用训练的能力。这一变化对那些将 AI 服务集成到其工作流程中，特别是具有严格合规要求的组织和开发者，产生了重要影响。

hackernews · teekert · 9月2日 12:30 · [社区讨论](https://news.ycombinator.com/item?id=49535284)

**「背景信息」** 人工智能模型通常通过分析大量数据进行训练，其中可能包含用户的输入和输出。关于用户数据是否用于模型训练及其选择退出机制的政策，是 AI 服务中一个重要的隐私和控制问题。Mistral AI 作为一家欧洲 AI 公司，其数据隐私控制曾备受关注，但近期其数据训练选择退出政策的变化引发了用户担忧。

**「影响」** AI 服务提供商（如 Mistral AI 和 GitHub Copilot）将数据训练政策改为默认选择加入，增加了用户和组织维护数据隐私和控制的负担。这种变化迫使受影响的用户和组织持续监控并调整设置，甚至考虑更换服务提供商以保护其数据。

**「社区讨论」** 社区讨论显示，用户普遍担忧 AI 公司可能无论用户是否选择退出都会使用其数据进行训练，并有用户提及微软/GitHub Copilot 的类似经历。有用户表示，为了保护隐私，他们转向了其他服务，但承认未来政策仍存在不确定性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://conductatlas.com/platform/mistral-ai/">Mistral AI — Policy monitoring and change archive | ConductAtlas</a></li>
<li><a href="https://aiweekly.co/alerts/mistral-docs-confirm-vibe-free-tier-trains-on-user-prompts-by-default">Mistral Docs Confirm Vibe Free Tier Trains on User... | AI Weekly</a></li>
<li><a href="https://smartscope.blog/en/generative-ai/github-copilot/github-copilot-data-training-policy-2026/">GitHub Copilot Data Training Policy : Settings... - SmartScope</a></li>
<li><a href="https://wavespeed.ai/blog/posts/github-copilot-data-training-policy-2026/">GitHub Copilot Data Training Policy in 2026 | WaveSpeed Blog</a></li>
<li><a href="https://apidog.com/blog/github-copilot-data-privacy-opt-out/">Urgent: How to Stop GitHub Copilot from Using Your Code for AI...</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Data Privacy`, `#AI Ethics`, `#Vendor Policy`, `#Machine Learning`

---

<a id="item-tech-news-6"></a>
### [开发者发布 59.4 亿 TikTok 视频和 32.3 亿用户资料数据集](https://www.reddit.com/r/MachineLearning/comments/1w5h9se/i_scraped_594_billion_tiktok_videos_and_323/) ⭐️ 8.0/10

一位开发者在 Reddit 上宣布，他已将一个包含 59.4 亿 TikTok 视频和 32.3 亿用户资料的庞大数据集上传至 Hugging Face 并免费开放。该数据集是作者几年前通过逆向工程 TikTok 移动应用程序接口（API）开发的方法收集的，该方法允许在无需 TikTok 账户的情况下访问 24 个公开端点。尽管 TikTok 应用暴露的数据是公开可访问的，但以这种方式获取数据可能违反了 TikTok 的服务条款，且完整的收集代码并非免费提供。这一资源为机器学习研究，特别是社交媒体分析、计算机视觉和内容理解领域，提供了宝贵的数据。

reddit · r/MachineLearning · /u/DataShack · 9月2日 17:38

**「背景」** TikTok 是一款全球流行的短视频社交应用，拥有庞大的用户基础和海量内容。对于机器学习研究而言，大规模的社交媒体数据集是分析用户行为、内容趋势、计算机视觉和自然语言处理等领域的重要资源。Hugging Face 是一个知名的机器学习平台，提供模型、数据集和工具的共享与协作。

**「影响」** 该数据集的免费发布为机器学习研究人员提供了一个前所未有的、大规模的 TikTok 内容和用户行为分析资源，有望推动社交媒体分析、推荐系统和内容理解等领域的研究进展。

**标签**: `#Machine Learning`, `#Datasets`, `#Data Scraping`, `#Social Media`, `#Open Source`

---

<a id="item-tech-news-7"></a>
### [Jasper Research 发布从零构建文本到图像模型的详细指南](https://www.reddit.com/r/MachineLearning/comments/1w5c9rd/detailed_explanation_of_how_to_create_a/) ⭐️ 8.0/10

Jasper Research 发布了一份详细的“食谱”，指导如何从零开始构建文本到图像模型。该资源提供了完整的推理过程、中间结果、一个包含 1 亿张图像的数据集（Monet Dataset）以及一个带有小型模型的代码库（nano t2i）。它旨在帮助用户深入理解文本到图像模型，并了解前沿实验室的构建方法，使其成为软件工程师和 AI 研究人员进行学习和开发的宝贵工具。

reddit · r/MachineLearning · /u/dh7net · 9月2日 14:40

**「背景信息」** Jasper Research 是一家专注于人工智能和机器学习创新的研究机构，致力于推动 AI 技术的边界。他们开发先进的 AI 工具，并经常将其开源，尤其在图像生成领域有所建树。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jasper-research.com/about-us">Why Us? | Jasper Research</a></li>
<li><a href="https://rs.linkedin.com/company/heyjasperai">Jasper | LinkedIn</a></li>
<li><a href="https://www.jasper.ai/blog/jasper-research-generate-on-brand-images-at-scale">Jasper Research Unlocks New Ways to Generate... | The Jasper Blog</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Artificial Intelligence`, `#Text-to-Image`, `#Deep Learning`, `#Open Source`

---

<a id="item-tech-news-8"></a>
### [大多数开源 AI 检测器无法维持 0.5%的误报率，并存在偏见](https://www.reddit.com/r/MachineLearning/comments/1w58erw/most_opensource_ai_detectors_cant_hold_a_05/) ⭐️ 8.0/10

一项研究对六款主流开源 AI 检测器进行了严格评估，发现其中大多数无法在现代 AI 输出和人工改写文本上维持 0.5%的误报率。具体而言，四款模型未能达到此标准，例如 MAGE 模型将 26%的普通人类网页文本错误标记为 AI 生成，而旧的 OpenAI RoBERTa 检测器在现代生成器上的 AUC 仅为 0.31。此外，所有检测器在处理人工改写的 AI 文本时性能显著下降，最佳模型召回率仅为 42%，并且普遍对非母语作者的文本存在偏见，以更高频率将其标记为 AI 生成。

reddit · r/MachineLearning · /u/grumpyp2 · 9月2日 12:04

**「背景」** 随着人工智能工具在文本生成中的应用日益广泛，区分人类创作和 AI 生成文本的需求也随之增加，催生了 AI 检测器的发展。这些检测器旨在评估文本的来源，但其准确性，尤其是在处理现代 AI 输出和人类润色文本时，一直是一个挑战。例如，梁（Liang）在 2023 年收集的托福（TOEFL）作文数据集，就曾被多个 AI 检测工具错误地标记为 AI 生成，凸显了该技术的局限性。

**「影响」** 这些结果表明，当前大多数开源 AI 检测器在实际应用中并不可靠，尤其是在识别经过人工润色的 AI 内容和评估非母语作者文本时，可能导致大量误判和不公平对待。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5407424">Artificial Writing and Automated Detection by Brian Jabarian , Alex Imas</a></li>
<li><a href="https://www.academia.edu/166076783/AI_Writing_Detection_in_Higher_Education_Population_Differentiated_False_Positives_Statistical_Convergence_and_the_Sociology_of_Algorithmic_Classification">(PDF) AI Writing Detection in Higher Education...</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Open Source`, `#AI Detection`, `#Bias in AI`

---

<a id="item-tech-news-9"></a>
### [CABiNet 与 YOLO26-sem 在 UAVid 数据集上的实时语义分割性能对比](https://www.reddit.com/r/MachineLearning/comments/1w5cfv1/cabinet_icra_2021_vs_yolo26sem_on_uavid_accuracy/) ⭐️ 8.0/10

一位作者重新评估了其 2021 年的实时语义分割模型 CABiNet，并将其与假设的 2026 年多任务模型 YOLO26-sem 在 UAVid 航空数据集上进行了详细的技术性能比较，分析了准确性、计算量和 GPU 延迟。结果显示，在 1024x1024 分辨率下，CABiNet-L 在更高精度端表现出色，mIoU 达到 67.14%，延迟为 4.44 毫秒，优于 YOLO26x-sem 的 64.41% mIoU 和 13.09 毫秒延迟；在相似计算量（约 44 GFLOPs）下，CABiNet-S 的 mIoU 为 65.25%，延迟 3.09 毫秒，也比 YOLO26s-sem 的 61.69% mIoU 和 2.52 毫秒延迟更准确。CABiNet 在小型/细长类别（如人类、静止汽车、移动汽车）上显示出显著的 mIoU 提升，尽管两模型在训练配方、预训练和数据增强方面存在差异，但数据表示、类别权重和评估协议均已标准化。

reddit · r/MachineLearning · /u/Naive-Explanation940 · 9月2日 14:46

**「背景」** 语义分割是一种计算机视觉任务，旨在将图像中的每个像素分类到预定义的类别中，而实时语义分割则要求模型以极低的延迟完成此任务。CABiNet 是一个 2021 年发布的双分支卷积神经网络（CNN），专为实时语义分割设计，其特点是结合了高分辨率空间分支和轻量级上下文分支。YOLO（You Only Look Once）系列模型通常以其在目标检测领域的实时性能而闻名，YOLO26-sem 是其一个假设的、针对语义分割任务的变体，代表了更通用、多任务模型的未来发展方向。

**「影响」** 对于需要高精度和低延迟的无人机实时语义分割应用，CABiNet 在特定场景下展现出优于更通用模型的效率和准确性，这表明专用架构在某些领域仍具有显著优势。

**标签**: `#Semantic Segmentation`, `#Computer Vision`, `#Real-time AI`, `#Deep Learning`, `#Model Efficiency`

---

<a id="item-tech-news-10"></a>
### [Mac App Store 应用可弃用 Intel Mac，Tahoe 成最后支持版](https://www.macrumors.com/2026/09/01/mac-app-store-intel-mac-support/) ⭐️ 8.0/10

Apple 已通知开发者，macOS 13 及以上版本的 Mac App Store 通用应用现可选择放弃对 Intel Mac 的支持。此举旨在简化开发流程，并优化应用的下载大小与设备占用空间。这意味着 Intel Mac 用户将不再收到这些应用的后续更新，但仍可继续使用最后兼容的版本，而“Tahoe”则成为支持 Intel Mac 的最后版本。

telegram · zaihuapd · 9月2日 03:30

**「背景」** 苹果一直在将其 Mac 电脑从英特尔处理器过渡到自研的 Apple Silicon 芯片，而“通用应用”是指同时支持这两种架构的应用程序。macOS Tahoe 26 是 macOS 的最新版本，并且已确认是最后一个支持英特尔 Mac 的主要 macOS 版本，标志着这一过渡进程中的一个重要里程碑。

**「影响」** 这项政策转变直接影响开发者，使其能够为 Apple Silicon 简化代码库，而 Intel Mac 用户将面临 macOS 13 及以上应用新软件更新的逐步停止。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://support.apple.com/en-us/122867">macOS Tahoe 26 is compatible with these computers - Apple Support</a></li>
<li><a href="https://pccentral.net/apple-macos-26-tahoe-last-intel-mac-support/">Apple macOS 26 Tahoe to be Last Version Supporting Intel Macs</a></li>
<li><a href="https://www.itechguides.com/your-old-macbooks-days-are-numbered-macos-tahoe-26-is-intels-last-major-release/">Your old MacBook&#x27;s days are numbered: is Intel Mac support ...</a></li>

</ul>
</details>

**标签**: `#macOS`, `#Apple Silicon`, `#Software Development`, `#Developer Policy`, `#Hardware Transition`

---