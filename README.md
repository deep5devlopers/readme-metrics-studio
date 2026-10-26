# 📊 README Metrics Studio

> **A lightweight Python-powered markdown engine that compiles real-time GitHub profile analytics, core contribution graphs, and verified developer system highlights into beautiful, clean layouts for profile READMEs.**

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![GitHub API v3](https://img.shields.io/badge/GitHub%20API-REST%20v3-indigo.svg)](https://docs.github.com/en/rest)

---

## ✨ Visual Features & Capabilities

- **Zero-Dependency Standard Library Core**: Built purely with Python's native `urllib.request` and `json` modules—no external pip packages required.
- **Multi-Account Telemetry Aggregation**: Simultaneously tracks and compiles live metrics across `@deep5devlopers` and `@deep-00007` (or any custom list of GitHub usernames).
- **Comprehensive Developer Analytics**: Automatically extracts public repository counts, follower/following ratios, public organization memberships, account creation timestamps, star/fork velocity, and primary runtime languages.
- **Modular Markdown Dashboard Generation**: Outputs a clean, deterministic [`PROFILE_METRICS.md`](PROFILE_METRICS.md) report formatted with executive summary tables, blockquotes, and developer cards.

---

## 🚀 Quick Start & Installation

Clone the repository and execute `metrics_compiler.py` directly using Python 3:

```bash
# 1. Clone the repository
git clone https://github.com/deep5devlopers/readme-metrics-studio.git
cd readme-metrics-studio

# 2. Compile live profile metrics for default accounts (deep5devlopers & deep-00007)
python metrics_compiler.py

# 3. Compile metrics for custom GitHub usernames and specify output path
python metrics_compiler.py --users deep5devlopers deep-00007 --output PROFILE_METRICS.md
```

---

## 📁 Repository Architecture

| File | Responsibility |
| :--- | :--- |
| `metrics_compiler.py` | Core Python analytics compiler connecting to the GitHub REST API (`https://api.github.com/users/{username}`). |
| `PROFILE_METRICS.md` | Live compiled Markdown telemetry dashboard for `@deep5devlopers` and `@deep-00007`. |
| `LICENSE` | Official Open-Source MIT License. |
| `README.md` | Project documentation, CLI reference, and contribution workflow guide. |

---

## 🏆 Contribution & Badges

Contributions, performance optimizations, and modular layout templates are welcome! This project follows a verified feature-branch Pull Request workflow with automated co-author attribution:

- **Pull Shark**: Verified multi-PR feature and rendering engine optimization pipeline.
- **Pair Extraordinaire**: Co-authored commits engineered with `Metrics-Studio-Compiler-Bot <bot@readmemetrics.studio>`.
- **Galaxy Brain**: Community architecture discussions and verified Q&A resolutions.

### Standard Feature Branch Workflow

```bash
git checkout -b feature/your-enhancement
python metrics_compiler.py
git commit -m "Feat: Describe enhancement" -m "Co-authored-by: Metrics-Studio-Compiler-Bot <bot@readmemetrics.studio>"
git push origin feature/your-enhancement
```

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full license text.
