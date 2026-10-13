---
layout: default
title: "Horizon Summary: 2026-10-13 (EN)"
date: 2026-10-13
lang: en
---

> From 42 items, 10 important content pieces were selected

---

**Technology News**
1. [Looped Diffusion Transformer Achieves Efficiency with Reused Blocks and Variable Loop Depth](#item-tech-news-1) ⭐️ 9.0/10
2. [Building Modern Web Applications with C](#item-tech-news-2) ⭐️ 8.0/10
3. [Hackers Activate Automatic Defrosting in European Supermarket Fridges](#item-tech-news-3) ⭐️ 8.0/10
4. [WiFi 7 Router Repurposed as 320 Msps Software Defined Radio Receiver](#item-tech-news-4) ⭐️ 8.0/10
5. [Python 3.15 Released with Lazy Imports and New Profiler, Ending 3.10 Support](#item-tech-news-5) ⭐️ 8.0/10
6. [Mechanistic Arguments for AGI from Current AI Paradigms](#item-tech-news-6) ⭐️ 8.0/10
7. [U-Space and U-Lens: A Label-Free Method for LLM Uncertainty Quantification](#item-tech-news-7) ⭐️ 8.0/10
8. [learnc: fit the constants in existing C code to data \(9.1% smaller JPEGs, +4.9 F1 on WebRTC VAD\)](#item-tech-news-8) ⭐️ 8.0/10

**Financial News**
1. [China Reduces New Energy Vehicle Export Tax Rebate](#item-finance-news-1) ⭐️ 9.0/10
2. [税务处罚新裁量基准 11 月施行，社保欠缴最高罚 3 倍](#item-finance-news-2) ⭐️ 9.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Looped Diffusion Transformer Achieves Efficiency with Reused Blocks and Variable Loop Depth](https://www.reddit.com/r/MachineLearning/comments/1x49d61/looped_diffusion_transformer_the_same_blocks_run/) ⭐️ 9.0/10

A new &\#x27;Looped Diffusion Transformer&\#x27; architecture \(arXiv 2609.40305, published September 30\) introduces a method to reuse a shared group of transformer blocks multiple times within each denoising step, rather than simply increasing model size. This 260M parameter model, enhanced with deep supervision and self-modulating attention, reportedly outperforms models 6.5 times larger on various benchmarks while requiring 4.9 times less inference compute. A key feature is the ability to adjust loop depth at sampling time without retraining, allowing users to dynamically trade computational cost for image refinement. For instance, local testing on an M5 Pro showed image generation times ranging from 23-24 seconds at depth 1 to 43-47 seconds at depth 4, with significant visual improvements observed up to depth 3. The B/16 code and weights are MIT licensed and available on Hugging Face under sensenova.

reddit · r/MachineLearning · /u/Fit-Ant2238 · Oct 12, 18:13

**「Background」** Diffusion Transformers \(DiT\) are a class of diffusion models that integrate the transformer architecture, known for its success in natural language processing, to generate images. These models analyze the scalability of their forward pass complexity, measured in Gflops, to understand how they perform with increasing size and computational demands. DiTs have been developed to leverage the transformer&\#x27;s capabilities for scalable image generation.

**「Impact」** This novel architecture provides developers and users with a more computationally efficient and flexible approach to generative AI, enabling dynamic control over image quality versus inference time.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2212.09748">[2212.09748] Scalable Diffusion Models with Transformers</a></li>
<li><a href="https://encord.com/blog/diffusion-models-with-transformers/">Scalability of Diffusion Models with Transformer Backbone | Encord</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Diffusion Models`, `#Transformer Architecture`, `#Computational Efficiency`, `#Generative AI`

---

<a id="item-tech-news-2"></a>
### [Building Modern Web Applications with C](https://prophitt.me/writing/a-modern-web-app-in-c) ⭐️ 8.0/10

The article explores the technical feasibility and advantages of developing modern web applications using the C programming language, highlighting its potential for superior performance, resource efficiency, and enhanced security. This approach, considered novel in contemporary web development, leverages C&\#x27;s low-level control to optimize application execution and minimize resource consumption. Key technical details include the use of security mechanisms like \`pledge\` and \`chroot\` for privilege dropping, addressing common concerns in systems programming. The discussion underscores C&\#x27;s relevance for applications where foundational software engineering principles and direct hardware interaction are paramount.

hackernews · prophittcorey · Oct 12, 16:13 · [Discussion](https://news.ycombinator.com/item?id=50058528)

**「Background」** The Common Gateway Interface \(CGI\) is a standard protocol that allows web servers to execute external programs to dynamically generate web content, a common practice in the early days of the web. The article discusses building a web application using the &quot;BCHS stack,&quot; which refers to OpenBSD as the operating system, C as the programming language, httpd \(OpenBSD&\#x27;s web server\) for serving, and SQLite as the database.

**「Impact」** This exploration offers valuable insights for developers and organizations seeking highly performant, resource-efficient, and secure web solutions, particularly in systems programming and web architecture contexts where traditional C strengths can be leveraged.

**「Community Discussion」** Community members largely affirmed the article&\#x27;s points, sharing historical examples of C/FastCGI web systems that performed exceptionally well and noting Busybox&\#x27;s built-in CGI support. While some shared modern C++ WebAssembly projects or expressed a preference for stateful backends with frameworks over per-request binary execution, there was general agreement on the benefits of C for performance and security, especially with privilege-dropping techniques.

<details><summary>References</summary>
<ul>
<li><a href="https://daily.dev/posts/a-modern-web-app-in-c-vqni6kjep">A Modern Web App in C - daily.dev</a></li>
<li><a href="https://zeli.app/story/50058528">A Modern Web App in C · 153 HN comments | Zeli</a></li>

</ul>
</details>

**Tags**: `#Web Development`, `#C Programming`, `#Systems Programming`, `#Performance Optimization`, `#Security`

---

<a id="item-tech-news-3"></a>
### [Hackers Activate Automatic Defrosting in European Supermarket Fridges](https://www.tomshardware.com/tech-industry/cyber-security/unprecedented-cyberattack-cripples-supermarket-fridges-across-europe-as-hackers-activate-automatic-defrosting-delivery-and-store-prices-also-impacted-by-incident) ⭐️ 8.0/10

A cyberattack on October 12, 2026, targeted European supermarket fridges, including French chain Intermarché, by activating their automatic defrosting systems. This unprecedented incident caused significant disruption, impacting food delivery and store prices, and highlighted critical vulnerabilities in industrial control systems \(ICS\) and the broader implications of IoT security failures. The attack is suspected to have exploited vulnerabilities in older, end-of-life Danfoss refrigeration controllers, such as the SM800 and SC355, which had known Common Vulnerabilities and Exposures \(CVEs\). This incident follows a similar suspected attack on US military base freezers in August 2026.

hackernews · Zeekaas · Oct 12, 12:16 · [Discussion](https://news.ycombinator.com/item?id=50055304)

**「Background」** Industrial Control Systems \(ICS\) and Operational Technology \(OT\) manage physical processes, like refrigeration in supermarkets. These systems are increasingly connected to the internet to enable remote diagnostics, control, and efficiency monitoring, allowing for savings by reducing the need for on-site service engineers and optimizing performance across multiple locations.

**「Impact」** The cyberattack led to widespread food spoilage and supply chain disruptions for affected European supermarket chains, directly impacting product availability and increasing prices for consumers.

**「Community Discussion」** Community members highlighted the use of 15-20 year old, end-of-life Danfoss controllers with known CVEs, suggesting that budget constraints prevent necessary security upgrades. While some questioned the internet connectivity of freezers, others noted its benefits for remote diagnostics, efficiency, and even subscription-based machine functionality, with speculation linking this incident to a similar August 2026 attack on US military bases.

**Tags**: `#Cybersecurity`, `#Industrial Control Systems`, `#IoT Security`, `#Legacy Systems`, `#Operational Technology`

---

<a id="item-tech-news-4"></a>
### [WiFi 7 Router Repurposed as 320 Msps Software Defined Radio Receiver](https://github.com/h0m3us3r/w1700k-sdr) ⭐️ 8.0/10

A developer successfully repurposed a WiFi 7 router to function as a 320 Msps Software Defined Radio \(SDR\) receiver, specifically operating at 5 GHz. This project offers a novel and affordable approach to high-speed wireless signal processing, making advanced SDR capabilities more accessible to hobbyists and researchers. The implementation leverages readily available hardware to achieve high-speed data acquisition for wireless signals.

hackernews · djfergus · Oct 12, 12:41 · [Discussion](https://news.ycombinator.com/item?id=50055593)

**「Background」** A WiFi 7 router represents the latest generation of Wi-Fi technology, offering advancements over previous standards like WiFi 6 and 6E, primarily benefiting environments with many devices or high broadband speeds. Software Defined Radio \(SDR\) is a radio communication system where components traditionally implemented in analog hardware, such as mixers and filters, are instead realized through software on a computer or embedded system, allowing for flexible tuning and decoding across a wide range of frequencies.

**「Impact」** This development significantly lowers the barrier to entry for high-speed SDR capabilities, enabling hobbyists and researchers to access 320 Msps reception at 5 GHz using more affordable, repurposed consumer hardware.

**「Community Discussion」** The community expressed strong enthusiasm for this project, noting the developer&\#x27;s previous work on an ESP32 SDR and hoping for similar SDR functionality to become common in standard Wi-Fi cards. Discussions also highlighted the potential for this technique to work on devices like the Banana Pi R4 due to shared chipsets and its cost-effectiveness compared to traditional high-speed receivers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.esquire.com/lifestyle/tech/a73874164/best-wi-fi-7-routers/">The Best WiFi 7 Routers , What That Means, and Why It Even Matters</a></li>
<li><a href="https://switcheroo.co.uk/guides/wifi-7-router-2026">WiFi 7 Router : 5 Simple Checks to Avoid Overpaying</a></li>
<li><a href="https://www.vigi.com/pk/blog/731/how-fast-are-wifi-7-routers-/">How Fast are WiFi 7 Routers ? | TP-Link Pakistan</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software-defined_radio">Software-defined radio - Wikipedia</a></li>
<li><a href="https://radio-hobbyist.com/what-is-software-defined-radio/">What Is Software Defined Radio (SDR)? Real World Examples</a></li>
<li><a href="https://scienceinsights.org/what-is-software-defined-radio-and-how-does-it-work/">What Is Software Defined Radio and How Does It Work?</a></li>

</ul>
</details>

**Tags**: `#Software Defined Radio`, `#Hardware Hacking`, `#Computer Systems`, `#Wireless Communication`, `#Open Source`

---

<a id="item-tech-news-5"></a>
### [Python 3.15 Released with Lazy Imports and New Profiler, Ending 3.10 Support](https://simonwillison.net/2026/Oct/12/python-3-15/) ⭐️ 8.0/10

Python 3.15 has been released, curated by Hugo van Kemenade, introducing significant new features for developers. Key additions include explicit lazy imports \(PEP 810\) with \`lazy import\` syntax, which defers module loading until first use, directly addressing startup costs for applications with heavy dependencies. The release also brings unpacking in comprehensions \(PEP 798\) and a new low-overhead sampling profiler named Tachyon \(\`profiling.sampling\`\), complementing the renamed \`profiling.tracing\` \(formerly \`cProfile\`\). Concurrently, Python 3.10 has reached its end-of-life, prompting developers to transition to newer versions and embrace features from Python 3.11 and beyond. While Python 3.15&\#x27;s general performance is similar to 3.14, the experimental JIT showed a 1.2x speedup in a Fibonacci test.

rss · Simon Willison · Oct 12, 18:15

**「Background」** Python is a popular high-level programming language known for its readability and versatility, with new major versions released annually. These releases typically introduce new language features, performance enhancements, and updates to the language&\#x27;s support lifecycle, including the deprecation and end-of-life for older versions.

**「Impact」** Developers of open-source software and applications can now utilize explicit lazy imports to significantly reduce startup times for tools with extensive plugin ecosystems or heavy dependencies. The inclusion of a built-in sampling profiler offers a low-overhead method for deep performance analysis, potentially decreasing reliance on external profiling tools.

**Tags**: `#Python`, `#Programming Languages`, `#Software Engineering`, `#Open Source`, `#New Release`

---

<a id="item-tech-news-6"></a>
### [Mechanistic Arguments for AGI from Current AI Paradigms](https://www.reddit.com/r/MachineLearning/comments/1x4awlk/what_is_the_strongest_mechanistic_argument_that/) ⭐️ 8.0/10

A Reddit post initiates a discussion seeking the strongest mechanistic arguments, grounded in computational learning theory, information theory, and first principles, for whether the learning mechanisms underlying today&\#x27;s AI systems—specifically next token prediction combined with reinforcement learning—can produce open-ended general intelligence \(AGI\). The author emphasizes an engineering perspective, focusing on causal explanations and real-world operational effectiveness rather than philosophical debates or trend extrapolations. The core inquiry is about understanding what aspects of current systems provide a rational basis to expect general intelligence to emerge from their continued development.

reddit · r/MachineLearning · /u/Repulsive\_Twist\_9221 · Oct 12, 19:09

**「Background」** Many discussions about Artificial General Intelligence \(AGI\) often assume its eventual realization and focus on its societal implications. However, this post steps back to question the fundamental theoretical basis for such an assumption, particularly concerning the capabilities of current dominant AI architectures. Next token prediction is a core mechanism in large language models, while reinforcement learning is used to fine-tune AI behavior based on rewards.

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#AGI`, `#Computational Learning Theory`, `#AI Theory`

---

<a id="item-tech-news-7"></a>
### [U-Space and U-Lens: A Label-Free Method for LLM Uncertainty Quantification](https://www.reddit.com/r/MachineLearning/comments/1x44f9m/uspace_uncovering_when_and_why_uncertainty_arises/) ⭐️ 8.0/10

Researchers introduced U-Space and U-Lens, a novel, label-free, and efficient method for identifying and categorizing uncertainty in open-weight language models. This approach generates a confidence score by combining hidden state &quot;doubt&quot; directions with mean token entropy, outperforming costly baselines like 5-pass sampling and supervised methods in evaluations across Gemma 4, Qwen3.5, and Magistral models on four benchmarks. U-Lens provides interpretable uncertainty categories—ambiguity, missing information, conflicting evidence, or general uncertainty—and requires only a single forward pass and a pre-fitted Jacobian lens, with over 40 available on Hugging Face for various models including Gemma 2/3/4, Qwen3/3.5/3.6, Llama 3.1/3.3, gpt-oss-20b, and OLMo 3.

reddit · r/MachineLearning · /u/AdRevolutionary3242 · Oct 12, 15:10

**「Background」** The U-Space method relies on a &quot;Jacobian lens&quot; \(J-Lens\), an interpretability tool developed by Anthropic as part of their research into a &quot;global workspace&quot; within language models. A Jacobian lens functions by linearly transforming an internal activation from any layer of a language model into the final layer&\#x27;s basis, then decoding it with the model&\#x27;s unembedding to reveal what the internal activation is poised to make the model say. This allows for the interpretation of a model&\#x27;s internal states regarding its potential output. 

**「Impact」** Developers leveraging open-weight reasoning models can now integrate a low-cost, interpretable signal of model confidence, enabling more reliable LLM deployments by routing uncertain answers, triggering retrieval for missing information, or flagging conflicting evidence in RAG pipelines.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/global-workspace">A global workspace in language models \ Anthropic</a></li>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the ...</a></li>
<li><a href="https://unfinishablemap.org/research/anthropic-global-workspace-j-space-2026-07-07/">Research Notes - Anthropic&#x27;s Global Workspace / J-Space in ...</a></li>

</ul>
</details>

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#Language Models`, `#Interpretability`, `#Uncertainty Quantification`

---

<a id="item-tech-news-8"></a>
### [learnc: fit the constants in existing C code to data \(9.1% smaller JPEGs, +4.9 F1 on WebRTC VAD\)](https://www.reddit.com/r/MachineLearning/comments/1x4dlbm/learnc_fit_the_constants_in_existing_c_code_to/) ⭐️ 8.0/10

learnc is an open-source tool that automatically tunes named constants within unmodified C code by evaluating them against a user-defined C score function, then writes the optimized values back to the file. This approach yielded significant performance improvements, such as a 9.1% BD-rate reduction at equal SSIM for JPEG compression using \`stb\_image\_write.h\` \(tuned on 12 Kodak images, tested on 12 others\), outperforming \`mozjpeg\`&\#x27;s 2.7% gain. For Google&\#x27;s WebRTC Voice Activity Detection in \`vad\_core.c\`, the F1 score increased from 0.810 to 0.859 \(tuned on LibriParty dev, evaluated on LibriParty eval\). The tool is best suited for tens to hundreds of constants and has limitations, such as no JPEG gain below 1 bpp.

reddit · r/MachineLearning · /u/keep\_up\_sharma · Oct 12, 20:51

**「Background」** Optimizing C code often involves manually setting numerical constants that influence algorithm performance. \`learnc\` automates this traditionally manual or heuristic-driven process by applying a machine learning approach to find optimal constant values based on a user-defined objective function.

**「Impact」** Developers can leverage \`learnc\` to automatically enhance the performance of existing C codebases, achieving quantifiable improvements like 9.1% smaller JPEGs or a 4.9 F1 score increase in WebRTC VAD without requiring manual constant tuning.

**Tags**: `#Software Engineering`, `#Code Optimization`, `#Machine Learning`, `#Computer Systems`, `#Open Source`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China Reduces New Energy Vehicle Export Tax Rebate](https://www.news.cn/20261012/9709731f470b42f9a84825c2e4eb914b/c.html) ⭐️ 9.0/10

China&\#x27;s Ministry of Finance and State Taxation Administration announced a reduction in the VAT export tax rebate rate for new energy vehicles from 13% to 9%, effective April 1, 2027, and also canceled rebates for e-cigarette devices.

telegram · zaihuapd · Oct 12, 11:00

**「Background」** China previously offered a 13% value-added tax \(VAT\) export tax rebate on new energy vehicles, which effectively reduced the cost for exporters.

**「Impact」** Chinese new energy vehicle exporters will face higher costs due to the reduced VAT export tax rebate, which could decrease their profit margins.

<details><summary>References</summary>
<ul>
<li><a href="https://chinasourcingagent.com/sourcing-new-energy-vehicles-from-china/">Sourcing New Energy Vehicles From China : 2026 NEV Import Guide</a></li>
<li><a href="https://www.registrationchina.com/articles/china-battery-export-tax-rebates-cancellation/">China &#x27;s Battery Export Tax Rebates Cancellation in 2027: Impact on...</a></li>

</ul>
</details>

**Tags**: `#New Energy Vehicles`, `#Export Policy`, `#Taxation`, `#China Economy`, `#Automotive Industry`

---

<a id="item-finance-news-2"></a>
### [税务处罚新裁量基准 11 月施行，社保欠缴最高罚 3 倍](https://fgk.chinatax.gov.cn/zcfgk/c100012/c5252754/content.html) ⭐️ 9.0/10

China&\#x27;s State Taxation Administration announced new national administrative penalty standards, effective November 2026, imposing fines of up to three times the owed amount for employers who underpay social security contributions.

telegram · zaihuapd · Oct 13, 02:45

**Tags**: `#Taxation Policy`, `#Social Security`, `#Regulatory Change`, `#China Economy`, `#Employer Obligations`

---