<div align="center">

# hongjin-he.github.io

**Personal academic website of HongJin HE (何泓锦)**

[![Live](https://img.shields.io/badge/live-hongjin--he.github.io-blue)](https://hongjin-he.github.io)
[![HTML](https://img.shields.io/badge/stack-HTML%20%2F%20CSS%20%2F%20vanilla%20JS-orange)](index.html)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

→ **[hongjin-he.github.io](https://hongjin-he.github.io)**

</div>

---

## About

Undergraduate at **HKUST** (RMBI + MATH + AI), on exchange at **Stanford** via the Interdisciplinary Honors Program. Research sits at the intersection of mathematical finance, stochastic analysis, and machine learning — with a focus on building rigorous theoretical foundations for world models applied to quantitative finance.

Founder of **Alpha Flow** — a research initiative developing mathematical frameworks that unify SDEs, mean-field game theory, and generative modeling for financial applications.

---

## Site Sections

| Section | Content |
|---------|---------|
| **Bio** | Research statement and founding philosophy of Alpha Flow |
| **Research Interests** | World models · Mathematical finance · Diffusion models · RL · LLM evaluation · Quant finance |
| **Papers & Projects** | Mathematical Framework for World Models (preprint) · LLM Hallucination in Financial Disclosures (under review) · Diffusion-Flow Alpha Mining · Stanford AI Labs Ecosystem |
| **Education** | Stanford (CS exchange 2025–26) · HKUST (RMBI + MATH + AI) |

---

## Papers

### [Mathematical Framework for World Models in Quantitative Finance](https://github.com/hongjin-he/mathmatical-framework-for-world-models-in-quant-finance)
arXiv preprint, July 2026  
Introduces the *E-Game-C architecture* — Encoder (Lévy-Itô decomposition) → Mean-Field Game (HJB + FPK system) → Controller (Stochastic Lyapunov stability). Seven original theorems unifying stochastic decomposition, topological groupoids, and mean-field game theory for financial world models.

### LLM Hallucination in Financial Disclosures
Under peer review, 2026  
Analysis of 5,552 U.S. firms' SEC filings across 3,600+ model responses. Identifies *D-type hallucination* — models fabricate confident answers when no source information exists. GPT-4o showed 54.8% improvement over GPT-3.5 in Prompt Score under controlled conditions.

---

## Projects

### [Diffusion-Flow Alpha Mining](https://github.com/hongjin-he/diffusion-alpha-mining)
Applies diffusion models and flow matching to quantitative alpha factor discovery. Learns P(α) ∝ R(α) — sampling proportional to reward rather than argmax — generating diverse, low-correlation alpha pools. 3× improvement over random baseline (Mean IC: 0.148 vs ~0.05). Built on GFlowNet trajectory balance, which is mathematically equivalent to continuous flow matching on discrete expression graphs.

### [LOB Arena — Backtest Framework](https://github.com/hongjin-he/quant-realtime-backtest-framework)
Production-grade limit order book simulation with price-time priority matching (O(log n) insert, O(1) best-price). Multi-strategy Arena for competing agents. Connects to the companion world models paper via the Lévy-Itô jump-diffusion synthetic market generator.

### [Stanford AI Labs Ecosystem](https://github.com/hongjin-he/stanford-ai-labs-ecosystem)
Nine interactive visualizations mapping Stanford's AI research landscape across 2018–2026 — collaboration networks, research trend analysis, industry talent flow. Built during CS exchange as a systematic alternative to the "vibes-based" lab selection process.

---

## Tech Stack

Single-file static site — no build tools, no frameworks, no dependencies.

| Layer | Choice | Reason |
|-------|--------|--------|
| Markup | Semantic HTML5 | Full control over structure |
| Styling | Custom CSS (CSS variables, flexbox) | No framework bloat |
| Theming | `prefers-color-scheme` + `data-theme` toggle | System dark mode + manual override |
| Hosting | GitHub Pages | Zero config, instant deploy |
| JS | ~30 lines (theme toggle only) | Everything else is pure CSS |

Light/dark mode is implemented with CSS variables — the entire theme switches by toggling `data-theme` on `:root`. No JavaScript frameworks, no build step, no `node_modules`.

---

## Links

- **Website:** [hongjin-he.github.io](https://hongjin-he.github.io)
- **GitHub:** [github.com/hongjin-he](https://github.com/hongjin-he)
- **LinkedIn:** [linkedin.com/in/hongjinhe-hkust-edu](https://www.linkedin.com/in/hongjinhe-hkust-edu)
- **Email:** hehongjinhkust0911@gmail.com

---

<div align="center">
<sub>HKUST × Stanford · 2025–2026</sub>
</div>
