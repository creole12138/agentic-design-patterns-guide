# 📘 Agentic Design Patterns · 8-Week Study Portal

> A self-paced, hands-on **8-week study portal** for Antonio Gulli's free book *"Agentic Design Patterns: A Hands-On Guide to Building Intelligent Systems"* (Springer, 2025) — with deep Chinese summaries, direct chapter links, weekly reading checklists, 40+ self-assessment quizzes, 8 hands-on projects, and a capstone challenge.
>
> 一份基于 Antonio Gulli《Agentic Design Patterns》的 **8 周自学门户**——包含每章深度中文摘要、直达原文链接、每周阅读清单、40+ 道自测题、8 个动手项目和综合 capstone。

🔗 **Live demo:** [Netlify](https://agentic-design-patterns-guide.netlify.app/) · [GitHub Pages](https://creole12138.github.io/agentic-design-patterns-guide/)

---

## ✨ Features · 特性

- **8 weeks of structured learning** — Week tabs, sticky sidebar with chapter index + reading checklist
- **21 chapter deep summaries** — 800-1200 Chinese characters each, based on actual PDF content (core mechanism, pitfalls, real-world tips, cross-chapter relationships)
- **One-click access to original chapters** — All 21 chapters + appendices linked to Antonio Gulli's author-maintained Google Docs
- **Hands-on projects** — 8 generic agent-building projects + 1 capstone (User feedback router, Multi-perspective competitive analysis, Operational data query agent, Enterprise knowledge bot, etc.)
- **40+ quizzes** — Click for instant correct/wrong feedback + detailed explanations
- **Local progress tracking** — `localStorage`-based, no backend required
- **Pure single-file HTML** — Open it locally, host it anywhere; no build step, no dependencies
- **Light/Dark theme toggle, responsive, sticky right sidebar** — Polished UX for desktop + mobile

---

## 📚 Curriculum · 8 周课程

| Week | Theme | Chapters Covered |
|------|-------|------------------|
| 1 | 基础 + 链式 | Intro · Ch1 Prompt Chaining · Ch2 Routing |
| 2 | 并行 + 反思 | Ch3 Parallelization · Ch4 Reflection |
| 3 | 工具 + 规划 | Ch5 Tool Use · Ch6 Planning |
| 4 | 多智能体 + 记忆 | Ch7 Multi-Agent · Ch8 Memory Management |
| 5 | 学习 + MCP + 目标 | Ch9 Learning & Adaptation · Ch10 MCP · Ch11 Goal Setting |
| 6 | 异常 + HIL + RAG | Ch12 Exception Handling · Ch13 Human-in-the-Loop · Ch14 RAG |
| 7 | 通信 + 推理 + 护栏 | Ch15 A2A · Ch16 Resource-Aware Opt · Ch17 Reasoning · Ch18 Guardrails |
| 8 | 评估 + 综合项目 | Ch19 Evaluation · Ch20 Prioritization · Ch21 Exploration + Capstone |

Recommended pace: **5-7 hours/week**, weekday reading + weekend coding.

---

## 🚀 Quick Start · 快速开始

### Option 1 — Open Locally

```bash
git clone https://github.com/creole12138/agentic-design-patterns-guide.git
cd agentic-design-patterns-guide
open index.html       # macOS
# or just double-click index.html in your file manager
```

### Option 2 — Visit Live Demo

Visit the Netlify live site: <https://agentic-design-patterns-guide.netlify.app/>

### Option 3 — Self-Host

Drop `index.html` into any static host — Netlify Drop, Cloudflare Pages, Vercel, GitHub Pages all work in <5 minutes.

---

## 🗂 Repository Structure · 仓库结构

```
.
├── index.html      # The full single-file learning portal (~175 KB)
└── README.md       # This file
```

That's it. No build, no dependencies, no backend.

Repository: <https://github.com/creole12138/agentic-design-patterns-guide>

---

## 🧰 What's in the Single HTML File

- 8 collapsible week panels (CSS-only show/hide via JS class toggle)
- Sticky right sidebar with 21-chapter index + dynamic per-week reading checklist
- 21 `<details>` deep-summary blocks (800-1200 chars each)
- 40+ interactive quiz cards with click-to-reveal answers
- Progress bar tied to `localStorage` (per-browser, no signup)
- All styling via CSS variables for easy theming
- ~2400 lines of HTML/CSS/JS, no external libs

---

## 📖 Source Material · 资料来源

- **Antonio Gulli — *Agentic Design Patterns*** (free Google Doc + Springer publication)
  - Author's maintained Google Doc index: <https://docs.google.com/document/d/1rsaK53T3Lg5KoGwvf8ukOUvbELRtH-V0LnOIFDxBryE/mobilebasic>
  - Springer book: <https://link.springer.com/book/10.1007/978-3-032-01402-3>
  - All royalties donated to **Save the Children**
- **PDF mirror (community):** [evoiz/Agentic-Design-Patterns](https://github.com/evoiz/Agentic-Design-Patterns)
- **Multi-framework code examples (community):** [ColtMercer/agentic-design-patterns](https://github.com/ColtMercer/agentic-design-patterns) — LangChain / LangGraph / CrewAI / Google ADK
- **Author LinkedIn:** [Antonio Gulli](https://www.linkedin.com/in/searchguy/)

---

## ⚖️ License · 版权说明

- **Original book content** (chapters, illustrations, code examples): © Antonio Gulli — All rights reserved.
- **Chapter summaries in this portal** are Chinese-language study notes / educational commentary written from scratch based on the book's structure. They are not verbatim translations or reproductions. Fair use for educational purposes.
- **HTML / CSS / JS for the portal itself** is released under the **MIT License** — feel free to fork, adapt, and reuse for your own study guides.
- The portal links to Antonio Gulli's official Google Docs for chapter full text rather than reproducing them.

If you find the portal useful, please:
1. Buy the book on [Springer](https://link.springer.com/book/10.1007/978-3-032-01402-3) — author royalties go to **Save the Children** 💝
2. Star the GitHub repos that mirror the PDF and code examples
3. Follow [Antonio Gulli on LinkedIn](https://www.linkedin.com/in/searchguy/)

---

## 🙋 Author · 整理者

**[Creole12138](https://github.com/creole12138)** — Portal curator and Chinese summary author.

If this helped your learning, ⭐ the repo and feel free to open an issue or PR for improvements / corrections.

---

## 🤝 Contributing

Spotted a typo, broken link, or have a better project idea for a hands-on? PRs welcome!

```bash
# Just edit index.html locally and submit a PR — it's a single file.
```

---

## 🗺 Roadmap · 后续计划

- [ ] English version of chapter summaries
- [ ] Embedded code snippets per pattern (collapsible)
- [ ] Print-friendly stylesheet for offline study
- [ ] Optional: split into per-chapter pages for SEO / shareability

---

<sub>Built with care for the AI engineering community · 2026</sub>
