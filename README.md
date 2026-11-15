<div align="center">

# The 7th Sense Lab

### Quantitative research and AI governance — risk you can check.

Work by **Joseph Bidias** — quantitative researcher and AI governance specialist, AI2030 Global Fellow. This is a curated index of my projects: what each one is, where it runs, and how far along it is. Flagships first.

![Focus](https://img.shields.io/badge/Quant_Research-·_AI_Governance-1A3A5C?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AI2030](https://img.shields.io/badge/AI2030-Global_Fellow-7D3C98?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-2E7D32?style=flat-square)

[GitHub](https://github.com/eaglepython) · [Portfolio site](https://eaglepython.github.io/The-7th-Sense-Lab/)

</div>

---

## 🧭 How to read this

Two kinds of work live here, labeled honestly so you know what you are looking at:

- **Flagships** — real, working software with tests and documentation.
- **Prototypes** — front-end demos that run on sample or simulated data to explore an idea. Labeled as such, never dressed up as production systems.

---

## ⭐ Flagships

### QuantRisk — fixed-income & credit-risk analytics platform
A daily risk pipeline that turns a bond and credit portfolio into the numbers a risk desk acts on: valuations and key-rate durations, Value-at-Risk and Expected Shortfall, a named-scenario stress engine, and a credit PD model with macro stress. ~4,800 lines of Python, **37 passing tests**, an HTML report, a Streamlit dashboard, plus Docker, CI, and Terraform. Runs on synthetic sample data out of the box, or real Treasury curves from FRED when configured.

[**Repo →**](https://github.com/eaglepython/quantrisk) · [**Static showcase →**](https://quantrisk1.netlify.app/)

### Regime-Aware Pairs Trader — MScFE capstone
Does pausing a pairs trade during high-volatility regimes improve risk-adjusted performance? A Markov-Switching regime filter tested on the XLE/XOP energy ETF pair across the 2018 oil selloff and the COVID-19 crash, with cointegration tests, VaR backtests, and a stress analysis. The result is reported straight: the pair was not cointegrated and neither strategy was profitable, but the filter cut the drawdown and sat out the crash. A clean, honest null result.

[**Repo →**](https://github.com/eaglepython/Regime-aware-pairs-trader)

---

## 📈 Quantitative finance

| Project | What it is | Links |
|---|---|---|
| **Quant AI/ML Portfolio** | A collection of quantitative finance and ML research: econometrics, option pricing, ensemble signals, and more. Backtested and educational. | [Repo](https://github.com/eaglepython/quant_ai_ml_portfolio) |

---

## 🏛️ AI governance & policy

Prototypes that explore practical problems in AI oversight. Each runs in the browser on sample or simulated data — none is deployed in an agency or company.

| Project | What it explores | Links |
|---|---|---|
| **Healthcare LLM Governance Toolkit** | A weighted risk questionnaire for healthcare AI and a mock oversight dashboard | [Repo](https://github.com/eaglepython/healthcare-llm-governance-toolkit) · [Demo](https://eaglepython.github.io/healthcare-llm-governance-toolkit) |
| **Multi-LLM Orchestration Platform** | Routing requests across providers to reduce single-vendor dependence | [Repo](https://github.com/eaglepython/multi-llm-orchestration-platform) · [Demo](https://eaglepython.github.io/multi-llm-orchestration-platform/) |
| **AI Ethics Monitoring Dashboard** | Which bias and fairness measures an oversight team needs on one screen | [Repo](https://github.com/eaglepython/ai-ethics-monitoring-dashboard) · [Demo](https://eaglepython.github.io/ai-ethics-monitoring-dashboard) |
| **Policy Analysis Dashboard** | Market concentration (HHI) and cost analysis from an uploaded CSV | [Repo](https://github.com/eaglepython/policy-analysis-dashboard) |
| **AI Governance Portfolio** | A landing page tying the governance prototypes together | [Repo](https://github.com/eaglepython/ai-governance-portfolio) |

---

## 👤 About

I build and study systems where a wrong answer reaches a real person — public health, county government, clinical research, and financial markets. Across all of it the hard question is rarely the model; it is who checks it, what gets measured, and what happens when a check fails. My work tries to take that seriously: rigorous methods, honest reporting, and results you can reproduce.

- **GitHub:** [github.com/eaglepython](https://github.com/eaglepython)
- **Focus:** quantitative risk, econometrics, AI governance and policy

<sub>Released under the MIT License. Prototypes run on sample or simulated data; nothing here is investment advice.</sub>
