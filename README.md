### Hi there, I'm Daniel Sawa 👋

BSc (Hons) Computer Science with Year in Industry student at the **University of York**. Focused on **Machine Learning (`PyTorch`)**, **Information Retrieval & Neural Ranking (`NDCG@k`, `MRR`)**, **Imperfect-Information Game Theory**, **Quantitative Research**, and high-concurrency **Rust / Python / C++** systems.

---

### 🚀 Featured Technical Projects

#### 1. [AI Poker Lab — Imperfect-Information Game Theory Solver, PyTorch Value Network & IR Drill Recommender](https://github.com/dns2jtm/aipokerlab)
- **Tech Stack:** Rust (`Rayon`, `DashMap`, `mimalloc`), Python (`PyTorch`, `NumPy`), Next.js 15, TypeScript, PostgreSQL (Prisma), Redis
- Multi-threaded **Rust 6-Max & Heads-Up Linear MCCFR solver** (`15.96M+` infosets) with Pluribus negative-regret pruning, **VR-MCCFR** control-variate baselines, and **OCHS** (8-quantile future-equity distributions clustered via L1/Earth Mover's Distance k-medians).
- **PyTorch ReBeL Belief-State Value Network (`value_net_torch.py` + `valuenet.rs`)** trained with `AdamW`, cosine annealing, and range-weighted Huber/MSE loss (exporting binary `bincode`/`VN01` weights directly into the Rust solver), paired with **Burch safety-gadget continual resolving** (cutting worst-case combo exploitation by `86.5%`) and expert-iteration distillation.
- **Information Retrieval & Offline Model Evaluation**: Hybrid lexical/telemetry **Leak-to-Drill Recommender (`DrillRecommender`)** and offline evaluation pipeline measuring **`NDCG@k`**, **`MRR`**, **`Precision@k`**, **`Recall@k`**, **Brier calibration**, and **24,000-hand statistical A/B policy evaluation** with **AIVAT** variance reduction.

#### 2. [XAU/USD Quantitative Mean-Reversion Engine](https://github.com/dns2jtm/xauusd-mean-reversion)
- **Tech Stack:** Python, Pandas, NumPy, Event-Driven Backtesting, MQL5
- Institutional-grade quantitative backtesting engine modeling multi-timeframe DeMarker oscillators across liquidity vacuums in Gold.
- Implements custom time-series resampling (6m, 12m, 20m), dynamic VWAP basket recovery algorithms, and econometric tail-risk analysis mathematically exposing negative skewness in short-volatility execution.

#### 3. [macOS Display Layout Engine](https://github.com/dns2jtm/macos-display-layout-engine)
- **Tech Stack:** Python, PyObjC (Quartz / CoreGraphics / AppKit / AXUIElement), Multi-threading
- Desktop automation daemon leveraging native macOS C-level accessibility and display APIs to calculate and tile window geometries across 3440×1440 UltraWide and Retina displays with sub-100ms response time.
- Implements asynchronous Quartz event filtering, 7+ concurrent client window tracking, and topology transforms during live monitor hotplugging.

#### 4. [Async DNS Scanner & Information Retrieval Ranking Pipeline](https://github.com/dns2jtm/async-dns-scanner)
- **Tech Stack:** Python `asyncio`, Raw UDP Sockets, RFC 1035 Wire Protocol, Information Retrieval (`TF-IDF`, `NDCG@k`, `MRR`), WHOIS (Port 43)
- High-concurrency asynchronous DNS resolution engine scanning hundreds of candidate permutations per second using non-blocking UDP socket pools.
- **Information Retrieval & Learning-to-Rank pipeline (`ranking.py` + `valuator.py`)** combining character n-gram TF-IDF cosine similarity, phonetic C-V alternation valuation, and neural feature interaction scoring, validated offline via **`NDCG@k`**, **`MRR`**, **`Precision@k`**, and **`Recall@k`**.

---

### 🛠️ Languages & Technologies
- **Languages:** Rust, Python, TypeScript, C++, JavaScript, Java, SQL, MQL5, Bash/Shell, OCaml
- **Machine Learning, IR & Quant:** PyTorch, Deep Neural Value Networks, Information Retrieval & Learning-to-Rank (`NDCG@k`, `MRR`, `Precision@k`, `TF-IDF`), Offline Evaluation & Statistical A/B Testing, Linear MCCFR, CFR+, ReBeL, NashConv, VR-MCCFR, AIVAT, Earth Mover's Distance (L1/EMD) Clustering, Event-Driven Backtesting, Tail Risk & TCA, NumPy, Pandas, SciPy
- **Full-Stack & Systems:** Rust Concurrency (`Rayon`, `DashMap`, `mimalloc`), Next.js 15, React, Node.js, Prisma, PostgreSQL, Redis, REST APIs, WebSockets, macOS Quartz/AppKit, Asyncio

---

📫 **Contact:** [dns2jtm@gmail.com](mailto:dns2jtm@gmail.com)
