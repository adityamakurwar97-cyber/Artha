# Changelog

## v1.4.0 — 2026-11-12

- Add reviewed multi-company package activation, issuer-isolated snapshots, a real
  company selector, all-registered reconciliation tests and synthetic second-issuer
  onboarding tests. Full peer-only datasets are not fabricated or activated.
- Add annual forecast margins, seeded stdlib Monte Carlo with quantiles/histogram,
  and validated reverse DCF for hypothetical user prices through Python APIs.
- Add system-aware/manual dark mode, tablet layout down to 768px, skeletons,
  background-inert dialogs, focus trapping, and an accessible SVG equity bridge.
- Split app.js into native state, API, views, dialogs and chart modules. Retain
  every legacy numerical assertion in a test-only JS benchmark; remove financial
  calculations from deployable browser assets. Add JSDoc and Python annotations
  and docstrings throughout src/ without changing the benchmark formulas.
- Add bounded Python admission, protected readiness, safe structured request logs,
  failed-login throttling, exact-origin proxy configuration, WAL/retention and
  online integrity-checked backups. Keep existing security and LLM validation.
- Add check/preflight commands, root GitHub CodeQL/Dependabot/verification workflows,
  unit/API/module/accessibility-helper/store/pool tests and operational docs.
- Verification limitation: real Chromium visual checks are blocked by this
  environment's socket restriction. Full WCAG 2.2 AA conformance is not certified.
