---
layout: default
title: "Horizon Summary: 2026-10-03 (EN)"
date: 2026-10-03
lang: en
---

> From 36 items, 10 important content pieces were selected

---

**Technology News**
1. [NeurIPS 2026 Paper Addresses Topological Out-of-Domain Generalization in Dynamical Systems](#item-tech-news-1) ⭐️ 9.0/10
2. [Google Research Introduces Cogentic, a Multi-Agent AI for Mathematical Proof Discovery](#item-tech-news-2) ⭐️ 9.0/10
3. [AI Finally Beats Best Human Stratego Player, Demonstrating Efficiency in Imperfect Information Games](#item-tech-news-3) ⭐️ 8.0/10
4. [Greg Kroah-Hartman Debunks LLM Claims in Linux Kernel Security](#item-tech-news-4) ⭐️ 8.0/10
5. [The Legend of von Neumann \(1973\) PDF Highlights His Foundational Influence](#item-tech-news-5) ⭐️ 8.0/10
6. [Zig v0.17.0](#item-tech-news-6) ⭐️ 8.0/10
7. [FLEET Algorithm Enhances Generative AI with MCTS and Memory for Reward Maximization](#item-tech-news-7) ⭐️ 8.0/10

**Financial News**
1. [Traders See Low Chance of October Fed Rate Hike After Weak Jobs Report](#item-finance-news-1) ⭐️ 9.0/10
2. [Nike Reports Sales Decline and Layoff Plans](#item-finance-news-2) ⭐️ 8.0/10
3. [Wall Street Banks See Soaring Demand for AI Skills](#item-finance-news-3) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [NeurIPS 2026 Paper Addresses Topological Out-of-Domain Generalization in Dynamical Systems](https://www.reddit.com/r/MachineLearning/comments/1wvwodf/topological_outofdomain_generalization_in/) ⭐️ 9.0/10

A forthcoming NeurIPS 2026 paper introduces a novel approach to tackle topological out-of-domain generalization \(OODG\) in dynamical systems reconstruction \(DSR\) and time series forecasting \(TSF\). This research addresses the critical challenge where models must adapt to fundamental changes in system dynamics, such as transitioning from cyclic to chaotic behavior, which current state-of-the-art models struggle with. The paper identifies and fixes key failure modes in previous hierarchical DSR models using feature-splitting and physical sparsity priors. This modified approach enables the model to correctly predict bifurcations and beyond-bifurcation dynamics without explicit knowledge of control parameters during training, and it has been tested successfully with various RNNs, including shallow PLRNNs and Neural ODEs.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Oct 2, 15:25

**「Background」** Dynamical systems reconstruction \(DSR\) and time series forecasting \(TSF\) involve modeling and predicting the behavior of systems over time based on observed data. Topological out-of-domain generalization \(OODG\) refers to the particularly challenging scenario where the underlying dynamical regime of a system fundamentally changes, for instance, when a system crosses a tipping point due to a slowly varying control parameter. This differs from simpler generalization tasks that only involve new initial conditions or changing statistical properties within the same dynamical regime.

**「Impact」** The ability to predict novel dynamical regimes and bifurcations without explicit knowledge of control parameters could significantly advance applications in fields like climate science, medicine \(e.g., predicting epileptic activity or sepsis\), and other complex systems where understanding and predicting critical regime changes is vital.

**Tags**: `#Machine Learning`, `#Artificial Intelligence`, `#Time Series Forecasting`, `#Dynamical Systems`, `#Out-of-Domain Generalization`

---

<a id="item-tech-news-2"></a>
### [Google Research Introduces Cogentic, a Multi-Agent AI for Mathematical Proof Discovery](https://arxiv.org/abs/2609.40324v1) ⭐️ 9.0/10

Google Research has unveiled Cogentic, a multi-agent AI system built on the Gemini foundation model, designed for automated proof discovery. Cogentic employs a &quot;proof-verification&quot; loop where independent provers explore different directions, and a specialized component performs adversarial verification, storing confirmed results in a persistent ledger. This system has successfully generated new mathematical proofs for five open problems in fields such as online learning, auction theory, and mechanism design, all of which have been independently verified by domain experts and detailed in a companion paper.

telegram · zaihuapd · Oct 2, 12:04

**「Background」** Automated reasoning systems aim to discover and verify mathematical proofs using computational methods. Cogentic advances this field by coordinating multiple AI agents to explore complex problem spaces and validate findings, moving beyond single-agent approaches.

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#Automated Reasoning`, `#Multi-Agent Systems`, `#Mathematical Proof`

---

<a id="item-tech-news-3"></a>
### [AI Finally Beats Best Human Stratego Player, Demonstrating Efficiency in Imperfect Information Games](https://arstechnica.com/science/2026/10/ai-finally-beat-the-best-stratego-player-in-history-and-did-it-on-a-budget/) ⭐️ 8.0/10

Artificial intelligence has successfully defeated the best human Stratego player, marking a significant advancement in AI&\#x27;s capability to manage complex strategic challenges in games with imperfect information. The new algorithm demonstrated remarkable efficiency, learning significantly faster by playing approximately 34 times fewer games than prior state-of-the-art models like DeepNash, yet achieving a much stronger performance. This breakthrough highlights novel approaches in AI for handling hidden information, a long-standing hurdle in game AI research. The achievement was published in Nature and detailed in an arXiv preprint.

hackernews · PaulHoule · Oct 2, 14:11 · [Discussion](https://news.ycombinator.com/item?id=49933740)

**「Background」** Stratego is a two-player deterministic board game where the objective is to capture the opponent&\#x27;s flag. It is classified as an imperfect-information game because players do not know the identity of their opponent&\#x27;s pieces until they engage in combat, making opponent modeling and strategic planning particularly challenging for artificial intelligence. For decades, this hidden information aspect has made Stratego a significant grand challenge for AI research, with previous methods often struggling to achieve even amateur-level play.

**「Impact」** This advancement concretely improves AI&\#x27;s ability to strategize in environments with hidden information, potentially benefiting applications beyond games in fields requiring decision-making under uncertainty.

**「Community Discussion」** Community members largely agree this is a significant achievement, particularly emphasizing the algorithm&\#x27;s efficiency in learning with fewer games compared to previous models. Some users reflected on their personal experiences with Stratego, while others noted that earlier claims of AI &\#x27;mastering&\#x27; the game in 2022 were not as complete as this new development.

<details><summary>References</summary>
<ul>
<li><a href="https://project.dke.maastrichtuniversity.nl/games/files/msc/Arts_thesis.pdf">Competitive play in stratego</a></li>
<li><a href="https://wwwis.win.tue.nl/~bnaic/2009/papers/bnaic2009_paper_63.pdf">Opponent Modelling in Stratego</a></li>
<li><a href="https://arxiv.org/abs/2206.15378">[2206.15378] Mastering the Game of Stratego with Model-Free...</a></li>
<li><a href="https://www.deeplearning.ai/the-batch/deepnash-the-rl-system-that-plays-stratego-like-a-master">DeepNash , the RL System That Plays Stratego like a Master</a></li>

</ul>
</details>

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#Game AI`, `#Imperfect Information Games`, `#Computer Science`

---

<a id="item-tech-news-4"></a>
### [Greg Kroah-Hartman Debunks LLM Claims in Linux Kernel Security](https://www.youtube.com/watch?v=NnV_cWeoo5Q) ⭐️ 8.0/10

Linux kernel developer Greg Kroah-Hartman critically assessed the effectiveness of Large Language Models \(LLMs\) in identifying kernel vulnerabilities, highlighting a significant disparity between marketing claims and actual technical findings. He specifically debunked exaggerated reports, such as Anthropic&\#x27;s Mythos claiming 79 vulnerabilities, revealing that most were either unsubstantiated, already fixed, or based on unrealistic assumptions. Kroah-Hartman concluded that the actual actionable fixes from these LLM findings amounted to only &quot;one hour of kernel development,&quot; underscoring the practical limitations of current AI in security. This expert evaluation provides crucial insight into the real-world impact and technical shortcomings of LLM-based vulnerability discovery.

hackernews · usernomdeguerre · Oct 2, 02:51 · [Discussion](https://news.ycombinator.com/item?id=49929391)

**「Context」** Greg Kroah-Hartman is a prominent Linux kernel developer and maintainer for critical subsystems, making his insights on kernel security highly authoritative. The discussion centers on Large Language Models \(LLMs\) and their application in identifying software vulnerabilities, specifically referencing &quot;Mythos,&quot; an AI model from Anthropic that was widely publicized for its purported ability to autonomously discover numerous previously unknown vulnerabilities across various systems.

**「Impact」** This expert critique by a prominent Linux kernel maintainer directly challenges the credibility of current LLM-based security tools and their vendors, potentially tempering expectations and influencing future investment and adoption decisions within the cybersecurity and AI development communities.

**「Community Discussion」** Community members widely appreciated Greg Kroah-Hartman&\#x27;s candor and detailed technical breakdown, noting the &quot;dissonance&quot; between LLM vendors&\#x27; grand safety claims and the poor quality of their reported vulnerabilities. Discussions highlighted that Anthropic&\#x27;s Mythos primarily used pattern matching without proper citation of original kernel developers, though some still expressed optimism for the future potential of specialized LLMs in bug discovery.

<details><summary>References</summary>
<ul>
<li><a href="https://peoplepill.com/people/greg-kroah-hartman">Greg Kroah - Hartman Biography: Linux kernel developer</a></li>
<li><a href="https://usesthis.com/interviews/greg.kh/">Uses This / Greg Kroah - Hartman</a></li>
<li><a href="https://labs.cloudsecurityalliance.org/research/ai-vuln-discovery-containment-claude-mythos-v1-0-csa-styled/">Claude Mythos: AI Vulnerability Discovery and Containment ...</a></li>
<li><a href="https://gridthegrey.com/posts/anthropic-s-mythos-ai-model-used-to-find-exploitable-macos-kernel-vulnerability/">Mythos AI Exploits macOS Kernel Memory Corruption</a></li>

</ul>
</details>

**Tags**: `#Large Language Models`, `#Cybersecurity`, `#Linux Kernel`, `#AI Evaluation`, `#Open Source`

---

<a id="item-tech-news-5"></a>
### [The Legend of von Neumann \(1973\) PDF Highlights His Foundational Influence](https://gwern.net/doc/math/1973-halmos.pdf) ⭐️ 8.0/10

The 1973 PDF titled &quot;The Legend of von Neumann&quot; offers a historical examination of John von Neumann, a pivotal figure whose foundational contributions continue to shape modern computer science. The document highlights his critical work in computer architecture, mathematics, and theoretical computer science. His insights are fundamental to understanding contemporary software engineering, computer systems, and artificial intelligence, underscoring the enduring relevance of his early work in technological fields.

hackernews · suopspaces · Oct 2, 13:18 · [Discussion](https://news.ycombinator.com/item?id=49933235)

**「Background」** John von Neumann was a Hungarian-born American mathematician who became one of the world&\#x27;s foremost mathematicians by his mid-twenties, known for his exceptional intellectual ability and broad contributions across various scientific fields. His foundational work significantly influenced computer architecture, mathematics, theoretical computer science, and early artificial intelligence, making him a pivotal figure in 20th-century science and technology.

**「Impact」** John von Neumann&\#x27;s 1945 architecture continues to underpin modern computers, influencing software development and artificial intelligence, while his foundational ideas remain a reference point for computing education, researchers, and developers worldwide.

**「Community Discussion」** Community members widely regard John von Neumann as one of the most influential scientists of the 20th century, with some suggesting his impact surpasses even Einstein or Planck due to his fundamental contributions across numerous fields. Anecdotes, such as Edward Teller&\#x27;s observation of von Neumann conversing with a child as an equal, illustrate his unique intellect. Readers also recommend &quot;The Man from the Future&quot; by Ananyo Bhattacharya for a comprehensive biography and note his membership in &quot;The Martians,&quot; a group of prominent Hungarian scientists.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/John_von_Neumann">John von Neumann - Wikipedia</a></li>
<li><a href="https://www.britannica.com/biography/John-von-Neumann">John von Neumann | Biography , Accomplishments... | Britannica</a></li>
<li><a href="https://forva.jp/en/insights/von-neumann-ai/">From von Neumann to AI: An Engineer&#x27;s Perspective on 80 Years ...</a></li>
<li><a href="https://www.tanok-tech.com/en/blog/von-neumann-architecture-1945-blueprint-modern-computing">Von Neumann Architecture: 1945 Design Still Powers Modern C…</a></li>
<li><a href="https://blog.stacklegend.com/en/john-von-neumann-and-the-birth-of-modern-computing">John von Neumann and the Birth of Modern Computing</a></li>

</ul>
</details>

**Tags**: `#Computer History`, `#Computer Architecture`, `#Theoretical Computer Science`, `#Foundational AI`

---

<a id="item-tech-news-6"></a>
### [Zig v0.17.0](https://ziglang.org/download/0.17.0/release-notes.html) ⭐️ 8.0/10

Zig v0.17.0 marks a significant update for the systems programming language, highlighted by community discussion on its design strengths, low-level capabilities, and the innovative exploration of LLMs for bug detection.

hackernews · ErenayDev · Oct 2, 20:56 · [Discussion](https://news.ycombinator.com/item?id=49938521)

**Tags**: `#Programming Languages`, `#Systems Programming`, `#Artificial Intelligence`, `#Software Engineering`, `#Open Source`

---

<a id="item-tech-news-7"></a>
### [FLEET Algorithm Enhances Generative AI with MCTS and Memory for Reward Maximization](https://www.reddit.com/r/MachineLearning/comments/1wvs12j/adding_memory_to_search_instead_of_sampling_in/) ⭐️ 8.0/10

The new FLEET algorithm improves best-of-N generation by integrating Monte Carlo Tree Search \(MCTS\) with a vector store, making the search process aware of previous rewards instead of relying on blind sampling. It attributes external rewards to specific tokens and uses MCTS to adjust logits in subsequent runs, tracking high entropy/varentropy logits as branching points and storing normalized hidden states with reward history. Tested with Llama 3.2 3B, FLEET solved seven more tasks on GSM8K and reached the sampling baseline in half the iterations, while on LiveCodeBench v6 easy split, it increased the score from 0.59 to 0.69 and reached the baseline in 9 iterations compared to 32. The metadata store can also be preserved as a prior for other tasks or to enrich SFT/RL.

reddit · r/MachineLearning · /u/Helpful\_Minimum\_2214 · Oct 2, 12:04

**「Background」** Best-of-N \(BoN\) generation is a method in generative AI where a model produces multiple independent outputs, and the best one is selected based on an external reward metric to enhance quality and efficiency. Monte Carlo Tree Search \(MCTS\) is a heuristic tree search algorithm used for decision processes, particularly in problems with vast decision spaces, which builds a search tree through random simulations to guide optimal choices.

**「Impact」** FLEET significantly enhances the efficiency and performance of generative models in reward maximization tasks, demonstrating concrete improvements on benchmarks like GSM8K and LiveCodeBench by achieving better results with substantially fewer iterations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/best-of-n-bon">Best-of-N (BoN): Optimizing Generative Outputs</a></li>
<li><a href="https://arxiv.org/abs/2410.20290">[2410.20290] Fast Best-of-N Decoding via Speculative Rejection Learning to Choose or Choosing to Learn: Best-of-N vs ... Best of N sampling: Alternative ways to get better model ... Best of N Inference - aussieai.com Best AI for Image Generation in 2026 — Ranked by Blind Human ... Best of N sampling: Alternative ways to get better model ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Monte_Carlo_tree_search">Monte Carlo tree search - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/monte-carlo-tree-search-mcts-in-machine-learning/">Monte Carlo Tree Search (MCTS) in Machine Learning</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Generative AI`, `#Reinforcement Learning`, `#Monte Carlo Tree Search`, `#Algorithm`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Traders See Low Chance of October Fed Rate Hike After Weak Jobs Report](https://www.cnbc.com/2026/10/02/fed-rate-hike-odds-decline-after-september-jobs-report.html) ⭐️ 9.0/10

Traders now see only a 17% chance of the Federal Reserve raising interest rates by a quarter percentage point in October, according to CME&\#x27;s FedWatch tool, a significant drop from 36% a week ago.

rss · CNBC Finance · Oct 2, 13:29

**「Background」** This shift in market expectations follows a September jobs report showing the U.S. economy added only 29,000 jobs, below estimates, and August core inflation, measured by the personal consumption expenditures \(PCE\) price index, rose 3%, lighter than expected.

**Tags**: `#Federal Reserve`, `#Monetary Policy`, `#Interest Rates`, `#Economic Data`, `#Market Expectations`

---

<a id="item-finance-news-2"></a>
### [Nike Reports Sales Decline and Layoff Plans](https://www.cnbc.com/2026/10/02/stocks-making-the-biggest-moves-premarket-nike-on-semiconductor-synaptics-vylor-more.html) ⭐️ 8.0/10

Nike&\#x27;s shares fell over 10% after the company reported a 4% decline in sales for its fiscal first quarter, missing LSEG consensus revenue estimates.

rss · CNBC Finance · Oct 2, 12:03

**「Background」** The company attributed the sales decline to its China business and announced plans to lay off staff in 2027.

**「Impact」** Investors in Nike, Seagate Technology, and Western Digital are affected by company-specific news and increased market competition, while investors in ON Semiconductor, Synaptics, and Vylor are affected by acquisition and index inclusion news.

<details><summary>References</summary>
<ul>
<li><a href="https://meyka.com/blog/nike-stock-hits-13-year-low-as-q1-revenue-misses-layoffs-loom-0210/">Nike Stock Hits 13-Year Low as Q 1 Revenue Misses , Layoffs ... | Meyka</a></li>
<li><a href="https://247wallst.com/investing/2026/10/02/nike-sinks-8-as-weak-outlook-and-layoffs-follow-revenue-miss-lululemon-and-on-holding-remain-flat/">Nike Sinks 8% as Weak Outlook and Layoffs Follow Revenue Miss ...</a></li>
<li><a href="https://alphai.io/news/article/10-02/0d005218bc0878be/nikes-sales-warning-splits-analysts-on-whether-its-turnaround-is-working">Nike &#x27; s sales warning splits analysts on whether its... — AlphAI</a></li>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2lqXzRHN0VSR0VlSFVvYVh2YmZpZ0FQAQ?hl=en-US&amp;gl=US&amp;ceid=US:en">Google News - Onsemi to acquire Synaptics in $7 billion all-stock deal...</a></li>
<li><a href="https://invezz.com/news/2026/06/26/why-did-on-semiconductor-stock-plunge-19-after-its-7b-synaptics-acquisition/">Why did ON Semiconductor stock plunge 21% after its...</a></li>
<li><a href="https://www.utmel.com/blog/news/semiconductor/onsemi-synaptics-acquisition-impact-bom-risk-checklist-and-second-source-strategy-for-edge-ai-designs">onsemi Synaptics Acquisition Impact : BOM Risk Checklist... - Utmel</a></li>
<li><a href="https://finance.yahoo.com/markets/stocks/articles/seagate-western-digital-shares-fall-121819634.html?fr=sycsrp_catchall">Seagate and Western Digital shares fall on Toshiba HDD expansion</a></li>
<li><a href="https://www.morningstar.com/news/dow-jones/202610023903/western-digital-seagate-shares-fall-on-nikkei-report-of-toshiba-boosting-hard-drive-production">Western Digital, Seagate Shares Fall on Nikkei Report of ...</a></li>
<li><a href="https://coincentral.com/seagate-and-western-digital-shares-drop-after-toshiba-expansion-report/">Seagate and Western Digital Shares Drop After Toshiba ...</a></li>

</ul>
</details>

**Tags**: `#Earnings`, `#Mergers and Acquisitions`, `#Corporate Actions`, `#Market Competition`, `#Stock Performance`

---

<a id="item-finance-news-3"></a>
### [Wall Street Banks See Soaring Demand for AI Skills](https://www.cnbc.com/2026/10/02/ai-skills-most-in-demand-at-jpmorgan-chase-citigroup-capital-one.html) ⭐️ 8.0/10

Demand for AI-related job postings at major Wall Street banks, including JPMorgan Chase, Citigroup, and Capital One, surged 49% year-over-year to 139,819 listings in 2026, with &\#x27;agent orchestration&\#x27; skills jumping 1,721%, according to an analysis by enterprise hiring firm Draup.

rss · CNBC Finance · Oct 2, 11:03

**「Background」** This increase reflects banks&\#x27; shift from basic chatbots to implementing advanced AI agents that work together on complex tasks to boost productivity and automate repetitive operations.

**「Impact」** The shift is creating new, higher-paying roles for specialized AI talent, particularly &quot;forward-deployed engineers,&quot; and is expected to lead to significant workforce redeployment within the financial industry.

**Tags**: `#AI`, `#Financial Industry`, `#Job Market`, `#Technology Adoption`, `#Workforce Development`

---