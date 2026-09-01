---
layout: default
title: "Horizon Summary: 2026-09-01 (EN)"
date: 2026-09-01
lang: en
---

> From 45 items, 10 important content pieces were selected

---

**Technology News**
1. [Google Removes MV2 Extensions, Including UBlock Origin, from Chrome Web Store](#item-tech-news-1) ⭐️ 8.0/10
2. [Security Cameras Repurposed for Automatic Bird Identification with BirdNet-Go](#item-tech-news-2) ⭐️ 8.0/10
3. [NAT&\#x27;s Role in Internet Centralization and Personal Server Paradigm Shift](#item-tech-news-3) ⭐️ 8.0/10
4. [Introducing Wrapture: A Unified Python Library for Testing and Tracing](#item-tech-news-4) ⭐️ 8.0/10

**Financial News**
1. [El Niño Forecast to Intensify, Threatening Food and Shipping](#item-finance-news-1) ⭐️ 9.0/10
2. [Markets Boost September Rate Hike Odds After Fed Chair Warsh&\#x27;s Speech](#item-finance-news-2) ⭐️ 8.0/10
3. [Aon to Acquire USI for $17 Billion](#item-finance-news-3) ⭐️ 8.0/10
4. [China&\#x27;s Xi Embarks on Diplomatic Visits Ahead of U.S. Summit](#item-finance-news-4) ⭐️ 8.0/10
5. [Chinese Court Freezes Nexperia Assets Amid Wingtech Lawsuit](#item-finance-news-5) ⭐️ 8.0/10
6. [EU Designates ChatGPT, Reddit, and Roblox as Very Large Online Services](#item-finance-news-6) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Google Removes MV2 Extensions, Including UBlock Origin, from Chrome Web Store](https://webiterate.dev/google-removed-extensions-ublock-origin-108/) ⭐️ 8.0/10

Google has officially removed all Manifest V2 \(MV2\) extensions, including the widely used ad blocker UBlock Origin, from the Chrome Web Store. This action signifies a major policy shift in Google&\#x27;s approach to browser extension functionality and the broader ecosystem. The change directly impacts web privacy and ad blocking capabilities for millions of Chrome users, as MV2 extensions are no longer available for download or installation through the official store.

hackernews · twapi · Aug 31, 21:10 · [Discussion](https://news.ycombinator.com/item?id=49514878)

**「Background」** Manifest V2 \(MV2\) was the previous standard for Google Chrome extensions, defining their architecture, permissions, and capabilities. Google announced a transition to Manifest V3 \(MV3\), which introduces changes to how extensions can operate, particularly impacting content blockers like uBlock Origin due to more restrictive API access. This transition involves phasing out MV2 support, first from the Chrome Web Store, and subsequently from the browser itself, with Chrome versions 139, 150, and 151 progressively terminating MV2 functionality.

**「Impact」** This removal significantly curtails ad blocking and privacy enhancement options for Chrome users who relied on MV2 extensions like UBlock Origin, potentially exposing them to more intrusive or malicious advertisements.

**「Community Discussion」** Community members express significant concern over the removal, particularly regarding the increased risk of malicious ads and scams for vulnerable users, and many advocate for switching to Firefox as a direct response. Several users recall Chrome&\#x27;s past improvements to the web but now encourage others to use alternative browsers, citing Firefox&\#x27;s continued support for robust ad blockers like uBlock Origin.

<details><summary>References</summary>
<ul>
<li><a href="https://winaero.com/how-to-restore-manifest-v2-and-ublock-origin-in-google-chrome-139/">How to Restore Manifest V2 and uBlock Origin in Google Chrome ... - Winaero</a></li>
<li><a href="https://www.gblock.app/articles/chrome-151-manifest-v2-removed-ublock-origin-2026">Chrome 151 Kills Manifest V2 — uBlock Origin Is Done</a></li>
<li><a href="https://www.digitaltrends.com/computing/chrome-is-removing-the-last-workaround-keeping-popular-ad-blockers-alive/">Chrome is removing the last workaround keeping Manifest V2 ad blockers ...</a></li>

</ul>
</details>

**Tags**: `#Browser Extensions`, `#Web Privacy`, `#Ad Blocking`, `#Google Chrome`, `#Open Source`

---

<a id="item-tech-news-2"></a>
### [Security Cameras Repurposed for Automatic Bird Identification with BirdNet-Go](https://jasontucker.blog/how-i-turned-my-security-cameras-into-an-automatic-bird-identification-system-with-birdnet-go/) ⭐️ 8.0/10

A new project demonstrates how to transform standard security cameras into an automated bird identification system using AI-powered audio analysis via BirdNet-Go. This creative application leverages existing hardware to detect and classify bird species by their calls, showcasing a practical integration of machine learning with home automation. The system provides an accessible method for hobbyists and enthusiasts to monitor local bird populations without specialized equipment. This approach highlights the versatility of AI in repurposing common devices for novel environmental monitoring tasks.

hackernews · speckx · Aug 31, 16:47 · [Discussion](https://news.ycombinator.com/item?id=49511856)

**「Background」** BirdNET is an AI-powered sound identification system developed through rigorous research for bioacoustics, designed to transform raw audio into ecological data by identifying bird sounds. BirdNET-Go is a self-hosted, real-time soundscape analyzer that leverages BirdNET AI to ingest audio from soundcards or network streams, perform multi-model classification, and present detections via a web user interface, often running on a Raspberry Pi.

**「Impact」** The project demonstrates a valuable application of AI for home automation, enabling hobbyists to repurpose security cameras for automated bird identification, though some implementations encounter technical challenges with audio quality.

**「Community Discussion」** Community members confirmed successful implementations, with one user integrating BirdNet-Go with a Unifi doorbell cam via its RTSP feed and planning an e-ink display for detected birds. Challenges included poor microphone quality and low sampling rates \(e.g., Aqara cameras&\#x27; 16kHz vs. BirdNET&\#x27;s 48kHz requirement\), leading some to use external microphones with Raspberry Pi setups for improved audio. Other users built portable Birdnet-Pi systems with e-ink displays for on-the-go identification, while the Merlin Bird ID app was also praised for its effectiveness.

<details><summary>References</summary>
<ul>
<li><a href="https://birdnet.cornell.edu/">BirdNET – AI-Powered Sound ID</a></li>
<li><a href="https://github.com/BirdNET-Team/BirdNET-Analyzer">BirdNET-Analyzer - GitHub</a></li>
<li><a href="https://github.com/tphakala/birdnet-go">GitHub - tphakala/birdnet-go: Self-hosted realtime soundscape analyser ...</a></li>
<li><a href="https://github.com/tphakala/birdnet-go/wiki/BirdNET%E2%80%90Go-Guide">Home · tphakala/birdnet-go Wiki · GitHub</a></li>

</ul>
</details>

**Tags**: `#Artificial Intelligence`, `#Machine Learning`, `#Audio Processing`, `#Home Automation`, `#Open Source`

---

<a id="item-tech-news-3"></a>
### [NAT&\#x27;s Role in Internet Centralization and Personal Server Paradigm Shift](https://dreamstation.systems/personal/ntppost.html) ⭐️ 8.0/10

A Hacker News discussion critically examines how Network Address Translation \(NAT\) fundamentally reshaped internet architecture, contributing significantly to centralization and altering the paradigm of running personal servers. Rusty Russell, the implementer of Linux&\#x27;s current NAT system, detailed how his design, which optimized for multiple connections per IP by differentiating remote addresses, inadvertently made incoming traffic from different sources unroutable, effectively removing public endpoints for personal servers. This technical shift, while providing a &quot;poor man&\#x27;s firewall,&quot; eroded the ease with which individuals could host their own servers, fostering a client-server model over a peer-to-peer internet. The conversation highlights NAT as a pivotal factor in the internet&\#x27;s evolution towards its current centralized state.

hackernews · robinpie · Aug 31, 02:23 · [Discussion](https://news.ycombinator.com/item?id=49504905)

**「Background」** Network Address Translation \(NAT\) is a method of remapping one IP address space into another by modifying network address information in the IP header of packets while they are in transit. It was formally proposed in RFC 1631 in 1994 primarily to address the pressing issues of IP address depletion and scaling in routing on the internet.

**「Impact」** NAT&\#x27;s widespread implementation fundamentally altered the internet&\#x27;s architecture, making it significantly harder for individuals to host personal servers and thereby accelerating the shift towards a centralized client-server model.

**「Community Discussion」** Linux NAT implementer Rusty Russell expressed regret, acknowledging his role in creating a system that inadvertently eroded the ability to run personal servers. While some participants agreed that NAT was an early factor in &quot;killing the open Internet&quot; and normalizing the client-server model, others argued that regular NAT is acceptable if controllable, blaming poor user experience and operator laziness for port forwarding issues, and distinguishing it from the more restrictive Carrier Grade NAT \(CGNAT\).

<details><summary>References</summary>
<ul>
<li><a href="https://dreamstation.systems/personal/ntppost.html">Internet centralization and the original sin of NAT</a></li>

</ul>
</details>

**Tags**: `#Networking`, `#Internet Architecture`, `#Computer Systems`, `#Decentralization`, `#History of Technology`

---

<a id="item-tech-news-4"></a>
### [Introducing Wrapture: A Unified Python Library for Testing and Tracing](https://simonwillison.net/2026/Aug/31/introducing-wrapture/) ⭐️ 8.0/10

Graham Dumpleton, creator of the \`wrapt\` library, has released Wrapture, a new Python library that extends \`wrapt\`&\#x27;s monkeypatching concepts to provide a unified solution for both testing and tracing. Positioned as an alternative to \`unittest.mock\`, Wrapture facilitates easy wrapping of functions and methods for tracing all access or overriding return values. It includes OpenTelemetry support and offers a configuration-based mechanism for adding non-intrusive tracing to existing Python projects, despite being a very young project.

rss · Simon Willison · Aug 31, 23:59

**「Background」** \`wrapt\` is a popular Python library known for its robust decorator and monkeypatching capabilities, allowing runtime modification of code behavior. \`unittest.mock\` is a module in Python&\#x27;s standard library that provides tools for mocking and patching objects during unit tests, enabling isolation of code under test.

**「Impact」** Wrapture offers Python developers a single, non-intrusive tool for both testing \(stubbing and modifying return values\) and observability \(tracing function calls\), potentially simplifying development workflows and reducing the need for separate mocking and tracing solutions.

**Tags**: `#Software Engineering`, `#Python`, `#Testing`, `#Observability`, `#Open Source`

---

## Financial News

<a id="item-finance-news-1"></a>
### [El Niño Forecast to Intensify, Threatening Food and Shipping](https://m.thepaper.cn/newsDetail_forward_33846426) ⭐️ 9.0/10

A rapidly strengthening El Niño is projected to reach &quot;super El Niño&quot; intensity by October 2026 at the latest, with a nearly 70% chance of becoming the strongest event on record by the end of 2026. The World Food Programme warns that this could lead to 50 million more people facing severe food insecurity by the end of 2027.

telegram · zaihuapd · Aug 31, 04:01

**「Background」** El Niño is a climate pattern characterized by warmer-than-average sea surface temperatures in the central and eastern tropical Pacific Ocean, which can significantly alter global weather patterns.

**「Impact」** The intensifying El Niño is already disrupting international shipping via the Panama Canal due to water shortages and causing significant agricultural losses, such as a 60% reduction in broccoli yields in France.

**Tags**: `#Climate Risk`, `#Agricultural Commodities`, `#Supply Chain Disruption`, `#Food Prices`, `#Global Economy`

---

<a id="item-finance-news-2"></a>
### [Markets Boost September Rate Hike Odds After Fed Chair Warsh&\#x27;s Speech](https://www.cnbc.com/2026/08/31/markets-see-warsh-endorsing-a-rate-hike-in-september-not-everyone-is-convinced.html) ⭐️ 8.0/10

Following Federal Reserve Chairman Kevin Warsh&\#x27;s speech, markets increased the probability of a September interest rate hike to 66.1% on Monday, nearly double prior expectations, according to CME Group&\#x27;s FedWatch, though Treasury Secretary Scott Bessent and economists express skepticism.

rss · CNBC Finance · Aug 31, 19:38

**「Background」** The Federal Open Market Committee \(FOMC\) sets the benchmark interest rate, and before Warsh&\#x27;s remarks, markets saw little chance of a hike until December, but his &\#x27;hawkish&\#x27; comments about underlying inflation needing to improve changed this outlook.

**「Impact」** In response to the increased rate hike expectations, gold prices fell and Asian stock markets declined on Monday, as a stronger dollar reversed a previous rally in gold.

**Tags**: `#Monetary Policy`, `#Interest Rates`, `#Federal Reserve`, `#Market Expectations`, `#Inflation`

---

<a id="item-finance-news-3"></a>
### [Aon to Acquire USI for $17 Billion](https://www.cnbc.com/2026/08/31/aon-ceo-says-usi-deal-seeks-to-build-premiere-middle-market-insurance-platform.html) ⭐️ 8.0/10

Insurance broker Aon announced it will acquire rival USI Insurance Services from private equity firm KKR for $17 billion, funded by new debt, to create what CEO Greg Case calls the &quot;premier U.S. middle-market platform.&quot;

rss · CNBC Finance · Aug 31, 15:15

**「Background」** This acquisition builds on Aon&\#x27;s 2024 purchase of NFP, another insurance broker focused on the U.S. middle market, which Piper Sandler analyst Paul Newsome says offers unique growth compared to large account commercial insurance.

**「Impact」** Aon&\#x27;s shares tumbled 7% following the announcement, as the deal aims to serve 200,000 middle-market companies and their 48 million employees.

**Tags**: `#Mergers and Acquisitions`, `#Insurance Industry`, `#Corporate Strategy`, `#Financial Services`, `#Middle Market`

---

<a id="item-finance-news-4"></a>
### [China&\#x27;s Xi Embarks on Diplomatic Visits Ahead of U.S. Summit](https://www.cnbc.com/2026/08/31/china-xi-us-trump-visit-sco-brics-modi-india.html) ⭐️ 8.0/10

Chinese President Xi Jinping is undertaking rare state visits to Egypt and Kyrgyzstan, and is expected to attend the BRICS summit in India, ahead of a planned U.S. trip in late September. The U.S. previously scaled back tariffs on India to 18% from 50% in February and is negotiating a trade deal, but India faces potential 100% tariffs if the proposed Graham bill punishing Russian oil purchases passes.

rss · CNBC Finance · Aug 31, 04:57

**「Background」** Xi has sharply curtailed foreign travel in recent years, making his current busy schedule a significant indicator of his priorities, while the U.S. is monitoring these summits amid efforts to improve ties with India and China but get tougher on Russia.

**「Impact」** India&\#x27;s purchases of Russian oil, which accounted for over 50% of its crude supplies in June and July, could lead to new U.S. tariffs, affecting its trade relations and energy costs.

**Tags**: `#Geopolitics`, `#Trade Policy`, `#International Relations`, `#Tariffs`, `#Emerging Markets`

---

<a id="item-finance-news-5"></a>
### [Chinese Court Freezes Nexperia Assets Amid Wingtech Lawsuit](https://www.reuters.com/world/asia-pacific/chinese-court-freezes-dutch-chipmaker-nexperia-bvs-stakes-four-china-units-2026-08-31/) ⭐️ 8.0/10

A Chinese court froze up to 2.14 billion yuan \(approximately $300 million\) in assets of Dutch chipmaker Nexperia and its equipment subsidiary, following a lawsuit by Wingtech Technology, which is seeking 8 billion yuan in compensation. Wingtech alleges Nexperia enforced discriminatory Dutch restrictions after Wingtech lost control of Nexperia due to Dutch authorities.

telegram · zaihuapd · Aug 31, 12:26

**「Background」** Chinese company Wingtech Technology lost control of its Dutch chipmaker Nexperia after the Dutch government seized control in October 2025 due to tech security concerns.

**「Impact」** The asset freeze and substantial compensation claim have direct financial implications for Nexperia and Wingtech Technology, highlighting the material consequences of the ongoing legal dispute in the semiconductor sector.

<details><summary>References</summary>
<ul>
<li><a href="https://dutchtimes.nl/news/netherlands/dutch-government-seizes-control-of-nexperia-amid-rising-tech-tensions-with-china/">Dutch Government Seizes Control of Nexperia Amid Rising Tech ...</a></li>

</ul>
</details>

**Tags**: `#Semiconductor Industry`, `#Legal Dispute`, `#Asset Freeze`, `#Cross-border Investment`, `#China`

---

<a id="item-finance-news-6"></a>
### [EU Designates ChatGPT, Reddit, and Roblox as Very Large Online Services](https://www.euronews.com/next/2026/08/31/eu-places-chatgpt-reddit-and-roblox-under-strictest-digital-safety-rules) ⭐️ 8.0/10

The European Commission designated ChatGPT as a Very Large Online Search Engine and Reddit and Roblox as Very Large Online Platforms under the Digital Services Act on August 31, due to each having over 45 million monthly active users in the EU. These services will face stricter digital regulations, including annual risk assessments and independent audits, after a four-month transition period.

telegram · zaihuapd · Aug 31, 14:39

**「Background」** The Digital Services Act \(DSA\) is an EU regulation that entered into force in 2022, establishing a legal framework for digital services accountability, content moderation, and platform transparency across the European Union. It imposes the most stringent requirements on Very Large Online Platforms and Search Engines \(VLOPs/VLOSEs\) that have over 45 million monthly active users in the EU.

**「Impact」** The designation means OpenAI \(for ChatGPT\), Reddit, and Roblox will face increased compliance burdens and operational changes to meet the EU&\#x27;s stricter digital safety rules, including annual risk assessments and independent audits.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EU_Digital_Services_Act">EU Digital Services Act</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_Services_Act">Digital Services Act - Wikipedia</a></li>
<li><a href="https://digital-strategy.ec.europa.eu/en/news/commission-designates-chatgpt-reddit-roblox-under-digital-services-act">Commission designates ChatGPT, Reddit, Roblox under Digital Services Act | Shaping Europe’s digital future</a></li>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/986682/openai-chatgpt-eu-dsa">ChatGPT to face tougher regulation in the EU | The Verge</a></li>
<li><a href="https://www.euronews.com/next/2026/08/31/eu-places-chatgpt-reddit-and-roblox-under-strictest-digital-safety-rules">EU places ChatGPT, Reddit and Roblox under strictest digital safety rules | Euronews</a></li>

</ul>
</details>

**Tags**: `#EU Regulation`, `#Digital Services Act`, `#Tech Industry`, `#Online Platforms`, `#Policy Change`

---