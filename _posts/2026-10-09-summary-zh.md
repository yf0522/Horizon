---
layout: default
title: "Horizon Summary: 2026-10-09 (ZH)"
date: 2026-10-09
lang: zh
---

> 从 41 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [英伟达机器人世界模型论文被指存在严重代码错误，引发 ICML 评审质疑](#item-tech-news-1) ⭐️ 8.0/10
2. [Lunara：一种新型图像生成架构与训练算法](#item-tech-news-2) ⭐️ 8.0/10
3. [ThinkingBox-Bench：评估 AI 代理在有状态业务工作流中可靠性的新基准](#item-tech-news-3) ⭐️ 8.0/10

**财经新闻**
1. [After a yearslong slump, China&\#x27;s real estate market may be set for a turnaround](#item-finance-news-1) ⭐️ 9.0/10
2. [主要公司盘前动态](#item-finance-news-2) ⭐️ 8.0/10
3. [华为重回智能手机市场，电动汽车销量放缓](#item-finance-news-3) ⭐️ 8.0/10
4. [人社部就新就业形态劳动者权益保障办法征求意见](#item-finance-news-4) ⭐️ 8.0/10
5. [OpenAI 年化收入低于此前报道](#item-finance-news-5) ⭐️ 8.0/10
6. [美政府以欺诈为由暂停微软绿卡申请资格](#item-finance-news-6) ⭐️ 8.0/10
7. [SpaceX 拟收购全美低频段频谱许可证](#item-finance-news-7) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [英伟达机器人世界模型论文被指存在严重代码错误，引发 ICML 评审质疑](https://www.reddit.com/r/MachineLearning/comments/1x0i6b5/nvidias_erroneous_paper_accepted_as_icmls/) ⭐️ 8.0/10

Reddit 用户对英伟达一篇被 ICML 评为焦点论文的机器人世界模型“dreamDojo”提出质疑。该论文基于 Cosmos 2.5，利用 4.4 万小时人类数据、其他数据及 256 块 H100 GPU 进行预训练，但据称其性能仅比 Cosmos 2.5 提升约 0.5 dB PSNR，改进微乎其微。用户进一步发现其后训练代码存在错误，且 GitHub 上报告了影响预训练的多个 bug，表明该论文的预训练、后训练和评估代码可能均有缺陷，从而质疑其技术价值和 ICML 的同行评审流程。

reddit · r/MachineLearning · /u/Amazing-Fox-7295 · 10月8日 04:58

**「背景」** 机器人世界模型是一种预测环境如何响应机器人动作的系统，使机器人能够规划和推理未来结果。ICML（国际机器学习大会）是机器学习领域的重要学术会议，其“焦点论文”代表了被评审者认为具有重要意义和高质量的论文。Nvidia 的 DreamDojo 是基于其先前工作 Cosmos 2.5 构建的机器人世界模型，旨在通过大规模人类视频数据预训练来生成更准确的物理交互。

**「影响」** 这一事件对 AI/ML 研究社区的科学严谨性以及 ICML 等顶级会议的同行评审流程提出了严峻挑战，尤其是在涉及大量计算资源和高知名度机构的研究成果方面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/nvidia/DreamDojo">GitHub - NVIDIA/DreamDojo: Official Codebase for &quot;DreamDojo ...</a></li>
<li><a href="https://agihunt.info/en/p/1a119ec735a084db9318c27c854">Nvidia&#x27;s DreamDojo world model wins ICML… · AGI Hunt</a></li>
<li><a href="https://dreamdojo-world.github.io/">DreamDojo: A Generalist Robot World Model from Large-Scale ...</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#Robotics`, `#Research Ethics`, `#Nvidia`, `#ICML`

---

<a id="item-tech-news-2"></a>
### [Lunara：一种新型图像生成架构与训练算法](https://www.reddit.com/r/MachineLearning/comments/1x13zf7/moonworks_lunara_modeling_artistic_intelligence_r/) ⭐️ 8.0/10

Moonworks 推出了 Lunara，这是一种新颖的扩散混合 Transformer 架构，拥有不到 100 亿个活跃参数，并结合了 CAT 训练算法，旨在建模图像生成中的艺术智能。CAT 算法通过主动学习原则，迭代地更新训练分布，包括目标样本获取、图像优化和选择性纳入人类创作的艺术作品。在对 1,000 个共享提示和 8,000 张生成图像的评估中，Lunara 在 GPT-5.6 Sol 评估中以 8.473 的得分在美学质量方面超越了 GPT-Image-1 Mini（8.457）和 Qwen-Image（8.366），并在盲测人工评估中在美学质量、情感共鸣和内容完整性方面均获得最高平均分。该研究旨在推动图像生成领域中主动学习和混合架构的进一步发展。

reddit · r/MachineLearning · /u/paper-crow · 10月8日 21:54

**「背景信息」** 扩散模型是一种深度学习技术，自 2022 年发布以来，已成为文本到图像生成领域的主流方法，例如 Stable Diffusion 系列模型。主动学习是一种机器学习范式，通过迭代地选择最有信息量的样本进行标注和训练，以提高模型性能。GPT-Image-1 Mini 是 OpenAI 推出的一款基于 GPT-5 的多模态模型，能够从文本或图像提示生成高质量图像，而 GPT-5.6 Sol 则是一个先进的 AI 模型，常用于评估其他模型的性能。

**「影响」** Lunara 在图像生成美学质量方面取得的领先表现，有望激励研究人员在主动学习和混合架构方面进行更多探索，从而推动生成式 AI 技术的进步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://snapaistudio.com/models/gpt-image-1-mini">Try GPT Image 1 Mini (OpenAI) Online | Snap AI Studio</a></li>
<li><a href="https://minimaxi.design/models/openai-gpt-image-1-mini-text-to-image">Openai GPT Image - 1 Mini Text-to-image — Text-to-image pricing...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stable_Diffusion">Stable Diffusion - Wikipedia</a></li>
<li><a href="https://artificialanalysis.ai/articles/gpt-5-6-has-landed">GPT-5.6 benchmarks across Intelligence, Speed and Cost</a></li>
<li><a href="https://benchlm.ai/models/gpt-5-6-sol">GPT-5.6 Sol Benchmarks, Pricing &amp; Speed (October 2026)</a></li>

</ul>
</details>

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#Generative AI`, `#Diffusion Models`, `#Active Learning`

---

<a id="item-tech-news-3"></a>
### [ThinkingBox-Bench：评估 AI 代理在有状态业务工作流中可靠性的新基准](https://www.reddit.com/r/MachineLearning/comments/1x17shf/thinkingbox_solving_an_agent_task_once_vs_solving/) ⭐️ 8.0/10

微软推出了一项名为 ThinkingBox-Bench 的新基准，旨在严格评估 AI 代理在复杂、有状态的业务工作流中重复完成任务的可靠性，并确保后端数据库状态的正确性。该基准包含 5 个领域（零售、旅游/酒店、汽车保险、数字银行内部 IT、咨询 IT/HR）的 507 个策略条件业务工作流，每个任务独立运行 20 次，从相同的干净后端开始，总计每个模型 10,140 次试验。评估通过比较终端后端状态和副作用与所需最终状态来完成，并引入了\`pass@1\`（所有尝试的成功率）、\`pass@20\`（20 次尝试中至少成功一次的任务比例）和\`all-20\`（20 次尝试中每次都成功的任务比例）三个指标。研究发现，模型的“发现能力”和“重复能力”排名差异显著，例如 Kimi-K3 在\`pass@20\`上表现最佳（93.89%），但在\`all-20\`上仅为 13.41%，而 Claude Opus 5 的\`all-20\`则高达 47.53%；此外，在 121,680 次有效试验中，有 67.24%的失败虽然“干净”终止且调用了状态更改工具，但仍导致了错误的数据库状态，表明仅凭完成代理任务不足以保证正确性。

reddit · r/MachineLearning · /u/tuhin\_k · 10月9日 00:50

**「背景」** AI 代理是能够感知环境、做出决策并执行行动以实现特定目标的系统，它们在自动化业务流程中扮演着越来越重要的角色。在企业环境中，许多任务涉及修改数据库或其他系统状态的顺序操作，即所谓的“有状态工作流”。因此，评估 AI 代理不仅要看它们能否完成任务，更要关注它们在重复执行时能否始终如一地保持系统状态的正确性，这对于确保业务操作的可靠性和数据完整性至关重要。

**「影响」** ThinkingBox-Bench 为 AI 代理的开发者和组织提供了一个更严格、更贴近实际业务场景的评估工具，有助于他们构建和部署在关键企业应用中更可靠、更值得信赖的 AI 代理。

**标签**: `#Artificial Intelligence`, `#Machine Learning`, `#AI Agents`, `#Benchmarking`, `#System Reliability`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [After a yearslong slump, China&\#x27;s real estate market may be set for a turnaround](https://www.cnbc.com/2026/10/08/chinas-real-estate-market-may-be-set-for-a-turnaround-sp-says.html) ⭐️ 9.0/10

Reports from S&amp;P Global Ratings and Guotai Junan International indicate China&\#x27;s yearslong property slump may be nearing an end, driven by government policies to reduce supply and stabilize the market, with some tier-one cities already showing signs of recovery.

rss · CNBC Finance · 10月8日 09:27

**标签**: `#China Economy`, `#Real Estate`, `#Economic Policy`, `#Market Forecast`, `#S&amp;P Global Ratings`

---

<a id="item-finance-news-2"></a>
### [主要公司盘前动态](https://www.cnbc.com/2026/10/08/stocks-making-the-biggest-moves-premarket-hae-avgo-lulu-wolf.html) ⭐️ 8.0/10

Wolfspeed 获得了国防部提供的 15 亿美元有条件贷款，而全球最大的合同芯片制造商台积电报告称，9 月份营收同比增长 54.6%，第三季度营收达到 160.3 亿美元。

rss · CNBC Finance · 10月8日 12:28

**「背景」** CSL 是一家澳大利亚跨国专业生物技术公司，致力于研究、开发、制造和销售用于治疗和预防严重人类疾病的产品，并生产血浆衍生和重组治疗产品。

**「影响」** Wolfspeed 的贷款将支持美国国内生产，而 Applied Digital 的强劲增长则凸显了对人工智能基础设施的持续需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CSL_Limited">CSL Limited - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/CSL_Behring">CSL Behring - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Semiconductors`, `#AI Infrastructure`, `#Corporate Earnings`, `#Financing`, `#Market Movers`

---

<a id="item-finance-news-3"></a>
### [华为重回智能手机市场，电动汽车销量放缓](https://www.cnbc.com/2026/10/08/huawei-china-smartphone-ev-slow.html) ⭐️ 8.0/10

华为正将重心转回搭载自研芯片的智能手机业务，因其电动汽车合作伙伴的交付量在 9 月份同比下降 29%，面临显著的销售放缓。

rss · CNBC Finance · 10月8日 08:04

**「背景」** 此前，美国在 2019 年实施的限制措施导致华为消费者业务收入在 2021 年减半；同时，中国汽车市场正经历自 2021 年以来最糟糕的一年，前三季度销量下降超过 20%。

**「影响」** 受此影响，华为电动汽车合作伙伴赛力斯集团（Seres Group）在上海上市的股票今年迄今已下跌超过 60%。

**标签**: `#Huawei`, `#Smartphones`, `#Electric Vehicles`, `#China Market`, `#Corporate Strategy`

---

<a id="item-finance-news-4"></a>
### [人社部就新就业形态劳动者权益保障办法征求意见](https://mp.weixin.qq.com/s/saqkOXlhe0wX7qD83vdkRw) ⭐️ 8.0/10

China&\#x27;s Ministry of Human Resources and Social Security has released a draft policy for public comment to protect gig economy workers, addressing issues like minimum wage, rest, and algorithmic management.

telegram · zaihuapd · 10月8日 09:23

**标签**: `#Gig Economy`, `#Labor Policy`, `#Regulation`, `#China`, `#Worker Rights`

---

<a id="item-finance-news-5"></a>
### [OpenAI 年化收入低于此前报道](https://www.ft.com/content/b66a9858-f8fb-46cb-b506-44bfe26fca2a?syn-25a6b1a6=1) ⭐️ 8.0/10

投资者获得的财务文件显示，OpenAI 截至 9 月底的年化收入接近 500 亿美元，比此前广泛报道的 700 亿美元少了约 200 亿美元。

telegram · zaihuapd · 10月8日 17:22

**「背景」** 这一差异部分源于计算口径不同，例如 Anthropic 计入了通过云伙伴销售的收入，而 OpenAI 则未计入。

**「影响」** 这一消息可能削弱市场对人工智能需求增长的乐观预期。

**标签**: `#Artificial Intelligence`, `#Company Revenue`, `#Tech Industry`, `#Market Sentiment`, `#Financial Reporting`

---

<a id="item-finance-news-6"></a>
### [美政府以欺诈为由暂停微软绿卡申请资格](https://apnews.com/article/h1b-visa-program-vance-microsoft-e7b3a407f822702b269ee277d21343ea) ⭐️ 8.0/10

The Trump administration has suspended Microsoft from a foreign worker green card program, alleging fraud by replacing laid-off American workers with foreign visa holders, a claim Microsoft has not yet addressed.

telegram · zaihuapd · 10月9日 00:00

**标签**: `#Regulatory Action`, `#Corporate Governance`, `#Immigration Policy`, `#Labor Market`, `#Tech Sector`

---

<a id="item-finance-news-7"></a>
### [SpaceX 拟收购全美低频段频谱许可证](https://x.com/SpaceX/status/2108291133025698301) ⭐️ 8.0/10

SpaceX plans to acquire nationwide low-band spectrum licenses to enable Starlink Mobile to become a major US mobile operator, offering high-speed mobile broadband across the country.

telegram · zaihuapd · 10月9日 01:04

**标签**: `#Telecommunications`, `#SpaceX`, `#Starlink`, `#Spectrum`, `#Market Competition`

---