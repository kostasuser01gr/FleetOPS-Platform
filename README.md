# FleetOPS Platform

[![CI](https://github.com/kostasuser01gr/FleetOPS-Platform/actions/workflows/ci.yml/badge.svg)](https://github.com/kostasuser01gr/FleetOPS-Platform/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-19-61DAFB)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org)

> Real-time fleet operations dashboard with AI-assisted decision support, live vehicle tracking, and operational logging.

No verified hosted demo is currently advertised. Run locally or deploy the static build to a host you control.

Built with **React 19**, **TypeScript**, **Vite**, and **Gemini AI** — runs entirely in the browser with no backend required.

---

## Features

- **Fleet Grid** — live vehicle card view with status, fuel level, location, and driver assignment
- **Map View** — real-time vehicle positions on an interactive map
- **Vehicle Detail** — per-vehicle telemetry, maintenance history, and quick actions
- **Operations Log** — timestamped event stream for dispatching, alerts, and status changes
- **AI Chat** — Gemini-powered assistant for fleet queries, route suggestions, and anomaly analysis
- **Command Palette** — `⌘K` global command launcher for fast navigation

---

## Tech Stack

- **React 19** · TypeScript · Vite
- **Tailwind CSS** — dark-first GitHub-inspired design
- **Gemini AI** (`@google/generative-ai`) — embedded AI chat assistant
- No backend — all state is local, deployable as a static site

---

## Getting Started

```bash
git clone https://github.com/kostasuser01gr/FleetOPS-Platform
cd FleetOPS-Platform
npm install
```

Create `.env.local`:
```env
VITE_GEMINI_API_KEY=your_gemini_api_key
```

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173)

---

## Build for Production

```bash
npm run build
npm run preview
```

The output is a static bundle — deployable to Vercel, Netlify, Cloudflare Pages, or any static host.

---

## License

MIT

---

## Author

**Konstantinos Foskolakis**
Full-stack engineer — Heraklion, Crete, Greece
[github.com/kostasuser01gr)

**Live Demo:** [fleetops-platform-hf122xsjj-kostasuser01gr.vercel.app](https://fleetops-platform-hf122xsjj-kostasuser01gr.vercel.app)

---

## Portfolio Positioning

This project demonstrates real-time fleet dashboard design with AI decision support embedded directly in the operational context. The zero-backend architecture is a deliberate choice: all state is local and the entire platform deploys as a static bundle, eliminating infrastructure cost and making the public demo fully accessible without credentials or backend setup. The Gemini AI integration is scoped to fleet-relevant queries — route suggestions, anomaly analysis, status interpretation — rather than a generic chatbot. The command palette, live vehicle grid, and operational log reflect the UX patterns that operational teams need for fast situational awareness.

*Built as a portfolio-grade real-time fleet operations dashboard. Estimated implementation effort for the current public version: 3–5 focused development days.*
