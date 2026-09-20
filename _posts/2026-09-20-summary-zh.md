---
layout: default
title: "Horizon Summary: 2026-09-20 (ZH)"
date: 2026-09-20
lang: zh
---

> 从 29 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [ProgramAsWeights：将英文函数描述编译为本地运行的神经网络程序](#item-tech-news-1) ⭐️ 8.0/10
2. [DiffusionGemma：如何在 PyTorch 中并行生成文本](#item-tech-news-2) ⭐️ 8.0/10
3. [加州州长签署行政令，拟强制上报 AI 失控事件并加强安全监管](#item-tech-news-3) ⭐️ 8.0/10
4. [OpenAI 推出 ChatGPT for Word 插件，可在 Word 内起草编辑文档](#item-tech-news-4) ⭐️ 8.0/10
5. [AI 生成的海报不一定糟糕](#item-tech-news-5) ⭐️ 7.0/10
6. [AI 写作的认知陷阱与应用建议](#item-tech-news-6) ⭐️ 7.0/10
7. [超曲面约束动态权重更新的语言模型架构实验](#item-tech-news-7) ⭐️ 7.0/10

**财经新闻**
1. [特朗普称获格陵兰安全永久控制权 丹麦称下周签署](#item-finance-news-1) ⭐️ 9.0/10
2. [四家 AI 巨头因呼吁放缓研发遭反垄断诉讼](#item-finance-news-2) ⭐️ 8.0/10
3. [美团、飞猪等平台因涉嫌算法营销被调查](#item-finance-news-3) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [ProgramAsWeights：将英文函数描述编译为本地运行的神经网络程序](https://www.reddit.com/r/MachineLearning/comments/1wl13eu/programasweights_compile_english_function/) ⭐️ 8.0/10

ProgramAsWeights \(PAW\) 是滑铁卢大学的一个开源研究项目，它允许用户用英文描述文本函数，将其编译成可重用的神经网络程序，并在本地（包括 CPU）运行，从而将编译与推理分离以实现高效应用。该系统使用微调的 Qwen3-4B 模型作为编译器，为冻结的 Qwen3-0.6B 解释器生成 LoRA 适配器，使不同的函数能共享相同的解释器基权重。这种方法在 FuzzyBench 数据集上，使用 0.6B 解释器的 PAW 达到了 73.4% 的精确匹配准确率，优于直接提示 Qwen3-32B 的 68.7%。PAW 还提供了一种通过训练进行编译的高精度模式，通过合成示例并微调生成的适配器，在 FuzzyBench-Hard 子集上实现了 83.6% 的语义准确率。

reddit · r/MachineLearning · /u/yuntiandeng · 9月19日 23:35

**「背景」** 在许多人工智能应用中，任务定义是固定的，而输入数据则不断变化，例如对数千封电子邮件进行分类。ProgramAsWeights 提出的核心思想是将“理解所需功能”（编译）与“重复执行该功能”（推理）这两个过程分离。通过训练一个大型模型来生成特定任务的权重，这些权重使一个较小的模型能够高效地执行重复性任务，从而避免了每次推理都依赖大型模型进行理解。

**「影响」** ProgramAsWeights 通过将自然语言描述的 AI 功能编译为可在本地 CPU 上运行的紧凑神经网络程序，显著降低了文本处理任务的延迟和成本，同时增强了用户隐私，并促进了可重用、可组合的 AI 软件组件的开发。

**标签**: `#AI Deployment`, `#Local Inference`, `#Natural Language Processing`, `#Machine Learning Research`, `#Open Source`

---

<a id="item-tech-news-2"></a>
### [DiffusionGemma：如何在 PyTorch 中并行生成文本](https://www.reddit.com/r/MachineLearning/comments/1wkdnns/diffusiongemma_how_it_generates_text_in_parallel/) ⭐️ 8.0/10

该文章详细介绍了 DiffusionGemma，展示了如何使用扩散模型在 PyTorch 中从零开始实现并行文本生成。它为高效的自然语言处理（NLP）模型开发提供了重要见解，通过利用扩散模型实现更快的文本生成。这种方法对于寻求优化 NLP 模型性能的机器学习从业者和软件工程师尤其有价值。

reddit · r/MachineLearning · /u/Winter\_Mistake\_3185 · 9月19日 05:41

**「背景」** 传统的自回归大型语言模型通常以逐个词元（token）的顺序方式生成文本。DiffusionGemma 是 Google DeepMind 开发的一种实验性开源语言模型，它摒弃了这种顺序生成方式，转而采用离散扩散模型，能够并行地迭代优化 256 个词元块，从而显著提高了文本生成速度，避免了传统模型的顺序解码瓶颈。

**「影响」** 这一技术深度解析为开发者提供了实现和优化高级 NLP 技术的实用指南，有望带来更高效、可扩展的文本生成系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/models/gemma/diffusiongemma/">DiffusionGemma — Google DeepMind</a></li>
<li><a href="https://huggingface.co/google/diffusiongemma-26B-A4B-it">google/diffusiongemma-26B-A4B-it · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2608.00146">[2608.00146] DiffusionGemma Technical Report - arXiv.org</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Artificial Intelligence`, `#Natural Language Processing`, `#Diffusion Models`, `#PyTorch`

---

<a id="item-tech-news-3"></a>
### [加州州长签署行政令，拟强制上报 AI 失控事件并加强安全监管](https://finance.sina.com.cn/stock/usstock/c/2026-09-19/doc-inisisqc3124180.shtml) ⭐️ 8.0/10

美国加州州长加文·纽森于 9 月 19 日签署了一项行政令，旨在加强人工智能（AI）安全，提议强制要求企业上报 AI 智能体“失控事件”，并可能要求先进 AI 模型配备紧急关停机制。该行政令还将召集一个专家小组，在两个月内提出完善 AI 安全法律的指导意见，并建议对 AI 实验室进行定期审计。纽森州长表示，由于联邦政府监管不足，加州有必要采取行动。

telegram · zaihuapd · 9月19日 05:44

**「背景」** 行政令是美国州长发布的一种指令，具有法律效力，用于管理州政府的运作并设定政策。加州州长加文·纽森签署此行政令，旨在弥补其认为联邦政府在人工智能监管方面的不足，从而在州层面推动 AI 安全措施。

**「影响」** 此行政令将直接影响在加州运营的 AI 公司，要求它们强制上报“失控”AI 事件，并可能需要为先进模型配备紧急关停机制，这在联邦监管不足的情况下为州级 AI 监管树立了重要先例。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://insiderpaper.com/california-governor-newsom-ai-kill-switch/">California governor signs order to explore AI &#x27;kill switch&#x27; - Insider ...</a></li>
<li><a href="https://deadline.com/2026/09/gavin-newsom-ai-executive-order-1237107446/">Gavin Newsom Moves To Lasso AI With Oversight Executive Order</a></li>

</ul>
</details>

**标签**: `#AI Safety`, `#AI Regulation`, `#Public Policy`, `#Artificial Intelligence`, `#Technology Industry`

---

<a id="item-tech-news-4"></a>
### [OpenAI 推出 ChatGPT for Word 插件，可在 Word 内起草编辑文档](https://chatgpt.com/apps/word/) ⭐️ 8.0/10

OpenAI 已推出官方 ChatGPT for Word 插件，将 ChatGPT 的能力直接引入 Microsoft Word，使用户能够在 Word 内部起草、编辑和排版文档。该插件还能接入 Outlook、SharePoint、Google Workspace 和 Dropbox 等应用，以补充文档上下文。此功能面向全球所有套餐，包括免费版、企业版和教育版，用户可从 Microsoft Marketplace 安装并使用其 ChatGPT 账号登录。

telegram · zaihuapd · 9月19日 10:21

**「背景」** ChatGPT 是 OpenAI 开发的一款基于大型语言模型的聊天机器人，能够理解和生成人类语言。Microsoft Word 是一款广泛使用的文字处理软件，用于创建和编辑文档。此次集成旨在将先进的 AI 文本生成和编辑能力直接带入日常文档工作流程。

**「影响」** 该插件通过将先进的 AI 功能直接嵌入到全球数百万用户日常使用的 Microsoft Word 中，显著提升了文档创建和编辑的效率和智能化水平。

**标签**: `#Artificial Intelligence`, `#Productivity Tools`, `#Software Integration`, `#Microsoft Word`, `#OpenAI`

---

<a id="item-tech-news-5"></a>
### [AI 生成的海报不一定糟糕](https://john.hartnup.uk/2026/06/07/ai-event-posters.html) ⭐️ 7.0/10

一篇文章探讨了人工智能（AI）生成高质量海报的潜力，引发了关于 AI 在创意设计领域能力和局限性的广泛讨论。社区辩论主要集中在 AI 生成作品的创意限制、其倾向于刻板印象的设计风格，以及与人类艺术产出相比被视为“低投入”的感知。评论者指出，即使是文章中被认为是“更好”的 AI 海报，也常因明显的 AI 痕迹和技术缺陷（如变形的线框球体）而被批评为“糟糕”。

hackernews · ereiamjh · 9月19日 09:20 · [社区讨论](https://news.ycombinator.com/item?id=49764791)

**「背景」** 生成式 AI 是一种人工智能技术，能够根据文本提示（prompt）生成图像、文本或其他媒体内容。尽管它在艺术和设计领域得到广泛应用，但其作品的原创性、质量以及训练数据来源的伦理问题引发了持续的争议。批评者常指出，AI 生成的内容可能缺乏深度，倾向于刻板印象，并且在细节上容易出现不自然或错误。

**「影响」** 对于寻求经济实惠设计方案的客户而言，AI 生成工具可能提供比普通自由设计师更优的替代方案，从而影响创意设计市场的竞争格局。

**「社区讨论」** 社区评论普遍认为，文章中被视为“更好”的 AI 生成海报仍然存在明显缺陷，例如缺乏原创性、倾向于刻板印象以及技术渲染错误，这些都传递出“低投入”的信号。然而，也有观点指出，对于预算有限的项目，AI 的产出可能优于普通自由设计师的表现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.forbes.com/sites/danidiplacido/2023/12/30/ai-generated-art-was-a-mistake-and-heres-why/">The Problem With AI-Generated Art, Explained</a></li>
<li><a href="https://www.theguardian.com/commentisfree/2025/may/20/ai-art-concerns-originality-connection">The trouble with AI art isn’t just lack of originality. It’s something far bigger | Eric Reinhart | The Guardian</a></li>
<li><a href="https://www.computer.org/publications/tech-news/trends/artists-mad-at-ai">AiArt: Why Some Artists Are Furious About AI-Produced Art</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Generative AI`, `#Creative Design`, `#AI Limitations`

---

<a id="item-tech-news-6"></a>
### [AI 写作的认知陷阱与应用建议](https://erichgrunewald.substack.com/p/why-you-should-almost-never-use-ai) ⭐️ 7.0/10

文章及其讨论深入审视了使用 AI 进行写作的潜在认知陷阱，并提供了何时以及如何有效利用 AI 工具进行沟通和内容生成的细致建议。讨论指出，阅读 AI 生成的文本与主动创作文本之间存在显著的认知差异，AI 可能导致作者被动接受近似词汇，从而削弱批判性思维和精确的措辞选择。此外，AI 生成的文本常会添加非作者本意的内容，可能掩盖核心信息，并以难以察觉的方式产生模糊或错误。因此，建议将 AI 用于个人阅读和内部辅助，例如生成摘要或报告草稿，而非直接用于面向外部受众的最终内容。

hackernews · erwald · 9月19日 16:35 · [社区讨论](https://news.ycombinator.com/item?id=49767937)

**「背景」** 人工智能写作通常指利用大型语言模型（LLM）等 AI 工具生成文本内容。随着这些工具的普及，关于其在沟通和内容创作中应用有效性与潜在弊端的讨论日益增多。本文作者埃里希·格鲁内瓦尔德（Erich Grunewald）探讨了何时以及如何使用 AI 写作，并强调即使是 AI 生成的内容也应明确标注，以便读者自行判断其可信度，但他认为几乎不应使用 AI 来撰写完整的实质性文本（tool-1-1, tool-1-2, tool-1-3）。

**「影响」** AI 写作可能导致沟通效率下降，并因其模糊和潜在错误而增加人工校对和修正的时间成本，尤其是在需要精确表达和细致入微的语境中。

**「社区讨论」** 社区讨论普遍认为，AI 写作可能导致作者被动接受不精确的表达，并因 AI 添加非本意内容而模糊核心信息，甚至以难以察觉的方式引入错误，从而增加校对负担。评论者建议将 AI 主要用于个人阅读和内部辅助，例如生成研究摘要或会议纪要草稿，而非直接用于面向外部受众的最终内容。此外，有观点提出，与其让 AI 直接生成文本，不如利用其批判性地审查人类写作，但需警惕 LLM 过度改写的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://erichgrunewald.substack.com/p/why-you-should-almost-never-use-ai">Why I Think You Should Almost Never Use AI to Write Anything Substantive</a></li>
<li><a href="https://www.erichgrunewald.com/posts/why-i-think-you-should-almost-never-use-ai-to-write-anything-substantive/">Why You Should Almost Never Use AI to Write Anything Substantive</a></li>
<li><a href="https://forum.nunosempere.com/posts/stmA3cmXY8jaZahtg/why-you-should-almost-never-use-ai-to-write-anything">Why You Should Almost Never Use AI to Write Anything Substantive</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Large Language Models`, `#AI Application`, `#Technical Communication`, `#Cognitive Impact`

---

<a id="item-tech-news-7"></a>
### [超曲面约束动态权重更新的语言模型架构实验](https://www.reddit.com/r/MachineLearning/comments/1wksamz/experimenting_with_hypersurfaceconstrained/) ⭐️ 7.0/10

一项实验探索了一种新颖的语言模型架构，旨在通过动态更新权重来减少训练参数并缓解 VRAM 瓶颈，其灵感来源于通用 Transformer。该模型通过学习到的超曲面生成权重增量（𝛥Wl），并将其应用于基础解码器层（Wl = W0 + 𝛥Wl），其中超曲面由周期函数（如三角波）定义。一个使用三个循环块、三角波和上下文调制的实验模型，在 FineWeb-Edu 数据集的 100 亿 token 样本上预训练后，其参数量仅为标准 24 层解码器 Transformer 的约 16%（27,162,624 vs 169,906,944）。尽管经典架构仍能产生最佳绝对损失，但该模型在性能上优于标准展开基线，为硬件资源受限的场景提供了潜力。

reddit · r/MachineLearning · /u/manila\_danimals · 9月19日 17:34

**「背景」** 通用 Transformer（Universal Transformer）是一种循环 Transformer 变体，它重复应用相同的 Transformer 块，以提高参数效率并实现更深层次的有效计算。门控线性注意力（Gated Linear Attention）是一种高效的线性注意力机制，它通过引入门控机制来增强标准线性注意力，同时保持计算优势，常用于高效的循环解码。FineWeb-Edu 数据集是一个大规模、高质量的教育网络数据集，包含从 FineWeb 数据集中筛选出的数万亿个 token。

**「影响」** 这项实验为大型语言模型开发者和研究人员提供了一种潜在的解决方案，通过大幅减少模型参数量（例如，降至基线模型的约 16%）来降低 VRAM 需求，从而可能实现更高效的硬件资源利用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Universal_Transformer">Universal Transformer</a></li>
<li><a href="https://arxiv.org/abs/1807.03819">Abstract page for arXiv paper 1807.03819: Universal Transformers</a></li>
<li><a href="https://research.google/blog/moving-beyond-translation-with-the-universal-transformer/">Moving Beyond Translation with the Universal Transformer</a></li>
<li><a href="https://arxiv.org/abs/2312.06635">[2312.06635] Gated Linear Attention Transformers with Hardware-Efficient Training</a></li>
<li><a href="https://openreview.net/forum?id=AC9FsaVIpk">Gating is Weighting: Understanding Gated Linear Attention through In-context Learning | OpenReview</a></li>
<li><a href="https://sustcsonglin.github.io/assets/pdf/icml24_poster_gla.pdf">Gated Linear Attention Transformers with Hardware-Efficient Training</a></li>
<li><a href="https://hf.edwardfuchs.keenetic.pro/datasets/HuggingFaceFW/fineweb-edu?duplicate=true">HuggingFaceFW/ fineweb - edu · Datasets at Hugging Face</a></li>
<li><a href="https://www.emergentmind.com/topics/fineweb-edu-dataset">FineWeb - Edu : Quality Educational Web Data</a></li>
<li><a href="https://www.innovatiana.com/en/datasets/fineweb-edu">Massive corpus of filtered educational pages for LLM... | Innovatiana</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Neural Networks`, `#Language Models`, `#Model Architecture`, `#Parameter Efficiency`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [特朗普称获格陵兰安全永久控制权 丹麦称下周签署](https://mp.weixin.qq.com/s/rIUqosxjd5xwqkA-OxFvHg) ⭐️ 9.0/10

The US claims to have secured permanent security control over Greenland with plans for a large military presence, while Denmark confirms an agreement is expected to be signed next week.

telegram · zaihuapd · 9月19日 01:18

**标签**: `#Geopolitics`, `#Defense Policy`, `#Arctic Region`, `#International Agreements`

---

<a id="item-finance-news-2"></a>
### [四家 AI 巨头因呼吁放缓研发遭反垄断诉讼](https://www.politico.com/news/2026/09/18/anthropic-openai-spacexai-google-sued-over-calls-to-pace-ai-development-01085023) ⭐️ 8.0/10

Anthropic、OpenAI、SpaceXAI 和 Google 四家 AI 巨头在美国加州联邦法院遭到反垄断诉讼。原告指控这些公司通过公开支持“放慢 AI 发展”的主张，形成非法协调，涉嫌违反美国反垄断法《谢尔曼法》第 1 条。

telegram · zaihuapd · 9月19日 02:08

**「背景」** 美国《谢尔曼法》是一项反垄断法，旨在维护商业领域的自由竞争，禁止限制贸易和垄断行为。此次诉讼指控四家公司通过公开响应“放慢 AI 发展”的主张，形成非法协调，涉嫌违反该法案中关于限制竞争的规定。

**「影响」** 如果诉讼成功，可能会影响人工智能服务的消费者，并改变人工智能行业内竞争和创新的步伐。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.apa.az/america/anthropic-google-openai-spacexai-sued-for-attempt-to-slow-down-ai-development-525164">Anthropic , Google , OpenAI , SpaceXAI sued for attempt to slow down...</a></li>
<li><a href="https://www.politico.com/news/2026/09/18/anthropic-openai-spacexai-google-sued-over-calls-to-pace-ai-development-01085023">Anthropic , OpenAI , SpaceXAI , Google sued over call to... - POLITICO</a></li>
<li><a href="https://en.wikipedia.org/wiki/Sherman_Antitrust_Act">Sherman Antitrust Act - Wikipedia</a></li>
<li><a href="https://www.ftc.gov/advice-guidance/competition-guidance/guide-antitrust-laws/antitrust-laws">The Antitrust Laws | Federal Trade Commission</a></li>
<li><a href="https://www.law.cornell.edu/wex/sherman_antitrust_act">Sherman Antitrust Act | Wex | US Law | LII / Legal Information Institute</a></li>

</ul>
</details>

**标签**: `#Antitrust`, `#AI Industry`, `#Legal Action`, `#Competition`

---

<a id="item-finance-news-3"></a>
### [美团、飞猪等平台因涉嫌算法营销被调查](https://mp.weixin.qq.com/s/FsHQ-AG2zSNSWfA2sJAXfQ) ⭐️ 8.0/10

北京市市场监督管理局已对美团、飞猪、同程和途家立案调查，指控其在酒店住宿业务中涉嫌算法营销和定价方面的反竞争行为。

telegram · zaihuapd · 9月19日 07:47

**「背景」** 美团、飞猪、同程和途家是中国主要的在线旅游平台，提供酒店住宿预订服务。北京市市场监督管理局负责市场监管和反垄断执法，此前已对携程等在线旅游平台进行过反垄断调查和处罚。

**「影响」** 此次调查影响中国主要的在线旅游平台，并凸显了监管机构对平台经济中算法实践的审查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meituan">Meituan - Wikipedia</a></li>
<li><a href="https://english.beijing.gov.cn/government/departments/202006/t20200622_1929912.html">Beijing Municipal Administration for Market Regulation</a></li>
<li><a href="https://www.lexology.com/library/detail.aspx?g=1e686f17-5ccc-451b-94af-442c607ab4c0">China Monthly Antitrust Update: February 2026 - Lexology</a></li>

</ul>
</details>

**标签**: `#Regulatory Action`, `#Online Travel`, `#Anti-Monopoly`, `#China Tech`, `#Platform Economy`

---