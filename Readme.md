## Serhii Kupriienko

**Software & Systems Engineer · Python & Rust · Package Ecosystems, Supply Chain & Edge Security**

> *Transforming packaging and infrastructure chaos into predictable stability.*

With **5+ years** across Python, multi-platform package distribution, production Linux systems, and **AWS (6+ years)**, I build reproducible build pipelines, resilient backend services, and hardened infrastructure across e-commerce, high-traffic web (**1M+ annual users**), ML/data, and security domains. Former History PhD turned Engineer—applying the same analytical rigor from deciphering historical manuscripts to untangling dependency graphs, binary ABI issues, and full-stack production bottlenecks.

[![LinkedIn](https://img.shields.io/badge/in-LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/serhii-kupriienko/)
[![Repositories](https://img.shields.io/badge/Public_Repos-77+-1e293b?style=flat-square&logo=github&logoColor=white)](https://github.com/skupriienko?tab=repositories)

---

### What I Do

- **Package Ecosystems & Reproducible Builds** — Cross-platform distribution across `PyPI` (`wheel`), `conda-forge` (`conda-build`), and `Cargo` on **Linux (`x86_64`/`ARM64`)**, **macOS**, and **Windows/MSYS2**—solving Python version migrations, CUDA compatibility, and ABI/linkage issues.
- **Production Linux, Edge Defense & Hardening** — End-to-end diagnostics and operations (`DNS → Cloudflare WAF/CDN → Nginx → App → DB`) for **1M+ user** platforms: custom Cloudflare WAF & AI-scraper mitigation (**60%+ origin traffic offloaded**), web-exposure auditing (CWE-552/200), zero-downtime migrations, KVM/QEMU virtualization, and deterministic Bash DR/backup automation.
- **Supply Chain & Application Security** — Dependency/vulnerability auditing, pre-flight security sentinels, API/endpoint hardening, and deterministic release workflows.
- **Backend, Data & AI-Native Tooling** — Async APIs & ETL pipelines (`FastAPI`, `Pydantic`, `asyncio`, `PostgreSQL`, `MariaDB`), strict QA gates (`ruff`, `pyright`, `pytest`, `pre-commit`), memory-safe **Rust** CLI utilities, and agentic/MLOps workflows (`Gemini`, `Antigravity`, `MCP`).

---

### Selected Open Source

| Project | Focus | Description |
| :--- | :--- | :--- |
| **[Conda-world-cheatsheet](https://github.com/skupriienko/Conda-world-cheatsheet)** | Packaging | Practical field guide to Conda environments, dependency resolution, and package builds |
| **[Ukrainian-Stopwords](https://github.com/skupriienko/Ukrainian-Stopwords)** | NLP / Dataset | ~2,000 curated Ukrainian stop words widely used in text-processing pipelines |
| **[Ukrainian-Sentiment-Analysis](https://github.com/skupriienko/Ukrainian-Sentiment-Analysis)** | NLP / Lexicon | Curated Ukrainian vocabulary and assets for sentiment analysis |
| **[Pyxtract](https://github.com/skupriienko/Pyxtract)** | Data / ETL | Modular Python toolkit for extracting structured text from URLs and PDFs |

---

### Core Stack & Tooling

| Area | Technologies *(ordered by depth)* |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-1e293b?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-1e293b?style=flat-square&logo=gnubash&logoColor=white) ![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-1e293b?style=flat-square&logo=cplusplus&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-1e293b?style=flat-square&logo=rust&logoColor=white) &nbsp;·&nbsp; `asyncio` `strict-typing` |
| **Packaging & Supply Chain** | ![PyPI](https://img.shields.io/badge/PyPI_%2F_wheel-1e293b?style=flat-square&logo=pypi&logoColor=white) ![Conda-Forge](https://img.shields.io/badge/conda--forge-1e293b?style=flat-square&logo=anaconda&logoColor=white) ![Cargo](https://img.shields.io/badge/Cargo-1e293b?style=flat-square&logo=rust&logoColor=white) &nbsp;·&nbsp; `conda-build` `setuptools-scm` `Vuln & Supply Chain Auditing` |
| **Native Builds & ABI** | ![CMake](https://img.shields.io/badge/CMake-1e293b?style=flat-square&logo=cmake&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-1e293b?style=flat-square&logo=nvidia&logoColor=white) &nbsp;·&nbsp; `GNU Make` `Meson` `GCC/Clang/MSVC` `ldd` `otool` `patchelf` `dumpbin` |
| **Systems, Edge & Cloud** | ![Linux](https://img.shields.io/badge/Linux-1e293b?style=flat-square&logo=linux&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_WAF-1e293b?style=flat-square&logo=cloudflare&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-1e293b?style=flat-square&logo=nginx&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-1e293b?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-1e293b?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1e293b?style=flat-square&logo=githubactions&logoColor=white) ![macOS](https://img.shields.io/badge/macOS-1e293b?style=flat-square&logo=apple&logoColor=white) &nbsp;·&nbsp; `RHEL/CentOS` `Ubuntu` `systemd` `KVM/QEMU` `Windows/MSYS2` |
| **Backend, DBs & AI** | ![FastAPI](https://img.shields.io/badge/FastAPI-1e293b?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-1e293b?style=flat-square&logo=pydantic&logoColor=white) ![Pytest](https://img.shields.io/badge/pytest-1e293b?style=flat-square&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-1e293b?style=flat-square&logo=ruff&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e293b?style=flat-square&logo=postgresql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-1e293b?style=flat-square&logo=mariadb&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-1e293b?style=flat-square&logo=sqlite&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_%2F_Agents-1e293b?style=flat-square&logo=googlegemini&logoColor=white) &nbsp;·&nbsp; `Pyright` `pre-commit` `Antigravity` `MLOps` |

---

<sub>Open to discussing package-building internals, supply chain & edge security, Linux infrastructure, ABI debugging, and modern Python/Rust tooling · 🇺🇦 Native · 🇬🇧 Professional · 🇪🇸 Intermediate</sub>
