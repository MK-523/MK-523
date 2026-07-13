# Mahesh Karthikeyan

## 🧵 I turn traces into decisions.

**UCLA Computer Science · systems/performance research · software + ML engineering · competitive chess**

I like systems that are difficult for different reasons: JVMs warming up under bursty load, risk engines whose decisions must be inspectable, and chess positions where one quiet move changes everything. My process stays the same—observe the system, isolate the decision, measure what changed, and ship something another person can actually use.

[LinkedIn](https://www.linkedin.com/in/mnkarthikeyan/) · [Portfolio](https://mk-523.github.io/) · [Email](mailto:mahesh523k@gmail.com) · [ChessStalker](https://chessstalker.com/)

---

## 🛰️ Current signal

- **At Flex:** helping build Python and TypeScript services for underwriting and risk decisioning, plus ReactFlow tools that make calculation paths reviewable in minutes instead of long walkthroughs.
- **At UCLA's Programmable Software Systems Lab:** studying JVM warmup, reusable compilation artifacts, and cache behavior in bursty serverless workloads.
- **Across my own projects:** exploring how game histories, model outputs, and complex rules become useful interfaces—not just backend results.

```text
runtime systems   → preserve useful work across ephemeral compute
decision tools    → make every input, rule, and output inspectable
chess analytics   → turn game history into opponent preparation
human-facing ML   → design for uncertainty, safety, and access
```

---

## 🧪 Systems from the notebook

### 01 / ♞ ChessStalker — preparation as a data product

**Question:** What if opponent preparation behaved like a query engine instead of a pile of games?

ChessStalker turns Lichess, Chess.com, and FIDE histories into opening, weakness, time-pressure, and playing-style reports. I helped build opening-tree analytics, Stockfish-backed workflows, and rating-conditioned Monte Carlo simulations for matchup-specific preparation.

**In the wild:** ChessStalker was featured throughout a [29-minute video on GM Hikaru Nakamura's official channel](https://www.youtube.com/watch?v=lHFyIkjdGf0).

[Use ChessStalker](https://chessstalker.com/) · [Read the case study](CHESSSTALKER_CASE_STUDY.md) · [Open a live Hikaru report](https://chessstalker.com/chesscom/hikaru)

### 02 / ⏱️ JVM + OpenFaaS — the first request matters

**Question:** Can a short-lived JVM function preserve useful work instead of paying the full warmup cost again?

At UCLA's Programmable Software Systems Lab, I build reproducible Linux, Docker, Kubernetes, OpenFaaS, and Redis experiments that separate container startup, JVM warmup, compilation, and cache-reuse costs. The public workspace packages the harness, lifecycle checks, recorded outputs, and portability validation.

**Measured in controlled experiments:** first-request latency moved from **337 ms to 125 ms**, while startup compile/load time improved by **31.6×**.

[Open the benchmark workspace](https://github.com/MK-523/hivejit-openfaas)

### 03 / 🦯 A-Eye — perception needs a safety margin

**Question:** How should a navigation assistant speak when its perception is uncertain?

A-Eye combines real-time visual perception, route state, and speech for blind and low-vision navigation. I helped develop its conservative decision layer: severity-aware alerts, repeat suppression, stale-state handling, low-confidence fallbacks, and explicit human confirmation around street crossing.

**Recognition:** winner of **MLH Best Use of ElevenLabs at LA Hacks 2026**.

[Code](https://github.com/AK20202007/A-Eye) · [Merged decision layer](https://github.com/AK20202007/A-Eye/pull/2) · [Demo](https://www.youtube.com/watch?v=m7Ee3nlPFwQ) · [Devpost](https://devpost.com/software/a-eye-pk9sdw)

<details>
<summary><strong>🗃️ Open the lab drawer: music, publishing, and chess</strong></summary>

### 🎼 Music-emotion and accessibility research

I proposed and led an independent music/NLP project with periodic Stanford mentor guidance, then rebuilt it as an offline-first toolkit for multi-emotion analysis, structured reports, tokenizer-aware aggregation, and accessible notation.

[Methodology](https://github.com/MK-523/NLP-music-sentimentanalysis/blob/c8bf706441a6ea837f1332097350314888dcf663/docs/METHODOLOGY.md) · [Reporting pipeline](https://github.com/MK-523/NLP-music-sentimentanalysis/blob/c8bf706441a6ea837f1332097350314888dcf663/music_emotion/report.py) · [Tests](https://github.com/MK-523/NLP-music-sentimentanalysis/blob/c8bf706441a6ea837f1332097350314888dcf663/tests/test_pipeline.py)

### 📚 ChessLife archive tools

A public, scaled-down reconstruction of publication-search work from my US Chess internship: portable SQL metadata, browser search, and a lightweight recommendation layer.

[Browse the demo repository](https://github.com/MK-523/uschess-webdemo)

### ♟️ ChessLux

An offline-first React Native chess companion with legal local play, 5,000 validated tactics, forgiving PGN review, and browser-based Stockfish analysis across web, iOS, and Android.

[Explore ChessLux](https://github.com/MK-523/chesslux)

</details>

---

## 🧾 Proof ledger

| Signal | What it represents |
|---|---|
| **337 ms → 125 ms** | First-request latency in controlled JVM serverless experiments |
| **31.6×** | Startup compile/load improvement in the same research setting |
| **30–60 min → under 5 min** | Internal review walkthroughs after helping build traceable decision tooling at Flex |
| **687,000 addresses · 15 states** | Dataset scale in [ACM SIGCOMM '24 research](https://arxiv.org/abs/2405.18657) I contributed to at UC Santa Barbara |
| **250,000+ monthly readers** | Audience served by Chess Life web properties I contributed to at US Chess |

---

## 🗺️ Field log

**2026 · Flex**  
Software/ML engineering for underwriting, risk decisioning, and decision-observability tools.

**2025–present · UCLA Programmable Software Systems Lab**  
JVM serverless runtime performance, JIT warmup, tracing, and reusable compilation artifacts.

**2023–2024 · US Chess**  
Searchable publication archives and web tooling for Chess Life.

**2022–2025 · UC Santa Barbara**  
Internet serviceability and bitrate analysis contributing to ACM SIGCOMM '24 research.

---

## 🎛️ Instruments on the bench

- **When latency matters:** `Linux` `Docker` `Kubernetes` `OpenFaaS` `Redis` `gdb` `runtime tracing`
- **When decisions must be inspectable:** `Python` `TypeScript` `SQL` `React` `typed rule systems` `reproducible benchmarks`
- **When models meet users:** `PyTorch` `JAX` `transformer pipelines` `NLTK` `Monte Carlo` `evaluation harnesses`
- **When the language shapes the system:** `C++` `Java` `Rust` `OCaml` `Python` `TypeScript`

---

## ♞ Away from the terminal

Chess is where I first learned to study adversarial decisions, build preparation systems, and stay with a difficult problem.

**Former US Chess Top 100 Junior** · **AIME Qualifier** · **U.S. National Chemistry Olympiad National Exam Participant** · **Stanford HAI AI+Education Summit table presenter** · **Valedictorian**

---

## 📡 Open channel

I'm especially interested in runtime performance, low-latency infrastructure, developer tooling, and applied ML where correctness is visible to the user.

[Send me a note](mailto:mahesh523k@gmail.com) · [Connect on LinkedIn](https://www.linkedin.com/in/mnkarthikeyan/) · [See what I'm building](https://mk-523.github.io/)
