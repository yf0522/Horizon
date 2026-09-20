---
layout: default
title: "Horizon Summary: 2026-09-20 (EN)"
date: 2026-09-20
lang: en
---

> From 29 items, 10 important content pieces were selected

---

**Technology News**
1. [ProgramAsWeights: Compile English Function Descriptions into Local Neural Programs](#item-tech-news-1) ⭐️ 8.0/10
2. [DiffusionGemma: Parallel Text Generation in PyTorch from Scratch](#item-tech-news-2) ⭐️ 8.0/10
3. [California Governor Orders Mandatory Reporting of AI Incidents](#item-tech-news-3) ⭐️ 8.0/10
4. [OpenAI Launches ChatGPT Plugin for Microsoft Word](#item-tech-news-4) ⭐️ 8.0/10
5. [AI-Generated Posters Spark Debate on Creative Limitations and Perceived Effort](#item-tech-news-5) ⭐️ 7.0/10
6. [Critiquing AI for Writing: Cognitive Pitfalls and Effective Use](#item-tech-news-6) ⭐️ 7.0/10
7. [Novel LLM Architecture Uses Hypersurfaces for Dynamic Weight Updates](#item-tech-news-7) ⭐️ 7.0/10

**Financial News**
1. [特朗普称获格陵兰安全永久控制权 丹麦称下周签署](#item-finance-news-1) ⭐️ 9.0/10
2. [AI Giants Sued Over Alleged Coordination to Slow Development](#item-finance-news-2) ⭐️ 8.0/10
3. [Chinese Regulators Investigate Online Travel Platforms](#item-finance-news-3) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [ProgramAsWeights: Compile English Function Descriptions into Local Neural Programs](https://www.reddit.com/r/MachineLearning/comments/1wl13eu/programasweights_compile_english_function/) ⭐️ 8.0/10

ProgramAsWeights \(PAW\) is an open-source research project from the University of Waterloo that compiles English descriptions of text functions into reusable neural programs for local execution, including on a CPU. This system separates compilation from inference, where a larger compiler model \(finetuned Qwen3-4B\) generates a LoRA adapter for a smaller, frozen interpreter model \(Qwen3-0.6B\) to specialize it for a given task. On the FuzzyBench dataset, PAW with the 0.6B interpreter achieves 73.4% exact-match accuracy, surpassing direct prompting of Qwen3-32B at 68.7%. An advanced &quot;Compile by Training&quot; mode further boosts semantic accuracy to 83.6% on FuzzyBench-Hard by finetuning the generated adapter for 100 steps. This approach enables efficient, private, and low-latency AI task execution without continuous external API calls.

reddit · r/MachineLearning · /u/yuntiandeng · Sep 19, 23:35

**「Background」** The core idea behind ProgramAsWeights is to separate the process of understanding a desired function \(compilation\) from its repeated execution \(inference\). This addresses scenarios where a task definition remains constant while inputs frequently change, such as classifying thousands of emails based on a single urgency definition. By training a larger model to generate task-specific weights for a smaller model, the system creates a specialized, reusable neural program.

**「Impact」** This technology allows developers and users to deploy AI-powered text functions locally on their machines, significantly reducing reliance on external APIs and improving privacy, latency, and cost efficiency for applications like email classification or data parsing. The resulting neural programs can be saved, distributed, and integrated directly into existing software, fostering a new paradigm for building AI tools.

**Tags**: `#AI Deployment`, `#Local Inference`, `#Natural Language Processing`, `#Machine Learning Research`, `#Open Source`

---

<a id="item-tech-news-2"></a>
### [DiffusionGemma: Parallel Text Generation in PyTorch from Scratch](https://www.reddit.com/r/MachineLearning/comments/1wkdnns/diffusiongemma_how_it_generates_text_in_parallel/) ⭐️ 8.0/10

The article details DiffusionGemma, demonstrating how to implement parallel text generation using diffusion models entirely from scratch in PyTorch. This technical deep-dive offers significant insights into efficient Natural Language Processing \(NLP\) model development. It specifically focuses on optimizing text generation through a parallel approach, which is crucial for improving the performance and scalability of advanced NLP systems.

reddit · r/MachineLearning · /u/Winter\_Mistake\_3185 · Sep 19, 05:41

**「Background」** Traditional Large Language Models \(LLMs\) typically generate text sequentially, token by token, a process known as autoregressive decoding. DiffusionGemma, developed by Google DeepMind, departs from this method by employing discrete diffusion to generate text. This model iteratively refines blocks of 256 tokens in parallel, thereby circumventing the sequential bottleneck inherent in conventional autoregressive LLMs and enabling significantly faster text generation.

**「Impact」** This resource directly benefits machine learning practitioners and software engineers by providing a practical implementation guide for advanced NLP techniques, enabling them to develop more efficient and optimized text generation models.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/gemma/diffusiongemma/">DiffusionGemma — Google DeepMind</a></li>
<li><a href="https://huggingface.co/google/diffusiongemma-26B-A4B-it">google/diffusiongemma-26B-A4B-it · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2608.00146">[2608.00146] DiffusionGemma Technical Report - arXiv.org</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Artificial Intelligence`, `#Natural Language Processing`, `#Diffusion Models`, `#PyTorch`

---

<a id="item-tech-news-3"></a>
### [California Governor Orders Mandatory Reporting of AI Incidents](https://finance.sina.com.cn/stock/usstock/c/2026-09-19/doc-inisisqc3124180.shtml) ⭐️ 8.0/10

California Governor Gavin Newsom signed an executive order on September 19 to bolster AI safety, proposing mandatory reporting of &\#x27;out-of-control&\#x27; AI agent incidents by companies. The order also suggests requiring advanced AI models to incorporate emergency shutdown mechanisms. Furthermore, it will convene an expert panel within two months to develop guidelines for AI safety laws and recommend regular audits of AI labs, with Newsom citing insufficient federal regulation as the impetus for California&\#x27;s action.

telegram · zaihuapd · Sep 19, 05:44

**「Context of AI Regulation」** An executive order is a directive issued by a governor that manages operations of the state government and has the force of law. California Governor Gavin Newsom issued this order, citing a perceived lack of sufficient federal regulation, to proactively address the safety and oversight of artificial intelligence within the state.

**「Impact」** Companies developing or deploying advanced AI models in California will face new requirements for reporting &\#x27;out-of-control&\#x27; incidents and potentially integrating emergency shutdown mechanisms, establishing a significant state-level regulatory precedent.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gov.ca.gov/2025/04/29/governor-newsom-deploys-first-in-the-nation-genai-technologies-to-improve-efficiency-in-state-government/">Governor Newsom deploys first-in-the-nation GenAI technologies to...</a></li>
<li><a href="https://insiderpaper.com/california-governor-newsom-ai-kill-switch/">California governor signs order to explore AI &#x27;kill switch&#x27; - Insider ...</a></li>
<li><a href="https://deadline.com/2026/09/gavin-newsom-ai-executive-order-1237107446/">Gavin Newsom Moves To Lasso AI With Oversight Executive Order</a></li>

</ul>
</details>

**Tags**: `#AI Safety`, `#AI Regulation`, `#Public Policy`, `#Artificial Intelligence`, `#Technology Industry`

---

<a id="item-tech-news-4"></a>
### [OpenAI Launches ChatGPT Plugin for Microsoft Word](https://chatgpt.com/apps/word/) ⭐️ 8.0/10

OpenAI has released an official ChatGPT plugin for Microsoft Word, integrating its AI capabilities directly into the word processing application. This plugin enables users to draft, edit, and format documents within Word, leveraging additional context from connected services such as Outlook, SharePoint, Google Workspace, and Dropbox. Available globally across all ChatGPT plans, including free, enterprise, and education versions, users can install it from the Microsoft Marketplace and log in with their ChatGPT account to enhance their document creation workflow.

telegram · zaihuapd · Sep 19, 10:21

**「Background」** ChatGPT is an advanced AI chatbot developed by OpenAI, known for its ability to generate human-like text and assist with various writing tasks. Microsoft Word is a ubiquitous word processing software, a core component of Microsoft Office, widely used for creating and editing documents across personal and professional settings. The integration of AI tools like ChatGPT into productivity applications aims to streamline and enhance user workflows by automating and assisting with content generation and refinement.

**Tags**: `#Artificial Intelligence`, `#Productivity Tools`, `#Software Integration`, `#Microsoft Word`, `#OpenAI`

---

<a id="item-tech-news-5"></a>
### [AI-Generated Posters Spark Debate on Creative Limitations and Perceived Effort](https://john.hartnup.uk/2026/06/07/ai-event-posters.html) ⭐️ 7.0/10

An exploration into AI&\#x27;s capability to generate event posters has ignited a community discussion regarding the technology&\#x27;s current creative limitations. While AI can produce designs, critics frequently identify its output as &quot;horrible&quot; due to visible flaws and a tendency towards stereotypical, surface-level associations, such as using sakura for a &quot;Japanese Minimal Poster.&quot; This often leads to a perception of &quot;low effort&quot; or &quot;blandness&quot; compared to human artistic output, exemplified by issues like deformed wireframe spheres in specific stylistic requests. However, some argue that AI can still outperform average budget-friendly freelance designers, suggesting its utility in certain contexts.

hackernews · ereiamjh · Sep 19, 09:20 · [Discussion](https://news.ycombinator.com/item?id=49764791)

**「Generative AI in Creative Design」** Generative AI refers to artificial intelligence models capable of producing new content, such as images, text, or audio, often based on patterns learned from vast datasets. In creative design, these models are used to generate visual assets like posters, logos, or illustrations. A significant ongoing debate surrounds the ethical implications of these models, particularly concerning the use of existing artistic works for training without consent and the perceived lack of originality or tendency towards stereotypical outputs in AI-generated art.

**「Impact」** The current state of AI in creative design indicates that while it can generate visual content, its struggle with originality and avoidance of stereotypes may lead to its work being perceived as uninspired or &quot;low effort&quot; by discerning audiences. This challenges its immediate widespread adoption for high-stakes creative projects requiring nuanced artistic expression.

**「Community Discussion」** Commenters largely agree that AI-generated posters often exhibit identifiable flaws and rely on stereotypical imagery, leading to a perception of &quot;low effort&quot; or &quot;blandness&quot; even in supposedly improved examples. However, a counterpoint suggests that AI can still produce better results than many budget-friendly freelance designers, highlighting a potential niche for its application.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/commentisfree/2025/may/20/ai-art-concerns-originality-connection">The trouble with AI art isn’t just lack of originality. It’s something far bigger | Eric Reinhart | The Guardian</a></li>
<li><a href="https://www.computer.org/publications/tech-news/trends/artists-mad-at-ai">AiArt: Why Some Artists Are Furious About AI-Produced Art</a></li>

</ul>
</details>

**Tags**: `#Artificial Intelligence`, `#Generative AI`, `#Creative Design`, `#AI Limitations`

---

<a id="item-tech-news-6"></a>
### [Critiquing AI for Writing: Cognitive Pitfalls and Effective Use](https://erichgrunewald.substack.com/p/why-you-should-almost-never-use-ai) ⭐️ 7.0/10

The article and its discussion critically examine the use of AI for writing, highlighting significant cognitive pitfalls such as passively accepting approximate wording rather than actively generating text. It emphasizes that while AI can be useful for personal consumption tasks like summarizing research or drafting internal reports, it often hinders effective communication when generating content for others. The discussion provides nuanced advice, suggesting AI is better suited for critiquing human-written text rather than producing substantive content directly. This approach helps users avoid the loss of subtlety and nuance that can occur with AI-generated prose. The core message is to understand AI&\#x27;s limitations and leverage its strengths judiciously in the writing process.

hackernews · erwald · Sep 19, 16:35 · [Discussion](https://news.ycombinator.com/item?id=49767937)

**「Context on AI Writing」** AI writing typically refers to the use of Large Language Models \(LLMs\) to generate text based on prompts, ranging from summaries and reports to creative content. These tools are designed to produce human-like prose, often used to assist with communication and content creation. The article critically examines the implications of relying on such AI for substantive writing, particularly when the output is intended for others to consume.

**「Impact」** Users who rely on AI for generating external communications risk obscuring their intended meaning and spending more time correcting subtle inaccuracies, ultimately diminishing the clarity and impact of their message.

**「Community Discussion」** Commenters largely agree that AI-generated text can obscure meaning and introduce subtle inaccuracies, with one user reporting significant time lost correcting AI prose that lacked nuance in a white paper summary. There is a consensus that AI is more effective for personal consumption tasks or as a critique tool for human writing, rather than for producing external communications.

<details><summary>References</summary>
<ul>
<li><a href="https://erichgrunewald.substack.com/p/why-you-should-almost-never-use-ai">Why I Think You Should Almost Never Use AI to Write Anything Substantive</a></li>
<li><a href="https://www.erichgrunewald.com/posts/why-i-think-you-should-almost-never-use-ai-to-write-anything-substantive/">Why You Should Almost Never Use AI to Write Anything Substantive</a></li>
<li><a href="https://forum.nunosempere.com/posts/stmA3cmXY8jaZahtg/why-you-should-almost-never-use-ai-to-write-anything">Why You Should Almost Never Use AI to Write Anything Substantive</a></li>

</ul>
</details>

**Tags**: `#Artificial Intelligence`, `#Large Language Models`, `#AI Application`, `#Technical Communication`, `#Cognitive Impact`

---

<a id="item-tech-news-7"></a>
### [Novel LLM Architecture Uses Hypersurfaces for Dynamic Weight Updates](https://www.reddit.com/r/MachineLearning/comments/1wksamz/experimenting_with_hypersurfaceconstrained/) ⭐️ 7.0/10

An experiment explores a novel language model architecture that dynamically updates the weights of a base decoder layer using learned hypersurfaces, inspired by Universal Transformers. This approach generates weight deltas \(ΔWl\) from hypersurface cross-sections, allowing a given weight matrix Wl to be constructed as W0 + ΔWl, with hypersurfaces defined by periodic functions like triangular waves. The goal is to significantly reduce training parameters and alleviate VRAM bottlenecks, a critical challenge in large language model development. Pre-training on a 10B-token FineWeb-Edu sample showed a three-loop-block model with triangular wave deltas and context modulation achieved 27,162,624 parameters, approximately 16% of a 169,906,944-parameter standard 24-layer transformer, while outperforming a standard unrolled baseline in loss. Although a classic 24-layer transformer still yielded the best absolute loss, the experimental model aims for &quot;good enough&quot; performance with drastically lighter hardware resources.

reddit · r/MachineLearning · /u/manila\_danimals · Sep 19, 17:34

**「Background」** The Universal Transformer is a recurrent transformer variant that repeatedly applies the same transformer block to improve parameter efficiency and enable deeper computation \(tool-1-1\). Gated Linear Attention \(GLA\) is an efficient alternative to standard attention in Transformers, often used for recurrent decoding and enhancing linear attention with gating \(tool-2-2, tool-2-3\). FineWeb-Edu is a large-scale dataset of high-quality educational web pages, filtered from the broader FineWeb dataset, comprising trillions of tokens \(tool-3-1, tool-3-2\).

**「Impact」** This experimental architecture offers a promising direction for developers to build and train language models with substantially fewer parameters, potentially easing VRAM constraints and making advanced models more accessible on resource-limited hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Universal_Transformer">Universal Transformer</a></li>
<li><a href="https://openreview.net/forum?id=AC9FsaVIpk">Gating is Weighting: Understanding Gated Linear Attention through In-context Learning | OpenReview</a></li>
<li><a href="https://sustcsonglin.github.io/assets/pdf/icml24_poster_gla.pdf">Gated Linear Attention Transformers with Hardware-Efficient Training</a></li>
<li><a href="https://hf.edwardfuchs.keenetic.pro/datasets/HuggingFaceFW/fineweb-edu?duplicate=true">HuggingFaceFW/ fineweb - edu · Datasets at Hugging Face</a></li>
<li><a href="https://www.emergentmind.com/topics/fineweb-edu-dataset">FineWeb - Edu : Quality Educational Web Data</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Neural Networks`, `#Language Models`, `#Model Architecture`, `#Parameter Efficiency`

---

## Financial News

<a id="item-finance-news-1"></a>
### [特朗普称获格陵兰安全永久控制权 丹麦称下周签署](https://mp.weixin.qq.com/s/rIUqosxjd5xwqkA-OxFvHg) ⭐️ 9.0/10

The US claims to have secured permanent security control over Greenland with plans for a large military presence, while Denmark confirms an agreement is expected to be signed next week.

telegram · zaihuapd · Sep 19, 01:18

**Tags**: `#Geopolitics`, `#Defense Policy`, `#Arctic Region`, `#International Agreements`

---

<a id="item-finance-news-2"></a>
### [AI Giants Sued Over Alleged Coordination to Slow Development](https://www.politico.com/news/2026/09/18/anthropic-openai-spacexai-google-sued-over-calls-to-pace-ai-development-01085023) ⭐️ 8.0/10

Four major AI companies—Anthropic, OpenAI, SpaceXAI, and Google—face an antitrust lawsuit in a U.S. federal court in California, alleging they illegally coordinated to slow AI development. The lawsuit, filed by consumers, claims that public statements by executives, including Anthropic CEO Dario Amodei&\#x27;s call to slow AI progress and subsequent agreement from Elon Musk, Sam Altman, and Demis Hassabis, may constitute an illegal agreement to restrict competition under Section 1 of the Sherman Act.

telegram · zaihuapd · Sep 19, 02:08

**「Background」** The Sherman Act is a U.S. antitrust law that prohibits agreements among competitors that restrain trade, such as the alleged coordination by these AI companies to slow development, to ensure free competition in commerce.

**「Impact」** Consumers who subscribe to the AI services of Anthropic, OpenAI, SpaceXAI, and Google could see changes in AI development pace if the court grants the requested injunction.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Sherman_Antitrust_Act">Sherman Antitrust Act - Wikipedia</a></li>
<li><a href="https://www.ftc.gov/advice-guidance/competition-guidance/guide-antitrust-laws/antitrust-laws">The Antitrust Laws | Federal Trade Commission</a></li>
<li><a href="https://www.law.cornell.edu/wex/sherman_antitrust_act">Sherman Antitrust Act | Wex | US Law | LII / Legal Information Institute</a></li>

</ul>
</details>

**Tags**: `#Antitrust`, `#AI Industry`, `#Legal Action`, `#Competition`

---

<a id="item-finance-news-3"></a>
### [Chinese Regulators Investigate Online Travel Platforms](https://mp.weixin.qq.com/s/FsHQ-AG2zSNSWfA2sJAXfQ) ⭐️ 8.0/10

The Beijing Market Supervision Administration has launched an investigation into Meituan, Fliggy, Tongcheng, and Tujia for alleged anti-competitive algorithmic marketing and pricing practices in their hotel accommodation businesses.

telegram · zaihuapd · Sep 19, 07:47

**「Background」** Meituan, Fliggy, Tongcheng, and Tujia are major online travel platforms in China, offering services like hotel bookings. The Beijing Market Supervision Administration, a local market regulator, is responsible for market supervision and anti-monopoly enforcement, and had previously investigated and penalized Ctrip for similar anti-monopoly issues.

**「Impact」** The investigation focuses on alleged practices such as requiring hotel merchants to offer the lowest prices across all platforms and depriving them of pricing autonomy.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meituan">Meituan - Wikipedia</a></li>
<li><a href="https://english.beijing.gov.cn/government/departments/202006/t20200622_1929912.html">Beijing Municipal Administration for Market Regulation</a></li>
<li><a href="https://www.lexology.com/library/detail.aspx?g=1e686f17-5ccc-451b-94af-442c607ab4c0">China Monthly Antitrust Update: February 2026 - Lexology</a></li>

</ul>
</details>

**Tags**: `#Regulatory Action`, `#Online Travel`, `#Anti-Monopoly`, `#China Tech`, `#Platform Economy`

---