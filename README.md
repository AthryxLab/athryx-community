<div align="center">

<!-- Logo placeholder — replace with your actual logo asset -->
<img src="https://raw.githubusercontent.com/athryxlab/.github/main/assets/logo.svg" alt="Athryx Logo" width="64" height="64" />

# Athryx

**Engineering Adaptive Performance**

[![Release](https://img.shields.io/github/v/release/athryxlab/community?color=00E5FF&label=Release&style=flat-square)](https://github.com/athryxlab/community/releases)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)](https://athryx.ai)
[![Discussions](https://img.shields.io/github/discussions/athryxlab/community?color=6C5CE7&style=flat-square)](https://github.com/athryxlab/community/discussions)
[![License](https://img.shields.io/badge/License-Proprietary-lightgrey?style=flat-square)](#license)

[**Try Athryx →**](https://athryx.ai) · [**Discussions**](https://github.com/athryxlab/community/discussions) · [**Roadmap**](#roadmap) · [**Release Notes**](https://github.com/athryxlab/community/releases)

</div>

---

## What is Athryx?

Athryx is a **physiology-first, adaptive performance intelligence platform** built for serious endurance athletes — marathon runners, cyclists, and triathletes who demand more than activity summaries.

Where most tools count your kilometers, Athryx models your physiology. It ingests your training data, quantifies fatigue and recovery, and surfaces the insights that actually drive performance — delivered through a conversational AI coach grounded in your real data.

> **Adaptation over prediction. Systems over hacks. Data must become actionable.**

---

## Modules & Status

| Module                  | Description                                                             |   Status   |
| ----------------------- | ----------------------------------------------------------------------- | :--------: |
| **Athryx Core**         | Secure sign-in, account management, Cockpit dashboard                   |  ✅ Live   |
| **Athryx Intelligence** | AI-assisted training analysis, fatigue monitoring, conversational coach |  ✅ Live   |
| **Athryx Engine**       | Adaptive workout generation, load-based recommendations                 | 🔜 Planned |
| **Athryx Recovery**     | HRV and fatigue modeling                                                | 🔜 Planned |
| **Athryx Insight**      | Advanced analytics and long-term trends                                 | 🔜 Planned |
| **Athryx Protocols**    | Recovery and nutrition knowledge base                                   | 🔜 Planned |

---

## Key Capabilities

### Cockpit Dashboard

A unified view of your training: weekly volume, moving time, workload index, recent activities, and a training load chart — all updated automatically from Strava.

### AI Performance Coach

A persistent, data-grounded AI agent that answers questions about your training. It has working memory across sessions — it knows your athlete profile, your current objectives, and your preparation context. Powered by GPT-5.1 via Mastra.

### Activity Intelligence

Drill into any session: heart rate zones, power distribution, pace analysis, elevation, suffer score, and more. Filter your full activity history by sport or date range.

### Athlete Zones

Visualize your heart rate and power zones, calibrated to your physiology.

### Privacy-First

Your data is never sold or shared with third parties. Infrastructure is hosted in Europe.

---

## Roadmap

> For the detailed roadmap, participate in [Discussions → Roadmap](https://github.com/athryxlab/community/discussions/categories/roadmap).

```
2026
├── Q1  Athryx Core + Intelligence (Live)
│       ─ Strava OAuth integration
│       ─ Cockpit dashboard
│       ─ Conversational AI coach with persistent memory
│
├── Q2  Athryx Engine (Planned)
│       ─ Adaptive workout generation
│       ─ Load-based weekly structure recommendations
│       ─ Readiness scoring
│
├── Q3  Athryx Recovery (Planned)
│       ─ HRV integration
│       ─ Fatigue curve modeling
│       ─ Recovery-adjusted training advice
│
└── Q4  Athryx Insight + Protocols (Planned)
        ─ Long-term trend analytics
        ─ Season periodization view
        ─ Curated recovery and nutrition protocols
```

---

## Releases

All releases are documented in the [**Releases**](https://github.com/athryxlab/community/releases) tab with full changelogs.

| Version                                                              | Date     | Highlights                                           |
| -------------------------------------------------------------------- | -------- | ---------------------------------------------------- |
| [v1.0.0](https://github.com/athryxlab/community/releases/tag/v1.0.0) | Mar 2026 | Initial public release — Core + Intelligence modules |

---

## Community

This repository is the **public home for Athryx discussions**. Whether you have a feature request, found a bug, want to share feedback, or just want to talk training — this is the place.

### [Open a Discussion →](https://github.com/athryxlab/community/discussions)

| Category                                                                                        | Purpose                                               |
| ----------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| 💡 [Ideas](https://github.com/athryxlab/community/discussions/categories/ideas)                 | Propose new features or improvements                  |
| 🗺️ [Roadmap](https://github.com/athryxlab/community/discussions/categories/roadmap)             | Follow and discuss what's coming next                 |
| 🐛 [Bug Reports](https://github.com/athryxlab/community/discussions/categories/bug-reports)     | Report issues you've encountered in the app           |
| 🙋 [Q&A](https://github.com/athryxlab/community/discussions/categories/q-a)                     | Ask questions about using Athryx                      |
| 📣 [Announcements](https://github.com/athryxlab/community/discussions/categories/announcements) | Official news and release announcements               |
| 🏃 [Training](https://github.com/athryxlab/community/discussions/categories/training)           | Discuss training methods, physiology, and performance |

---

## Stack

Athryx is built with a modern, production-grade stack.

**Backend** — Node.js 22, Express 5, TypeScript, Mastra AI, PostgreSQL 16 + pgvector, MikroORM, Zod, Docker, AWS Elastic Beanstalk

**Frontend** — React 19, Vite 6, TypeScript, Tailwind CSS, shadcn/ui, Framer Motion, Recharts, nginx

---

## Links

|                    |                                                |
| ------------------ | ---------------------------------------------- |
| **App**            | [athryx.ai](https://athryx.ai)                 |
| **Blog**           | [athryx.ai/blog](https://athryx.ai/blog)       |
| **Privacy Policy** | [athryx.ai/privacy](https://athryx.ai/privacy) |
| **Terms of Use**   | [athryx.ai/terms](https://athryx.ai/terms)     |

---

## License

Athryx is proprietary software. All rights reserved © 2026 Athryx Lab.

This community repository exists solely for public discussion, feedback, and release tracking. No source code is distributed here.

---

<div align="center">

Built with precision for athletes who demand more.

**[athryx.ai](https://athryx.ai)**

</div>
