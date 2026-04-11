# optionstrat — TODO

**Type:** Options Strategy Explorer & Education Tool  
**Stack:** Not yet chosen (design-phase only)  
**Status:** ~5% complete (README/design only — no code)

---

## Actions To Take

- [ ] **Choose and document the tech stack** — Decide on frontend (React/Vue/Svelte), backend (Node/Python), charting library (D3/Plotly/Chart.js), and broker APIs (Alpaca/TD Ameritrade/IB); document decisions in README
- [ ] **Initialize project structure** — Create `src/` with `components/`, `services/`, `utils/`; add `package.json` (or `pyproject.toml`) with core dependencies; configure linter (ESLint/Ruff), formatter, and build tool
- [ ] **Build a proof-of-concept Greeks calculator** — Implement Black-Scholes Delta/Gamma/Vega/Theta for a basic call/put; validates tech stack and establishes a working baseline before adding complexity
- [ ] **Set up development environment** — Configure Jest/Vitest for testing, Prettier for formatting, and a local dev server; document everything in `CONTRIBUTING.md`
- [ ] **Create core database schema** — Design tables/models for Users, Strategies, Portfolios, TradeExecutions, and PerformanceTracking; add seed data for 20+ pre-built strategies
