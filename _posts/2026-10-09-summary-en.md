---
layout: default
title: "Horizon Summary: 2026-10-09 (EN)"
date: 2026-10-09
lang: en
---

> From 41 items, 10 important content pieces were selected

---

**Technology News**
1. [Nvidia’s erroneous paper accepted as ICML’s spotlight](#item-tech-news-1) ⭐️ 8.0/10
2. [Moonworks Lunara Introduces Novel Diffusion Mixture Transformer for Image Generation](#item-tech-news-2) ⭐️ 8.0/10
3. [ThinkingBox-Bench: New AI Agent Benchmark for Stateful Workflow Reliability and Database Correctness](#item-tech-news-3) ⭐️ 8.0/10

**Financial News**
1. [After a yearslong slump, China&\#x27;s real estate market may be set for a turnaround](#item-finance-news-1) ⭐️ 9.0/10
2. [Wolfspeed Secures $1.5 Billion Defense Department Loan](#item-finance-news-2) ⭐️ 8.0/10
3. [Huawei Shifts Focus to Smartphones Amid EV Sales Slowdown](#item-finance-news-3) ⭐️ 8.0/10
4. [人社部就新就业形态劳动者权益保障办法征求意见](#item-finance-news-4) ⭐️ 8.0/10
5. [OpenAI&\#x27;s Annualized Revenue Lower Than Reported](#item-finance-news-5) ⭐️ 8.0/10
6. [美政府以欺诈为由暂停微软绿卡申请资格](#item-finance-news-6) ⭐️ 8.0/10
7. [SpaceX 拟收购全美低频段频谱许可证](#item-finance-news-7) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Nvidia’s erroneous paper accepted as ICML’s spotlight](https://www.reddit.com/r/MachineLearning/comments/1x0i6b5/nvidias_erroneous_paper_accepted_as_icmls/) ⭐️ 8.0/10

A Reddit user has critiqued Nvidia&\#x27;s DreamDojo paper, a robotics world model accepted as an ICML spotlight, alleging its technical merit is questionable. The paper, which builds on Cosmos 2.5 and utilized 44,000 hours of human data, hundreds of hours of other data, and 256 H100 GPUs, reportedly showed only a marginal 0.5 dB PSNR improvement over its predecessor. The critique highlights multiple critical bugs discovered in the released code for pre-training, post-training, and evaluation, suggesting the reported results are fundamentally flawed. This situation raises significant concerns regarding the scientific rigor of the research and the effectiveness of the peer-review process for high-profile publications.

reddit · r/MachineLearning · /u/Amazing-Fox-7295 · Oct 8, 04:58

**「Background」** A robotics world model is an AI system designed to learn and predict the dynamics of an environment, allowing robots to simulate outcomes and plan actions without constant real-world interaction. Nvidia&\#x27;s DreamDojo is an example of such a model, building upon their prior work, Cosmos 2.5. An ICML spotlight designation is a prestigious recognition at the International Conference on Machine Learning, highlighting papers deemed to be of high quality and significance.

**「Impact」** The allegations of fundamental code errors and marginal improvements despite massive resource investment could undermine confidence in the scientific rigor and peer-review standards within the AI/ML research community, particularly for high-profile works.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/nvidia/DreamDojo">GitHub - NVIDIA/DreamDojo: Official Codebase for &quot;DreamDojo ...</a></li>
<li><a href="https://agihunt.info/en/p/1a119ec735a084db9318c27c854">Nvidia&#x27;s DreamDojo world model wins ICML… · AGI Hunt</a></li>
<li><a href="https://dreamdojo-world.github.io/">DreamDojo: A Generalist Robot World Model from Large-Scale ...</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Robotics`, `#Research Ethics`, `#Nvidia`, `#ICML`

---

<a id="item-tech-news-2"></a>
### [Moonworks Lunara Introduces Novel Diffusion Mixture Transformer for Image Generation](https://www.reddit.com/r/MachineLearning/comments/1x13zf7/moonworks_lunara_modeling_artistic_intelligence_r/) ⭐️ 8.0/10

Moonworks has introduced Lunara, a novel Diffusion Mixture Transformer architecture with fewer than 10B active parameters, designed for image generation. It employs a CAT training algorithm that iteratively updates the training distribution through targeted sample acquisition, image refinement, and selective inclusion of human-created artwork, leveraging active learning principles and semantic variations. In evaluations using 1,000 prompts and 8,000 images against seven baselines including SD 3.5 Turbo and GPT-Image-1 Mini, Lunara achieved the highest aesthetic quality score of 8.473 under GPT-5.6 Sol evaluation. Furthermore, blinded human evaluators consistently ranked Lunara highest across aesthetic quality, emotional resonance, and content integrity, demonstrating its leading performance in artistic intelligence modeling.

reddit · r/MachineLearning · /u/paper-crow · Oct 8, 21:54

**「Background」** Diffusion models are a type of generative artificial intelligence that creates images by progressively refining random noise, a technique exemplified by models like Stable Diffusion 3.5 Turbo. Active learning is a machine learning approach where an algorithm strategically selects new data points for labeling to optimize training efficiency. Lunara&\#x27;s performance is benchmarked against models such as OpenAI&\#x27;s GPT-Image-1 Mini, with evaluations of aesthetic quality conducted by GPT-5.6 Sol, a sophisticated OpenAI model.

**「Impact」** This advancement provides a new competitive architecture and training methodology for generative AI, potentially influencing future research in active learning and mixture-based models for image generation.

<details><summary>References</summary>
<ul>
<li><a href="https://snapaistudio.com/models/gpt-image-1-mini">Try GPT Image 1 Mini (OpenAI) Online | Snap AI Studio</a></li>
<li><a href="https://toolplay.ai/tools/gpt-image-1-mini-ai-image-generator/">GPT Image 1 Mini AI Image Generator | Toolplay</a></li>
<li><a href="https://minimaxi.design/models/openai-gpt-image-1-mini-text-to-image">Openai GPT Image - 1 Mini Text-to-image — Text-to-image pricing...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stable_Diffusion">Stable Diffusion - Wikipedia</a></li>
<li><a href="https://huggingface.co/stabilityai/stable-diffusion-3.5-large-turbo/tree/main">stabilityai/stable-diffusion-3.5-large-turbo at main</a></li>
<li><a href="https://huggingface.co/city96/stable-diffusion-3.5-large-turbo-gguf/tree/main">city96/stable-diffusion-3.5-large-turbo-gguf at main</a></li>
<li><a href="https://metr.org/blog/2026-06-26-gpt-5-6-sol/">Summary of METR&#x27;s predeployment evaluation of GPT-5.6 Sol</a></li>
<li><a href="https://artificialanalysis.ai/articles/gpt-5-6-has-landed">GPT-5.6 benchmarks across Intelligence, Speed and Cost</a></li>
<li><a href="https://benchlm.ai/models/gpt-5-6-sol">GPT-5.6 Sol Benchmarks, Pricing &amp; Speed (October 2026)</a></li>

</ul>
</details>

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#Generative AI`, `#Diffusion Models`, `#Active Learning`

---

<a id="item-tech-news-3"></a>
### [ThinkingBox-Bench: New AI Agent Benchmark for Stateful Workflow Reliability and Database Correctness](https://www.reddit.com/r/MachineLearning/comments/1x17shf/thinkingbox_solving_an_agent_task_once_vs_solving/) ⭐️ 8.0/10

Microsoft researchers have introduced ThinkingBox-Bench, a new benchmark designed to rigorously evaluate AI agents on their ability to reliably complete complex, stateful business workflows and ensure correct backend database states across repeated attempts. The benchmark comprises 507 policy-conditioned workflows across five domains, with each task executed 20 times from a clean backend, totaling 10,140 trials per model, and graded by comparing the terminal backend state against the required end state. Key findings indicate that models rank differently based on discovery \(\`pass@20\`, tasks solved at least once\) versus repeatability \(\`all-20\`, tasks solved on all 20 attempts\); for instance, Kimi-K3 solved 93.89% of tasks at least once but only 13.41% on all 20, while Claude Opus 5 achieved 79.09% at least once and 47.53% on all 20. Furthermore, 67.24% of observed failures terminated cleanly without errors but still resulted in incorrect backend states, highlighting the inadequacy of proxy metrics for true reliability.

reddit · r/MachineLearning · /u/tuhin\_k · Oct 9, 00:50

**「Background」** AI agents are designed to autonomously perform multi-step tasks, often interacting with external systems and maintaining internal state. Traditional benchmarks frequently assess an agent&\#x27;s ability to complete a task once, but they often overlook the consistency of performance across multiple attempts or the correctness of the underlying system state after task completion. This gap is critical for real-world business applications where reliability and data integrity are paramount.

**「Impact」** This benchmark provides developers and organizations with a more robust and realistic method to evaluate AI agents for critical business applications, moving beyond single-shot success rates to assess true reliability and data integrity in stateful workflows. It enables a clearer understanding of an agent&\#x27;s readiness for deployment in environments where consistent, correct outcomes are essential.

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#AI Agents`, `#Benchmarking`, `#System Reliability`

---

## Financial News

<a id="item-finance-news-1"></a>
### [After a yearslong slump, China&\#x27;s real estate market may be set for a turnaround](https://www.cnbc.com/2026/10/08/chinas-real-estate-market-may-be-set-for-a-turnaround-sp-says.html) ⭐️ 9.0/10

Reports from S&amp;P Global Ratings and Guotai Junan International indicate China&\#x27;s yearslong property slump may be nearing an end, driven by government policies to reduce supply and stabilize the market, with some tier-one cities already showing signs of recovery.

rss · CNBC Finance · Oct 8, 09:27

**Tags**: `#China Economy`, `#Real Estate`, `#Economic Policy`, `#Market Forecast`, `#S&amp;P Global Ratings`

---

<a id="item-finance-news-2"></a>
### [Wolfspeed Secures $1.5 Billion Defense Department Loan](https://www.cnbc.com/2026/10/08/stocks-making-the-biggest-moves-premarket-hae-avgo-lulu-wolf.html) ⭐️ 8.0/10

Chipmaker Wolfspeed secured a conditional $1.5 billion loan, a 30-year financing commitment from the Defense Department, to support domestic production.

rss · CNBC Finance · Oct 8, 12:28

**「Background」** CSL is a multinational biotechnology company that develops and manufactures plasma-derived products, and plasmapheresis is a medical procedure that separates plasma from blood. Warrants are financial instruments that give the holder the right to buy a company&\#x27;s stock at a specific price, often used as a form of compensation or incentive. A Tier 1 hyperscaler refers to a very large cloud service provider, and the total addressable market \(TAM\) is the maximum revenue opportunity for a product or service, which for Palantir includes &quot;sovereign AI,&quot; or AI systems developed and controlled by a nation-state.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CSL_Limited">CSL Limited - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/CSL_Behring">CSL Behring - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Semiconductors`, `#AI Infrastructure`, `#Corporate Earnings`, `#Financing`, `#Market Movers`

---

<a id="item-finance-news-3"></a>
### [Huawei Shifts Focus to Smartphones Amid EV Sales Slowdown](https://www.cnbc.com/2026/10/08/huawei-china-smartphone-ev-slow.html) ⭐️ 8.0/10

Huawei is shifting its consumer business focus back to smartphones with self-developed chips, aiming to recover overseas market share, as its electric vehicle partnerships saw deliveries drop 29% year-on-year in September.

rss · CNBC Finance · Oct 8, 08:04

**「Background」** In 2019, U.S. restrictions blocked Huawei&\#x27;s access to Google&\#x27;s Android operating system and TSMC-made semiconductors, which significantly reduced its overseas smartphone sales and halved its consumer business revenue by 2021.

**「Impact」** Seres Group, which manufactures Huawei&\#x27;s Aito EV line, has seen its Shanghai-listed shares drop by more than 60% so far this year.

**Tags**: `#Huawei`, `#Smartphones`, `#Electric Vehicles`, `#China Market`, `#Corporate Strategy`

---

<a id="item-finance-news-4"></a>
### [人社部就新就业形态劳动者权益保障办法征求意见](https://mp.weixin.qq.com/s/saqkOXlhe0wX7qD83vdkRw) ⭐️ 8.0/10

China&\#x27;s Ministry of Human Resources and Social Security has released a draft policy for public comment to protect gig economy workers, addressing issues like minimum wage, rest, and algorithmic management.

telegram · zaihuapd · Oct 8, 09:23

**Tags**: `#Gig Economy`, `#Labor Policy`, `#Regulation`, `#China`, `#Worker Rights`

---

<a id="item-finance-news-5"></a>
### [OpenAI&\#x27;s Annualized Revenue Lower Than Reported](https://www.ft.com/content/b66a9858-f8fb-46cb-b506-44bfe26fca2a?syn-25a6b1a6=1) ⭐️ 8.0/10

OpenAI&\#x27;s annualized revenue was nearly $50 billion as of late September, according to financial documents obtained by investors and reported by the Financial Times, which is about $20 billion less than widely reported figures.

telegram · zaihuapd · Oct 8, 17:22

**「Background」** The discrepancy partly stems from different accounting methods, as other companies like Anthropic include revenue from sales through cloud partners, while OpenAI does not.

**「Impact」** This revised figure may temper market optimism regarding the growth of demand for artificial intelligence.

**Tags**: `#Artificial Intelligence`, `#Company Revenue`, `#Tech Industry`, `#Market Sentiment`, `#Financial Reporting`

---

<a id="item-finance-news-6"></a>
### [美政府以欺诈为由暂停微软绿卡申请资格](https://apnews.com/article/h1b-visa-program-vance-microsoft-e7b3a407f822702b269ee277d21343ea) ⭐️ 8.0/10

The Trump administration has suspended Microsoft from a foreign worker green card program, alleging fraud by replacing laid-off American workers with foreign visa holders, a claim Microsoft has not yet addressed.

telegram · zaihuapd · Oct 9, 00:00

**Tags**: `#Regulatory Action`, `#Corporate Governance`, `#Immigration Policy`, `#Labor Market`, `#Tech Sector`

---

<a id="item-finance-news-7"></a>
### [SpaceX 拟收购全美低频段频谱许可证](https://x.com/SpaceX/status/2108291133025698301) ⭐️ 8.0/10

SpaceX plans to acquire nationwide low-band spectrum licenses to enable Starlink Mobile to become a major US mobile operator, offering high-speed mobile broadband across the country.

telegram · zaihuapd · Oct 9, 01:04

**Tags**: `#Telecommunications`, `#SpaceX`, `#Starlink`, `#Spectrum`, `#Market Competition`

---