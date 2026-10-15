### Hi there, I'm Daniel Sawa 👋

BSc (Hons) Computer Science with Year in Industry student at the **University of York**. Focused on quantitative systems, imperfect-information game theory, low-level macOS/POSIX systems programming, and high-concurrency architectures.

---

### 🚀 Featured Technical Projects

#### 1. [AI Poker Lab — Imperfect-Information Game Theory Solver & Training Platform](https://github.com/dns2jtm/aipokerlab)
- **Tech Stack:** Rust (`Rayon`, `DashMap`, `mimalloc`), Python (`NumPy`), Next.js 15, TypeScript, PostgreSQL (Prisma), Redis
- Multi-threaded **Rust 6-Max & Heads-Up Linear MCCFR solver** (`15.96M+` infosets) with Pluribus negative-regret pruning, **VR-MCCFR** control-variate baselines, and **OCHS** (8-quantile future-equity distributions clustered via L1/Earth Mover's Distance k-medians).
- **ReBeL-style depth-limited subgame resolving** with a trained turn belief-state value network, **Burch safety-gadget continual resolving** (bounding worst-case range-corruption exploitation to `<0.1%` of pot and cutting max combo exploitation by `86.5%`), and expert-iteration self-play distillation.
- Persistent low-latency Rust `--stdio` solver worker paired with a vectorized **Python/NumPy CFR+ restricted subgame solver** computing exact two-player **NashConv** (`solver_gap_chips`) and equity-realization matrices, powering a Next.js 15 / TypeScript / Redis platform (`<50ms` cached `spotHash` lookups, 12 leak detectors, and spaced-repetition drills).

#### 2. [XAU/USD Quantitative Mean-Reversion Engine](https://github.com/dns2jtm/xauusd-mean-reversion)
- **Tech Stack:** Python, Pandas, NumPy, Event-Driven Backtesting, MQL5
- Institutional-grade quantitative backtesting engine modeling multi-timeframe DeMarker oscillators across liquidity vacuums in Gold.
- Implements custom time-series resampling (6m, 12m, 20m), dynamic VWAP basket recovery algorithms, and econometric tail-risk analysis mathematically exposing negative skewness in short-volatility execution.

#### 3. [macOS Display Layout Engine](https://github.com/dns2jtm/macos-display-layout-engine)
- **Tech Stack:** Python, PyObjC (Quartz / CoreGraphics / AppKit / AXUIElement), Multi-threading
- Desktop automation daemon leveraging native macOS C-level accessibility and display APIs to calculate and tile window geometries across 3440×1440 UltraWide and Retina displays with sub-100ms response time.
- Implements asynchronous Quartz event filtering, 7+ concurrent client window tracking, and topology transforms during live monitor hotplugging.

#### 4. [Async DNS Scanner & Linguistic Valuator](https://github.com/dns2jtm/async-dns-scanner)
- **Tech Stack:** Python `asyncio`, Raw UDP Sockets, RFC 1035 Wire Protocol, WHOIS (Port 43)
- High-concurrency asynchronous DNS resolution engine scanning hundreds of candidate permutations per second using non-blocking UDP socket pools.
- Pure Python wire-format serializer/deserializer, phonetic pronounceability evaluator (C-V alternation algorithms), and direct port 43 WHOIS verification.

---

### 🛠️ Languages & Technologies
- **Languages:** Rust, Python, TypeScript, C++, JavaScript, Java, SQL, MQL5, Bash/Shell, OCaml
- **Quant & Game Theory:** Linear MCCFR, CFR+, ReBeL, NashConv, VR-MCCFR, AIVAT, Earth Mover's Distance (L1/EMD) Clustering, Event-Driven Backtesting, Tail Risk & Skewness Analysis, TCA, Monte Carlo, NumPy, Pandas
- **Full-Stack & Systems:** Rust Concurrency (`Rayon`, `DashMap`, `mimalloc`), Next.js 15, React, Node.js, Prisma, PostgreSQL, Redis, REST APIs, WebSockets, macOS Quartz/AppKit, Asyncio

---

📫 **Contact:** [dns2jtm@gmail.com](mailto:dns2jtm@gmail.com)
