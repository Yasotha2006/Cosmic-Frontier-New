# 🌌 Cosmic Frontier

## Exploring the cost-accuracy frontier of AI reasoning — one star at a time.

---

## 📋 Table of Contents

- [The Central Claim](#-the-central-claim)
- [Intended Audience](#-intended-audience--prerequisites)
- [Learning Objectives](#-learning-objectives)
- [Live Demo](#-live-demo)
- [Architecture](#-architecture)
- [BDH Integration](#-bdh-integration)
- [Setup Instructions](#-setup-instructions)
- [Environment Variables](#-environment-variables)
- [Live vs Precomputed Components](#-live-vs-precomputed-components)
- [Primary Sources](#-primary-sources-2022-2026)
- [AI Assistance Disclosure](#-ai-assistance-disclosure)
- [Credits & Licenses](#-credits--licenses)
- [Known Limitations](#-known-limitations)

---

## 🎯 The Central Claim

> **A 150-million-parameter model (BDH-CQ) can achieve near-frontier reasoning performance at 11x lower cost by performing recurrent latent-space reasoning without generating a verbal chain-of-thought.**

---

## 👥 Intended Audience & Prerequisites

| Audience | Prerequisites |
|----------|---------------|
| AI Researchers | Basic understanding of transformers |
| ML Engineers | Familiarity with language models |
| Data Scientists | Interest in AI efficiency |
| Students | High-level understanding of LLMs |

---

## 📚 Learning Objectives

After using Cosmic Frontier, learners will be able to:

1. **Define** the Cost-Accuracy Pareto Frontier
2. **Explain** why BDH-CQ achieves 11x cost savings
3. **Distinguish** latent reasoning from chain-of-thought
4. **Identify** limitations of small specialized models

---

## 🌐 Live Demo

**[🔗 Cosmic Frontier Live Demo](https://your-app-url.vercel.app)**

---

## 🏗️ Architecture

| Layer | Technology |
|-------|------------|
| Framework | Next.js 16 + React 19 |
| Styling | Tailwind CSS v4 + shadcn/ui |
| Charts | Recharts |
| Animations | Framer Motion |
| Language | TypeScript |
| Package Manager | pnpm |

### Component Structure

```
cosmic-frontier/
├── app/
│   ├── page.tsx              # Main page
│   ├── layout.tsx            # Root layout
│   └── globals.css           # Cosmic theme
├── components/
│   ├── cosmic/
│   │   ├── Hero.tsx
│   │   ├── ParetoChart.tsx
│   │   ├── ReasoningEffort.tsx
│   │   ├── LatentVsCoT.tsx
│   │   ├── HistoricalTimeline.tsx
│   │   ├── EquationsVisualizer.tsx
│   │   ├── Limitations.tsx
│   │   ├── Quiz.tsx
│   │   └── StarfieldBackground.tsx
│   └── ui/                   # shadcn/ui components
├── lib/
│   └── utils.ts
├── data/
│   └── frontierData.ts       # Precomputed model data
├── README.md
├── CONCEPT_EVIDENCE.md
├── ONE_PAGE_SUMMARY.pdf
└── .env.example
```

---

## 🧠 BDH Integration

The BDH module is **woven throughout** the experience.

### Section 3: "Dial the Reasoning Effort" — BDH-CQ Simulator

| Effort | Accuracy | Cost |
|--------|----------|------|
| Low | 21.6% | $0.00022 |
| Medium | 24.1% | $0.00039 |
| High | 29.5% | $0.00070 |

**Key Result:** BDH-CQ achieves 29.5% accuracy at $0.00070 — **11x cheaper than GPT-5.6 Luna (Low)** .

### Section 4: Latent vs CoT Comparison

- **BDH-CQ:** Latent reasoning (0 tokens generated)
- **GPT-5.6 Luna:** Chain-of-thought (~100 tokens)

### Section 6: Equations of Reasoning

Visualizes BDH's formalism: `s_t = f(s_{t-1}, x_t, W_syn)`

---

## 🚀 Setup Instructions

### Prerequisites

- Node.js 20+
- pnpm (or npm/yarn)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/cosmic-frontier.git
cd cosmic-frontier

# 2. Install dependencies
pnpm install

# 3. Run development server
pnpm dev

# 4. Open http://localhost:3000
```

### Build for Production

```bash
pnpm build
pnpm start
```

---

## 🔐 Environment Variables

No secrets are required. All data is precomputed from public sources.

```bash
# .env.example
# No secrets needed — all data is precomputed
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

---

## ⚡ Live vs Precomputed Components

| Component | Status |
|-----------|--------|
| Pareto Chart | ✅ Precomputed |
| Reasoning Effort | ✅ Interactive |
| Latent vs CoT | 🎨 Animated (labeled) |
| Historical Timeline | ✅ Precomputed |
| Quiz | ✅ Interactive |
| Starfield | 🎨 Animated (labeled) |

---

## 📖 Primary Sources (2022-2026)

| # | Source | Link |
|---|--------|------|
| 1 | BDH-CQ Technical Report (2026) | [pathway.com/bdh-cq](https://www.pathway.com/bdh-cq) |
| 2 | Dragon Hatchling Paper (2026) | [arxiv.org/abs/2502.09371](https://arxiv.org/abs/2502.09371) |
| 3 | From Attention to Synapses (2026) | [pathway.com/blog/from-attention-to-synapses](https://www.pathway.com/blog/from-attention-to-synapses) |
| 4 | The Equations of Reasoning (2026) | [pathway.com/blog/equations-of-reasoning](https://www.pathway.com/blog/equations-of-reasoning) |
| 5 | ARC-AGI-1 Leaderboard (2026) | [arc-agi.live](https://arc-agi.live/) |

---

## 🤖 AI Assistance Disclosure

This project was built with assistance from AI tools. All code has been **reviewed, understood, and can be defended** by the team.

---

## 📄 Credits & Licenses

### Data Sources
- BDH-CQ Technical Report (Pathway, 2026)
- ARC-AGI-1 Leaderboard

### Design
- Cosmic theme inspired by space imagery
- Fonts: Inter, Space Grotesk (Google Fonts)

### License
**MIT License** — See LICENSE file for details

---

## ⚠️ Known Limitations

| Limitation | Impact |
|------------|--------|
| Precomputed data only | Not connected to live BDH-CQ model |
| ARC-AGI specific | Concept shown only for ARC-AGI |
| Developer-reported results | Not independently verified at scale |

---

## 📧 Contact

- **Project:** Cosmic Frontier
- **Hackathon:** DataForge x rime 2026 Pathway Track
- **Repository:** [GitHub URL]
- **Live Demo:** [Vercel URL]

---

**🌌 Cosmic Frontier — Making the frontier click. One star at a time.**

---

*Last Updated: 2026*
