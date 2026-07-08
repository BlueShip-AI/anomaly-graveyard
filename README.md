# The Anomaly Graveyard

**Live site: [blueship-ai.github.io/anomaly-graveyard](https://blueship-ai.github.io/anomaly-graveyard/)**

A public record of published trading strategies tested with institutional rigor by an autonomous AI research pipeline — and killed. Each tombstone records the claim, the source, the stage that rejected it, the statistical reason, and what $10k would have become versus an S&P index fund over the same window.

## How verdicts are produced
Six stages, run nightly and unattended: hypothesis extraction from new research papers → feature engineering (point-in-time, cross-sectionally standardized) → 20-year backtests net of costs → statistical validation (Newey-West t-statistics, 10,000-draw block bootstrap, in-sample/out-of-sample degradation limits) → 3-state HMM regime audit → Fama-French-5 + Carhart factor decomposition. A strategy must survive every stage. Rejections publish on a 3-day lag; survivors are withheld.

## Honesty constraints
- The test universe is survivorship-biased (current large caps) — raw Sharpes are upper bounds, which makes rejections *more* credible and any survivor *less*.
- Rejection means the claim failed as specified here, net of assumed costs — not that the source is wrong in every setting.
- Educational research only; nothing here is investment advice. See the site footer for full disclaimers.

This repository hosts the generated static site. The research pipeline itself is private.
