---
layout: default
title: "Horizon Summary: 2026-08-13 (ZH)"
date: 2026-08-13
lang: zh
---

> 从 41 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [DRAM 操纵新方法实现低级系统访问](#item-tech-news-1) ⭐️ 9.0/10
2. [DeepMind 推出手语转文字模型 SL2T，首次应用于 Pixel 11](#item-tech-news-2) ⭐️ 9.0/10
3. [OpenAI 与 Cerebras 合作，GPT-5.6 Sol Ultrafast 实现 7 倍加速](#item-tech-news-3) ⭐️ 8.0/10
4. [DeepSeek Harness 发布开发者预览版：开源 AI 代理框架，提供高级可追溯性](#item-tech-news-4) ⭐️ 8.0/10
5. [《选择无聊技术》：创新代币与技术战略](#item-tech-news-5) ⭐️ 8.0/10
6. [DeepSeek V4 Pro 0813 模型发布，开放权重并支持峰谷定价](#item-tech-news-6) ⭐️ 8.0/10
7. [worldproof 工具揭示像素指标在评估世界模型时失效](#item-tech-news-7) ⭐️ 8.0/10
8. [国际象棋 Transformer 模型移除单个注意力头后无法找到复杂战术](#item-tech-news-8) ⭐️ 8.0/10
9. [苹果洽谈新闻内容授权，为 Siri AI 提供实时资讯，或采用按使用量付费模式](#item-tech-news-9) ⭐️ 8.0/10
10. [DeepSeek 发布 Harness 应用并开源 DeepSeek-V4-Pro-0813 模型权重](#item-tech-news-10) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [DRAM 操纵新方法实现低级系统访问](https://github.com/xoreaxeaxeax/skitter-creek-bath-salts) ⭐️ 9.0/10

一项名为“Spaghettifying DRAM”的研究项目，由知名安全研究员 Christopher Domas 发布在 GitHub 上，揭示了操纵 DRAM 以实现低级系统访问的新颖方法。这项研究代表了硬件安全和逆向工程领域的重大进展，可能导致硬件级别的漏洞利用和 Ring-0 权限访问。它深入探讨了计算机系统和硬件安全，具有高度的技术深度和新颖性。

hackernews · matt\_d · 8月13日 14:17 · [社区讨论](https://news.ycombinator.com/item?id=49286341)

**「背景」** DRAM（动态随机存取存储器）是计算机中用于存储运行时数据的主要内存类型。Christopher Domas（xoreaxeaxeax）的“Spaghettifying DRAM”研究揭示了一种通过修改 AMD Family 16h 处理器 DRAM 控制器的一个配置位来“扰乱”DRAM 物理地址映射的新方法。这种技术旨在绕过 CPU 的正常保护机制，从而获得对 PSP、C6、微代码和 SMM 等通常受限的 CPU 组件的低级访问权限。

**「影响」** 这项研究可能使攻击者在受影响的系统上获得 Ring-0 权限，从而访问通常隐藏在负环区域的所有内容，这对于 Xbox 和 PlayStation 等难以获取 Ring-0 权限的设备而言，可能带来显著的安全风险。目前已知该方法适用于 2013 年的 AMD Jaguar 架构，但其对更新 CPU 的适用性尚不明确。

**「社区讨论」** 社区成员对 Christopher Domas 的这项工作及其即将到来的 Black Hat 演讲表示高度期待，赞扬了他解释复杂研究的能力。讨论指出，现代 DRAM 的日益复杂性使其成为一个巨大的攻击面，并对该研究在 AMD Jaguar（2013 年架构）上的有效性以及其对 Zen 3 及其他更新 CPU 的适用性提出了疑问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/xoreaxeaxeax/skitter-creek-bath-salts">GitHub - xoreaxeaxeax/ skitter - creek - bath - salts : Unlocking...</a></li>
<li><a href="https://dzen.ru/b/an3nioa_N0hzeys8">Один бит в контроллере DRAM открывает всю память... | Дзен</a></li>
<li><a href="https://www.linkedin.com/in/christopher-domas">Christopher Domas - Independent Security Researcher | Reverse ...</a></li>

</ul>
</details>

**标签**: `#Hardware Security`, `#DRAM`, `#Reverse Engineering`, `#Computer Systems`, `#Exploitation`

---

<a id="item-tech-news-2"></a>
### [DeepMind 推出手语转文字模型 SL2T，首次应用于 Pixel 11](https://deepmind.google/blog/putting-sign-language-ai-into-users-hands/) ⭐️ 9.0/10

谷歌 DeepMind 发布了大规模多语言手语转文字 AI 模型 SL2T，首次将手语 AI 集成到消费产品中。该模型率先支持美国手语（ASL）转英语，并已在 Pixel 11 设备的 Gboard 键盘和实时字幕功能上线。SL2T 模型通过超过 10 万小时、50 多种手语数据训练，在 FLEURS-ASL 基准上零样本得分达到 70 BLEURT，远超此前记录，且为保护用户隐私，仅处理手部与身体姿态关键点。

telegram · zaihuapd · 8月13日 08:55

**「背景」** 手语转文字 AI 旨在通过识别手语动作并将其转换为书面文本，以弥合听障人士与健听人士之间的沟通鸿沟。此前，此类技术在消费级产品中的大规模应用面临数据量、准确性和隐私保护等多重挑战。

**「影响」** SL2T 模型在 Pixel 11 上的部署，显著提升了听障用户在日常沟通和信息获取方面的可访问性，为他们提供了更便捷的交流工具。

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Accessibility`, `#Sign Language Processing`, `#Mobile Technology`

---

<a id="item-tech-news-3"></a>
### [OpenAI 与 Cerebras 合作，GPT-5.6 Sol Ultrafast 实现 7 倍加速](https://www.cerebras.ai/blog/accelerating-gpt-5-6-sol-ultrafast-with-openai) ⭐️ 8.0/10

OpenAI 与 Cerebras 合作，据报道已成功将前沿大型语言模型 GPT-5.6 Sol 的运行速度提升了 7 倍。在评估中，GPT-5.6 Sol 的 Ultrafast 模式在 11 小时 11 分钟内回答了 2,500 个 HLE 问题，而 Claude Fable 5 完成相同任务需要 78 小时 27 分钟，实现了近 7 倍的加速且准确性相当。这一显著的性能提升有望大幅加速 AI 模型的处理和开发，从而实现更快的迭代和潜在更复杂的模型。

hackernews · pr337h4m · 8月13日 18:10 · [社区讨论](https://news.ycombinator.com/item?id=49289844)

**「背景信息」** GPT-5.6 Sol 是 OpenAI 的一个前沿大型语言模型，被描述为该公司最智能或最强大的模型。Cerebras 是一家专注于开发用于人工智能加速的专用硬件的公司，其技术正在为 OpenAI 的 Ultrafast 模式提供支持，旨在显著提升该模型的运行速度。

**「影响」** 此次加速使得大型语言模型能够以远超以往的速度处理复杂任务，例如在单个工作日内处理“人类知识的前沿”，从而可能显著缩短 AI 开发周期并催生更先进的模型。然而，社区中存在关于 Ultrafast 模式是否与标准 GPT-5.6 Sol 在性能上完全等同的疑问，这可能影响其直接应用场景。

**「社区讨论」** 社区对 OpenAI 和 Cerebras 的合作及其带来的显著速度提升表示兴奋，并有评论强调速度对于提高 LLM“思维质量”的重要性，因为它能促进迭代。然而，也有用户对 Ultrafast 模式是否与常规 GPT-5.6 Sol 在性能上完全一致表示怀疑，指出官方声明中缺乏明确的 1:1 性能等同性确认。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/previewing-ultrafast/">Previewing Ultrafast mode: GPT‑5.6 Sol at up to ... - OpenAI</a></li>
<li><a href="https://www.cerebras.ai/blog/accelerating-gpt-5-6-sol-ultrafast-with-openai">Accelerating GPT-5.6 Sol Ultrafast with OpenAI - cerebras.ai</a></li>
<li><a href="https://investors.cerebras.ai/news-releases/news-release-details/cerebras-powers-ultrafast-mode-openais-gpt-56-sol">Cerebras Powers Ultrafast Mode for OpenAI’s GPT-5.6 Sol ...</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Computer Systems`, `#Hardware Acceleration`, `#Performance Optimization`

---

<a id="item-tech-news-4"></a>
### [DeepSeek Harness 发布开发者预览版：开源 AI 代理框架，提供高级可追溯性](https://deepseek.com/harness/en/) ⭐️ 8.0/10

DeepSeek Harness 发布了其开源 AI 代理框架的开发者预览版，该框架基于全新的 Cordis v4 架构构建。它提供先进的可追溯性功能，允许开发者深入检查模型行为和推理过程，从而显著提升 AI 代理的调试和理解能力。这一特性通过记录系统提示、推理、工具调用、子代理调度和上下文注入等所有模型交互，为 AI 开发带来了新颖且有价值的透明度。作为一项开放源代码项目，它旨在促进 AI 代理开发和调试的进步。

hackernews · bjin · 8月13日 12:58 · [社区讨论](https://news.ycombinator.com/item?id=49285244)

**「背景信息」** Cordis 是一个元框架，提供先进的插件系统，支持在不重启运行进程的情况下热加载和卸载插件。它以在卸载时能够回滚状态和副作用、清理资源的能力而闻名，并提供依赖注入、事件通信和上下文隔离等核心功能。DeepSeek Harness 采用了最新的 Cordis v4 架构，该架构在 Koishi 等项目中使用的 v3 版本基础上进行了改进。

**「影响」** DeepSeek Harness 的深度可追溯性功能为 AI 开发者提供了一个强大的工具，能够详细检查代理的内部运作，这在许多现有 AI 模型中是难以实现的，从而有助于更有效地理解和调试复杂的 AI 行为。

**「社区讨论」** 社区讨论指出，DeepSeek Harness 目前处于早期开发者预览阶段，欢迎反馈。用户普遍认为其“一切皆可追溯”的特性是一项关键优势，因为它能记录模型所见的一切，而这在其他模型中常被加密或混淆；同时，该框架利用 Cordis v4 架构实现了插件的热加载和状态清理，尽管也有用户对“一切皆是插件”的架构模式表示了“插件疲劳”。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/cordiverse/cordis">GitHub - cordiverse/cordis: Meta-Framework of Spatiotemporal ...</a></li>
<li><a href="https://deepwiki.com/hydro-dev/Hydro/3-core-architecture">Core Architecture | hydro-dev/Hydro | DeepWiki</a></li>
<li><a href="https://deepwiki.com/cordiverse/cordis/3-core-architecture">Core Architecture | cordiverse/cordis | DeepWiki</a></li>
<li><a href="https://github.com/koishijs/docs/issues/185">Should explain cordis · Issue #185 · koishijs/docs</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#AI Agents`, `#Open Source`, `#Debugging`, `#Software Engineering`

---

<a id="item-tech-news-5"></a>
### [《选择无聊技术》：创新代币与技术战略](https://mcfunley.com/choose-boring-technology) ⭐️ 8.0/10

2015 年的经典文章《选择无聊技术》引入了“创新代币”概念，这是一个被广泛采纳的战略技术选择框架。该框架提出，每家公司拥有有限的创新预算（即“创新代币”），应谨慎分配。它在软件工程领域具有高度相关性，并被认为适用于人工智能等新兴领域，为技术决策提供了持久的指导。

hackernews · tosh · 8月13日 17:48 · [社区讨论](https://news.ycombinator.com/item?id=49289512)

**「背景」** “选择无聊技术”是丹·麦金利在 2015 年提出的一种软件工程理念，其核心观点是每家公司在技术创新上拥有有限的“创新代币”。这些代币代表了组织处理复杂性和新颖性的能力，应谨慎用于真正能区分业务的核心问题，而非基础设施或未经证实的工具。该理念倡导优先使用成熟、稳定的“无聊技术”，以降低运营风险并提高效率。

**「影响」** 该框架为技术领导者和软件工程师提供了宝贵的工具，帮助他们在面对新兴技术（如 AI）时，通过有效分配有限的“创新代币”来做出明智的战略决策。

**「社区讨论」** 社区普遍认为这篇文章极具价值，其“创新代币”概念对产品经理和工程领导者在权衡取舍方面非常有帮助，并强调其在代理/AI 时代仍具有持久的适用性。然而，也有评论指出，在实践中可能存在对“无聊技术”的误用，并且很难找到真正秉持这种工程文化的公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mcfunley.com/choose-boring-technology">Choose Boring Technology - Dan McKinley</a></li>
<li><a href="https://concepts.dsebastien.net/concept/innovation-tokens/">Innovation Tokens - Concepts</a></li>
<li><a href="https://concepts.dsebastien.net/concept/boring-technology/">Boring Technology - Concepts</a></li>

</ul>
</details>

**标签**: `#Software Engineering`, `#Technology Strategy`, `#Engineering Management`, `#AI Strategy`

---

<a id="item-tech-news-6"></a>
### [DeepSeek V4 Pro 0813 模型发布，开放权重并支持峰谷定价](https://simonwillison.net/2026/Aug/12/deepseek-v4-pro-0813/) ⭐️ 8.0/10

DeepSeek 发布了其最新的 V4 Pro 0813 模型，该模型拥有 1.7 万亿参数，文件大小为 893 GB。最初通过 API 在 OpenRouter 上提供，随后确认其开放权重已在 Hugging Face 上发布，这对开源 AI 社区是一个重要进展。新模型增强了 Agent 能力，原生支持 Responses API 格式并适配 Codex，同时为 V4-Pro 和 V4-Flash 新增了低、中、高三档思考模式。此外，API 调用将从 2026 年 8 月 17 日 0 时起实行峰谷定价，闲时价格为高峰时段的一半。

rss · Simon Willison · 8月12日 23:59

**「背景」** DeepSeek 是一家专注于人工智能研究的公司，此前已发布过 DeepSeek-V4-Pro（4 月）和 DeepSeek-V4-Flash-0731（7 月）等具有开放权重的大型语言模型。这些模型的发布通常旨在推动 AI 技术的透明度和可访问性，使研究人员和开发者能够更深入地探索和应用这些先进的模型。

**「影响」** DeepSeek V4 Pro 0813 开放权重的发布及其在代理和编码能力上的显著提升（在多项测试中超越 Opus 4.8），为开源人工智能社区和开发者提供了强大的新工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepseekv4pro.com/news/deepseek-v4-pro-0813-official-release-opus-fable-benchmarks">DeepSeek V 4 Pro 0813 : Opus 4.8 and Fable 5 Agent Benchmarks</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Large Language Models`, `#Open Source`, `#DeepSeek`

---

<a id="item-tech-news-7"></a>
### [worldproof 工具揭示像素指标在评估世界模型时失效](https://www.reddit.com/r/MachineLearning/comments/1vnliv7/worldproof_diagnosing_where_worldmodel/) ⭐️ 8.0/10

一个名为\`worldproof\`的开源工具被开发用于诊断预测未来帧的世界模型，它通过比较预测结果与真实情况及物理不变量来揭示预测失败的原因。在验证过程中，该工具发现常用的像素级指标（如 SSIM 和 PSNR）在评估真实机器人视频（例如 SO-101 机械臂和 DROID 数据集）上的世界模型时，往往无法有效区分模型性能。具体而言，在 SO-101 数据上，“复制最后一帧”基线模型的 SSIM 和 PSNR 在 6 步预测范围内几乎持平，而在 DROID 数据集上，SSIM 仅在约 8 到 24 步的预测范围内呈现出可区分的单调下降趋势，超出此范围则再次趋于平坦，表明这些指标在特定场景下缺乏鉴别力。\`worldproof\`工具是 Apache-2.0 许可，可通过\`pip install worldproof\`安装，支持 LeRobotDataset v3.0，并测量 PSNR、SSIM、LPIPS、潜在预测误差等多种指标。

reddit · r/MachineLearning · /u/georgia\_bucea · 8月13日 19:58

**「背景」** 世界模型（world models）是机器学习领域的一种模型，旨在学习环境的动态，从而能够预测未来的状态或帧，常用于机器人控制和规划。像素级指标如结构相似性指数（SSIM）和峰值信噪比（PSNR）是图像质量评估的常用方法，用于量化预测图像与真实图像之间的相似度，通常被用来评估世界模型预测帧的准确性。

**「影响」** 这一发现对依赖传统像素级指标评估世界模型的研究人员和开发者提出了挑战，促使他们重新审视现有评估方法，并探索更具鉴别力的诊断工具和指标，尤其是在处理真实世界机器人数据时。

**标签**: `#Machine Learning`, `#Artificial Intelligence`, `#Robotics`, `#Model Evaluation`, `#Open Source`

---

<a id="item-tech-news-8"></a>
### [国际象棋 Transformer 模型移除单个注意力头后无法找到复杂战术](https://www.reddit.com/r/MachineLearning/comments/1vmvl4w/chessformer_lens_demo_ablating_1_of_a_chess/) ⭐️ 8.0/10

一项演示揭示，在一个拥有 128 个注意力头的国际象棋 Transformer 模型中，仅移除其中一个注意力头，就会导致模型无法识别并执行复杂的“莫菲弃后”战术。这一发现强调了人工智能推理中单个组件的关键作用，为理解大型神经网络内部组件的功能角色提供了具体的见解。该实验通过 GitHub 上提供的 Notebooks 进行复现，展示了 AI 可解释性方面的重要进展。

reddit · r/MachineLearning · /u/Weird-Asparagus4136 · 8月13日 00:29

**「背景」** 莫菲的弃后是国际象棋史上著名的策略性走法，出自美国棋手保罗·莫菲于 1858 年对阵两位业余棋手的“歌剧院之战”。这一步棋因其精妙和出人意料而闻名，通常被视为国际象棋中的一个经典范例。

**「影响」** 这项研究为 AI 研究人员和开发者提供了关于 Transformer 模型内部工作原理的宝贵线索，有助于未来设计更鲁棒、更可解释的人工智能系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Opera_Game">Opera Game - Wikipedia</a></li>
<li><a href="https://www.lesswrong.com/posts/vtMCTjH76DYMjAKYu/chessformer_lens-app-demo-paul-morphy-s-opera-game-sacrifice">chessformer _ lens app demo: Paul Morphy &#x27; s Opera Game sacrifice</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#AI Interpretability`, `#Transformer Models`, `#Neural Networks`

---

<a id="item-tech-news-9"></a>
### [苹果洽谈新闻内容授权，为 Siri AI 提供实时资讯，或采用按使用量付费模式](https://9to5mac.com/2026/08/12/report-apple-seeks-publisher-deals-to-give-siri-ai-better-access-to-current-events/) ⭐️ 8.0/10

苹果公司据报正与出版商洽谈多年期内容协议，旨在为预计于 2026 年末推出的 Siri AI 提供最新的新闻和信息。消息人士透露，苹果讨论的付款方案可能基于内容使用量，而非行业常见的预付固定授权费模式，且预算可能高达九位数。此举旨在增强 Siri AI 获取时事信息的能力，并可能改变大型 AI 公司与内容提供商的合作模式。

telegram · zaihuapd · 8月13日 04:40

**「背景」** Siri 是苹果公司开发的智能语音助手，而 AI 模型通常需要大量高质量、实时的训练数据和信息来源，以提供准确和最新的响应。当前，许多大型 AI 公司通过预付固定费用来授权内容，以解决 AI 模型在获取最新信息方面的挑战。

**「影响」** 苹果提出的按使用量付费模式，可能为内容出版商提供一种新的收入来源，并促使其他 AI 公司重新评估其内容授权策略，从而影响整个 AI 内容许可市场的运作方式。

**标签**: `#Artificial Intelligence`, `#Siri`, `#Content Licensing`, `#Technology Industry`, `#AI Strategy`

---

<a id="item-tech-news-10"></a>
### [DeepSeek 发布 Harness 应用并开源 DeepSeek-V4-Pro-0813 模型权重](https://mp.weixin.qq.com/s/mANdGRI4fO_sEbC1ECEoZQ) ⭐️ 8.0/10

DeepSeek 已发布其全新的开源应用 Harness，并以 MIT 协议开放其源代码。Harness 采用“一切皆插件”的架构，将模型、工具、技能、会话、沙箱、存储、调度和 UI 等核心能力设计为可替换插件，并提供标准、PTC、极简和创造四种运行模式，由 Cordis 驱动。此外，DeepSeek-V4-Pro-0813 模型权重已在 Hugging Face 上公开可用，尽管曾短暂出现 404 错误，但随后已恢复正常访问。

telegram · zaihuapd · 8月13日 12:39

**「背景信息」** DeepSeek（深度求索）是一家中国人工智能公司，成立于 2023 年 7 月，以开发大型语言模型（LLM）而闻名，其模型通常采用开放权重并以 MIT 等开源许可发布。DeepSeek Harness 是该公司发布的一款开源应用，采用“一切皆插件”的架构，由 Cordis 驱动，旨在将模型、工具、技能等 AI 能力设计为可替换的插件。DeepSeek-V4-Pro-0813 是 DeepSeek 推出的一款大型混合专家（MoE）模型，以其 1M 的上下文窗口和高性价比而著称。

**「影响」** 开发者和研究人员现在可以利用 DeepSeek Harness 的灵活插件架构来集成 AI 能力，并直接访问 DeepSeek-V4-Pro-0813 模型权重，从而加速 AI 应用的开发与实验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_%28Company%29">DeepSeek (Company)</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>
<li><a href="https://openrouter.ai/deepseek/deepseek-v4-pro-0813">DeepSeek V4 Pro 0813 - API Pricing &amp; Benchmarks | OpenRouter</a></li>
<li><a href="https://artificialanalysis.ai/models/deepseek-v4-pro">DeepSeek V4 Pro 0813 (max) - Intelligence, Performance &amp; Price Analysis</a></li>
<li><a href="https://wccftech.com/deepseek-prices-its-new-v4-pro-0813-model-at-0-87-per-1-million-output-tokens-as-the-high-flying-chinese-ai-lab-wows-with-its-soaring-token-consumption/">DeepSeek Prices Its New V4-Pro-0813 Model At $0.87 Per 1 Million Output Tokens, As The Chinese AI Lab Comes Out Second Only To Anthropic On Token Consumption</a></li>
<li><a href="https://www.deepseek.com/harness/en/">DeepSeek Harness developer preview: Everything is a plugin</a></li>
<li><a href="https://qcode.cc/en/deepseek-harness-guide">DeepSeek Harness + Cordis (2026): Developer Preview... | QCode.cc</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Open Source`, `#Machine Learning`, `#AI Frameworks`, `#Model Release`

---