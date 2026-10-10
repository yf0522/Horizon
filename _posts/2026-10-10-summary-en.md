---
layout: default
title: "Horizon Summary: 2026-10-10 (EN)"
date: 2026-10-10
lang: en
---

> From 42 items, 10 important content pieces were selected

---

**Technology News**
1. [Cloudflare Acquires Deno, Ending Active Runtime Development After One Year](#item-tech-news-1) ⭐️ 9.0/10
2. [Telegram Desktop Vulnerability Allows One-Click Arbitrary File Theft](#item-tech-news-2) ⭐️ 9.0/10
3. [Carrier-Explode Decodes iPhone, Pixel, and Galaxy Carrier Settings](#item-tech-news-3) ⭐️ 8.0/10
4. [Matthew Green Warns AI Could Undermine Public-Key Encryption Confidence](#item-tech-news-4) ⭐️ 8.0/10
5. [Talus: 23M-parameter Diffusion Model for Game Terrain, Running in Browser on WebGPU](#item-tech-news-5) ⭐️ 8.0/10
6. [Amazon Builds 1000th Kuiper Satellite, Nears Commercial Space Internet Launch](#item-tech-news-6) ⭐️ 8.0/10
7. [JetBrains Releases Mellum2.1, an Open-Source 12B MoE Model for Coding Agents](#item-tech-news-7) ⭐️ 8.0/10

**Financial News**
1. [Telecom Stocks Fall Amid New Starlink Competition](#item-finance-news-1) ⭐️ 8.0/10
2. [SpaceX Spectrum Deal Impacts Telecom Stocks](#item-finance-news-2) ⭐️ 8.0/10
3. [Nasdaq CEO: Tokenization Could Free Billions in Capital](#item-finance-news-3) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Cloudflare Acquires Deno, Ending Active Runtime Development After One Year](https://deno.com/blog/cloudflare) ⭐️ 9.0/10

Cloudflare has acquired Deno, a prominent JavaScript/TypeScript runtime, with plans to cease active development of the Deno runtime after one year of maintenance. During this year, Cloudflare will provide monthly releases for bug fixes and security updates, but will not pursue further innovation or new features for the runtime. This acquisition effectively concludes the primary innovation and support for the Deno project, although the runtime will remain open source for community contributions.

hackernews · ilreb · Oct 9, 13:03 · [Discussion](https://news.ycombinator.com/item?id=50019911)

**「Background」** Deno is an open-source runtime for JavaScript and TypeScript, created by Ryan Dahl \(also the creator of Node.js\), designed with a focus on security and modern web standards. It aimed to address perceived shortcomings of Node.js by offering built-in TypeScript support, a secure sandbox environment, and native browser-compatible APIs.

**「Impact」** Developers and organizations currently relying on Deno for their projects will need to plan for the eventual cessation of official development and innovation, potentially requiring migration to alternative runtimes or reliance on community-driven maintenance.

**「Community Discussion」** The community expresses significant disappointment, viewing the acquisition as an &quot;acqui-hire&quot; that effectively shuts down Deno&\#x27;s development, despite the one-year support window. Many users, who favored Deno for its security and innovative approach, lament the loss of future innovation and attribute the shift to Deno&\#x27;s earlier pivot towards npm compatibility, which some felt diluted its original vision.

**Tags**: `#Software Engineering`, `#JavaScript Runtimes`, `#Open Source`, `#Cloudflare`, `#Tech Industry`

---

<a id="item-tech-news-2"></a>
### [Telegram Desktop Vulnerability Allows One-Click Arbitrary File Theft](https://telegram.me/zaihuapd/44307) ⭐️ 9.0/10

A critical vulnerability, CVE-2026-107181, has been discovered in Telegram Desktop versions below 7.2.9, enabling one-click arbitrary file theft. This flaw allows malicious tg:// links to silently exfiltrate sensitive user data, such as documents, browser sessions, SSH keys, and crypto wallets, without user confirmation. The vulnerability stems from unescaped semicolons in IPC commands within these links, which are misinterpreted as separate commands when combined with an interpret: handler. Telegram has addressed this issue in version 7.2.9, urging users to upgrade promptly, exercise caution with unusual tg:// links, and enable a local password for added security.

telegram · zaihuapd · Oct 9, 09:51

**「Background」** Inter-Process Communication \(IPC\) is a mechanism that allows different software processes to exchange data and signals. In applications like Telegram Desktop, custom URI schemes such as \`tg://\` are used to trigger specific actions via IPC. A vulnerability can occur if special characters within these URIs, like semicolons, are not properly escaped, leading to an IPC record-separator injection where malicious commands can be inserted and executed.

**「Impact」** Users of Telegram Desktop versions prior to 7.2.9 face a direct risk of having highly sensitive personal data, including SSH keys and cryptocurrency wallet information, stolen through a single malicious link click.

<details><summary>References</summary>
<ul>
<li><a href="https://securityvulnerability.io/vulnerability/CVE-2026-107181">CVE - 2026 - 107181 : IPC Record-Separation Injection Vulnerability in...</a></li>
<li><a href="https://www.rapid7.com/db/vulnerabilities/cve-2026-107181/">CVE - 2026 - 107181 : Telegram ... | Rapid7 Vulnerability Database</a></li>

</ul>
</details>

**Tags**: `#Cybersecurity`, `#Software Vulnerability`, `#Instant Messaging`, `#Data Security`, `#Computer Systems`

---

<a id="item-tech-news-3"></a>
### [Carrier-Explode Decodes iPhone, Pixel, and Galaxy Carrier Settings](https://carrierexplode.com/) ⭐️ 8.0/10

Carrier-Explode is a new side project that continuously archives and decodes carrier settings for major phone brands, including iPhone, Pixel, and Galaxy devices. This tool provides critical insights into how network operators configure and control mobile device functionality, offering explanations for common baseband configurations. While still under development with ongoing assumption checks, the project has already proven useful for enthusiast groups in understanding real-world network issues. It aims to demystify the opaque settings that dictate device behavior on various mobile networks.

hackernews · simplyalec · Oct 9, 18:10 · [Discussion](https://news.ycombinator.com/item?id=50024499)

**「Background」** Carrier settings are configuration files pushed by mobile network operators to devices, dictating how phones connect to the network, use features like 5G, and manage services such as personal hotspots. These settings are often opaque and can vary significantly between carriers and device models, influencing device functionality and user experience.

**「Impact」** This project offers a valuable resource for users and enthusiasts to understand specific carrier-imposed limitations or changes, such as the disabling of 5G Standalone mode or personal hotspot features, which are typically not transparently communicated by carriers or device manufacturers.

**「Community Discussion」** Community members highlighted the project&\#x27;s utility in understanding specific carrier actions, such as AT&amp;T/Apple&\#x27;s apparent disabling of 5G Standalone mode on some iPhone 18 Pro Max devices to address a hardware lockup issue. Users also expressed frustration over carriers disabling features like Personal Hotspot via these settings, noting the project&\#x27;s potential to shed light on such anti-user practices. The project was also praised for its global coverage, showing operators beyond just the US.

**Tags**: `#Mobile Technology`, `#Reverse Engineering`, `#Computer Systems`, `#Networking`, `#Telecommunications`

---

<a id="item-tech-news-4"></a>
### [Matthew Green Warns AI Could Undermine Public-Key Encryption Confidence](https://simonwillison.net/2026/Oct/9/matthew-green/) ⭐️ 8.0/10

Leading cryptographer Matthew Green has warned about the potential for artificial intelligence to rapidly erode confidence in existing public-key encryption algorithms, estimating a 15% chance of this occurring and a 1% chance of a &quot;Minicrypt&quot; scenario where public-key encryption is impossible. Green emphasizes a critical mismatch between the speed at which AI can produce security surprises and the significantly slower process for human beings to replace or update cryptographic standards. He stresses that recovery from such a surprise requires proactive preparation due to this speed disparity.

rss · Simon Willison · Oct 9, 15:02

**「Background」** Public-key encryption is a fundamental cryptographic system that uses a pair of keys—a public key for encryption and a private key for decryption—to secure communications and data, forming the backbone of internet security. &quot;Minicrypt&quot; refers to a hypothetical computational world, as described by Russell Impagliazzo, where public-key cryptography is computationally impossible, meaning secure communication without a shared secret key would not be feasible.

**Tags**: `#Cryptography`, `#Artificial Intelligence`, `#Cybersecurity`, `#Computer Systems`, `#Future of Tech`

---

<a id="item-tech-news-5"></a>
### [Talus: 23M-parameter Diffusion Model for Game Terrain, Running in Browser on WebGPU](https://www.reddit.com/r/MachineLearning/comments/1x1v71p/talus_a_23mparameter_diffusion_model_for_game/) ⭐️ 8.0/10

Talus is a 23M-parameter diffusion model designed to generate 64x64 game terrain heightmaps \(4 km, up to 1,200 m\), conditioned on terrain type and five measured properties like mean elevation and slope. It was efficiently trained from scratch on a single RTX 5060 \(8 GB\) in approximately 4.5 hours using 45,000 procedural maps, employing a Pixel-space U-Net and 50-step DDIM. The model&\#x27;s relative heights mechanism improved grainy plains, reducing the distance ratio from 3.98 to 1.23, and evaluation against a real-vs-real noise floor showed metric W1 at 1.51x the floor on TEST. Notably, Talus runs in a web browser via ONNX export with fp16 weights and ONNX Runtime Web on WebGPU, generating a map in about 3 seconds on an RTX 5060, with its Apache-2.0 licensed code and weights publicly available.

reddit · r/MachineLearning · /u/Old\_Cow\_6636 · Oct 9, 19:52

**「Background」** Diffusion models are a class of generative AI models that create new data, such as images or terrain maps, by iteratively denoising a random starting point. Heightmaps are grayscale images where pixel brightness represents elevation, commonly used in game development to define terrain geometry. WebGPU is a modern web standard that provides web developers with low-level access to a system&\#x27;s GPU for high-performance computations, while ONNX Runtime Web is a JavaScript library that enables running ONNX-formatted machine learning models directly in web browsers, leveraging WebGPU for accelerated inference.

**「Impact」** The ability to run Talus directly in a web browser using WebGPU, coupled with its Apache-2.0 license, significantly lowers the barrier to entry for game developers and designers to integrate AI-generated terrain into their workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://onnxruntime.ai/docs/tutorials/web/ep-webgpu.html">Using WebGPU | onnxruntime</a></li>
<li><a href="https://edgeruntimehq.pages.dev/">Edge AI Inference Leaderboard: WebGPU &amp; ONNX Runtime</a></li>
<li><a href="https://opensource.microsoft.com/blog/2024/02/29/onnx-runtime-web-unleashes-generative-ai-in-the-browser-using-webgpu/">ONNX Runtime Web unleashes generative AI in the browser using...</a></li>

</ul>
</details>

**Tags**: `#Machine Learning`, `#Diffusion Models`, `#Game Development`, `#WebGPU`, `#AI Applications`

---

<a id="item-tech-news-6"></a>
### [Amazon Builds 1000th Kuiper Satellite, Nears Commercial Space Internet Launch](https://arstechnica.com/space/2026/10/amazon-builds-1000th-satellite-is-weeks-away-from-space-internet-rollout/) ⭐️ 8.0/10

Amazon has completed its 1000th satellite for Project Kuiper, also known as Amazon Leo, at its factory in Kirkland, Washington. This milestone brings the company within weeks of launching its commercial low-Earth orbit satellite internet service. The Amazon Leo satellites are slated to launch on an upcoming re-flight mission of the Vulcan rocket, with another Vulcan rocket prepared to deploy more satellites in 2026.

telegram · zaihuapd · Oct 9, 04:30

**「Background」** Amazon&\#x27;s Project Kuiper, also known as Amazon Leo, is an initiative announced in 2019 to provide global broadband internet access through a constellation of 3,236 satellites in Low Earth Orbit \(LEO\). This project aims to deliver fast, affordable broadband to unserved and underserved communities worldwide. The Vulcan Centaur rocket is a key launch vehicle for deploying these satellites, including the initial prototype missions.

**「Impact」** Amazon&\#x27;s imminent launch of its commercial low-earth orbit internet service, supported by 1000 satellites, will intensify competition in the global satellite internet market, potentially offering a significant alternative to existing providers like Starlink for users seeking connectivity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aboutamazon.com/what-we-do/devices-services/amazon-leo">Amazon Leo</a></li>
<li><a href="https://keeptrack.space/deep-dive/amazon-vs-spacex">Amazon vs SpaceX: The Battle for the Best Satellite... - KeepTrack</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_Vulcan_launches">List of Vulcan launches - Wikipedia</a></li>
<li><a href="https://www.aboutamazon.com/news/innovation-at-amazon/amazons-project-kuiper-satellites-will-fly-on-the-new-vulcan-centaur-rocket-in-early-2023">Amazon&#x27;s Project Kuiper test satellites to fly on first Vulcan Centaur...</a></li>
<li><a href="https://www.engadget.com/amazon-prototype-project-kuiper-satellites-ula-vulcan-centaur-132457407.html">Amazon&#x27;s first Project Kuiper internet satellites will launch on Vulcan ...</a></li>
<li><a href="https://synergia.themarzipan.com/race-global-connectivity/">The Race for Global Connectivity – synergia Blog</a></li>
<li><a href="https://vocal.media/01/amazon-s-project-kuiper-your-complete-guide-to-the-future-of-satellite-internet">&quot;Amazon&#x27;s Project Kuiper : Your Complete Guide to the Future of...&quot;...</a></li>

</ul>
</details>

**Tags**: `#Satellite Internet`, `#Space Technology`, `#Amazon`, `#Computer Systems`, `#Telecommunications`

---

<a id="item-tech-news-7"></a>
### [JetBrains Releases Mellum2.1, an Open-Source 12B MoE Model for Coding Agents](https://blog.jetbrains.com/ai/2026/10/mellum2-1-gets-to-work-a-fast-open-model-for-coding-agents/) ⭐️ 8.0/10

JetBrains has released Mellum2.1, an open-source programming model featuring a 12B Mixture-of-Experts \(MoE\) architecture with 2.5B active parameters, distributed under the Apache 2.0 license. This model was trained using reinforcement learning in real environments, enabling it to explore codebases, edit files, and inspect modifications. Mellum2.1 is specifically designed for local coding agents, and its model weights are now available on Hugging Face.

telegram · zaihuapd · Oct 9, 07:30

**「Background」** A programming model in this context refers to an artificial intelligence model specifically trained to understand, generate, and manipulate code. Coding agents are autonomous AI systems that leverage such models to perform various software development tasks, from navigating codebases to making and verifying code changes.

**「Impact」** This release provides developers and organizations with a fast, open-source tool to enhance the automation of code-related tasks within their software engineering workflows.

**Tags**: `#Artificial Intelligence`, `#Software Engineering`, `#Open Source`, `#Machine Learning`, `#Coding Agents`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Telecom Stocks Fall Amid New Starlink Competition](https://www.cnbc.com/2026/10/09/stocks-making-the-biggest-moves-midday-tmus-vz-t-cci-teva.html) ⭐️ 8.0/10

Shares of T-Mobile plunged 13%, and AT&amp;T and Verizon fell 10% each, after SpaceX moved to boost its Starlink Mobile service, heightening competition concerns for legacy telecom carriers.

rss · CNBC Finance · Oct 9, 18:57

**「Background」** SpaceX&\#x27;s Starlink Mobile service provides satellite-based cellular connectivity, directly competing with traditional mobile network operators.

**「Impact」** Conversely, cellular tower companies like Crown Castle climbed 12%, while managed care provider Humana&\#x27;s shares soared 12% after its largest Medicare Advantage contract rating improved.

**Tags**: `#Telecommunications`, `#Healthcare`, `#Technology`, `#Corporate Earnings`, `#Market Analysis`

---

<a id="item-finance-news-2"></a>
### [SpaceX Spectrum Deal Impacts Telecom Stocks](https://www.cnbc.com/2026/10/09/stocks-making-the-biggest-moves-premarket-dal-spcx-tmus.html) ⭐️ 8.0/10

SpaceX shares rose 4% premarket after Grain Management announced an agreement to sell its nationwide 800 megahertz spectrum portfolio to SpaceX, a move expected to bolster Starlink Mobile&\#x27;s capabilities.

rss · CNBC Finance · Oct 9, 12:31

**「Background」** This acquisition is anticipated to increase competition for existing telecom providers, causing shares of T-Mobile, AT&amp;T, and Verizon to fall by 7%, almost 6%, and over 5% respectively in premarket trading.

**「Impact」** SpaceX&\#x27;s acquisition of 800 MHz spectrum is expected to intensify competition for major U.S. telecom carriers like T-Mobile, AT&amp;T, and Verizon, while potentially increasing demand for tower infrastructure companies.

<details><summary>References</summary>
<ul>
<li><a href="https://qz.com/spacex-starlink-mobile-spectrum-grain-management-telecom-stocks-100926">SpaceX Starlink Mobile spectrum deal hits telecom stocks</a></li>
<li><a href="https://arstechnica.com/tech-policy/2026/10/starlink-spectrum-deal-boosts-musk-plan-to-beat-att-t-mobile-and-verizon/">Starlink spectrum deal boosts Musk plan to beat AT&amp;T, T- Mobile ...</a></li>
<li><a href="https://www.androidauthority.com/spacex-starlink-mobile-8-billion-spectrum-deal-3721430/">SpaceX &#x27;s $8 billion spectrum deal takes aim at US carriers</a></li>

</ul>
</details>

**Tags**: `#Telecommunications`, `#Airline Industry`, `#Healthcare Sector`, `#Technology Stocks`, `#Corporate Earnings`

---

<a id="item-finance-news-3"></a>
### [Nasdaq CEO: Tokenization Could Free Billions in Capital](https://www.cnbc.com/2026/10/09/nasdaq-ceo-tokenization-could-unleash-billions-in-trapped-capital-.html) ⭐️ 8.0/10

Nasdaq CEO Adena Friedman stated that asset tokenization could free tens of billions of dollars in capital currently tied up as collateral across the global financial system and facilitate 24/7 trading.

rss · CNBC Finance · Oct 9, 06:30

**「Background」** Tokenization involves representing financial assets, such as stocks and bonds, as digital tokens that can be transferred using blockchain technology.

**「Impact」** This shift could expand access to capital markets for companies globally and make previously inaccessible asset classes available to more investors.

**Tags**: `#Tokenization`, `#Capital Markets`, `#Financial Technology`, `#Blockchain`, `#AI in Finance`

---