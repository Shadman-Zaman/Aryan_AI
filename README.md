# Where is AI? Everyday AI Systems Analysis

*Perspective: Computer Science & Software Engineering*

---

## 1. Content Recommendation Engine (e.g., YouTube, TikTok, Spotify)

* **What the AI does:** Predicts user engagement probability (click-through rate, watch time, repeat listens) using collaborative filtering, deep retrieval models, and multi-task neural network ranking pipelines.
* **What data it uses:** Explicit signals (likes, bookmarks, shares, skips) and implicit behavioral telemetry (dwell time, completion rate, scroll velocity, time-of-day, session sequences).
* **What business problem it solves:** User retention and inventory monetization. Minimizes search friction to maximize platform daily active users (DAU) and ad impression inventory.
* **Who benefits:** Platforms (higher ad revenue/subscription stickiness), advertisers (targeted ad placements), and creators (algorithmic distribution without upfront marketing spend).
* **What could go wrong:** Algorithmic radicalization and echo chambers; optimization loops prioritizing rage and outrage; compulsive screen-time behavior; filter bubbles reducing serendipitous discovery.

---

## 2. AI-Assisted Code Autocomplete (e.g., GitHub Copilot)

* **What the AI does:** Autocompletes functions, generates boilerplate, writes unit tests, and translates natural-language docstrings into executable source code using large language models fine-tuned on source code.
* **What data it uses:** The open editing buffer (active file, cursor position, surrounding imports), related project files via local vector search/AST analysis, and billions of lines of public repository code.
* **What business problem it solves:** Developer latency and cognitive load. Reduces time spent context-switching between the IDE and external documentation or writing repetitive boilerplate.
* **Who benefits:** Software engineers (increased coding velocity), engineering teams (faster sprint delivery), and tool vendors (developer tooling ARR).
* **What could go wrong:** Silent hallucination of insecure dependencies or deprecated APIs; propagation of unpatched security vulnerabilities (CWE/CVE patterns); subtle logic bugs bypassing casual human code review; open-source license contamination.

---

## 3. Algorithmic Routing & Dispatch (e.g., Google Maps, Uber)

* **What the AI does:** Solves dynamic vehicle routing problems (VRP) by running graph-search algorithms (Dijkstra/A*) combined with predictive machine learning models forecasting traffic speeds and demand surges.
* **What data it uses:** Real-time GPS pings from mobile devices, historical velocity datasets per road segment by hour/day, road classification maps, incident reports, and weather telemetry.
* **What business problem it solves:** Fleet dispatch latency, vehicle idle time, fuel/time inefficiency, and supply-demand imbalances in real time.
* **Who benefits:** Drivers (reduced unpaid idle miles), commuters (lower ETA variance and fuel savings), and urban logistics platforms (lower operational overhead).
* **What could go wrong:** Rerouting heavy highway traffic through narrow, residential neighborhoods; routing failures during extreme weather or unmapped hazards; algorithmic dispatch bias leading to wait-time disparities across socioeconomic zones.

---

## 4. Automated Spam & Phishing Filters (e.g., Gmail Spam Filter)

* **What the AI does:** Classifies inbound network traffic and messaging as legitimate, unsolicited bulk email (spam), or malicious phishing attacks using multimodal text classifiers, header inspection, and domain reputation scoring.
* **What data it uses:** Raw message body tokens, embedded links and URL redirect paths, DKIM/SPF/DMARC authentication records, sender IP reputations, and collective user labeling ("Report spam" / "Not spam").
* **What business problem it solves:** Network security overhead, human vulnerability to social engineering, and inbox clutter that degrades workplace productivity.
* **Who benefits:** End users (reduced fraud and identity theft exposure), enterprise IT security teams (fewer credential breaches), and email infrastructure providers.
* **What could go wrong:** False positives where critical medical, financial, or legal emails are silently quarantined; adversarial evasion where attackers use homoglyphs, zero-width characters, or prompt injection to bypass neural classifiers.
