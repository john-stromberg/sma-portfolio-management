# SMA Portfolio Management

Portfolio hub for workflow-oriented SMA platform projects across **equities, bonds, alternatives, ETFs, and mutual funds**.

## Objective

This parent repository organizes implementation-focused projects that emphasize:
- clear visual communication for portfolio decisions,
- scalable analytics and engineering workflows,
- explainable outputs for PM, risk, and client-facing use.

## Design principles

- **Visualization-first:** dashboards and charts should communicate decisions, not just metrics.
- **Explainability:** every repo should map outputs to a decision memo format.
- **Scalable workflows:** modular architecture (analytics, API, app, pipeline, SQL).
- **Professional usability:** reproducible runs, test coverage, and integration-ready interfaces.

## Repository map

| Repository | Primary focus | Typical outputs |
|---|---|---|
| `sma-risk-visual-analytics-platform` | Multi-asset risk dashboards and stress views | Risk panels, scenario visuals, monitoring tables |
| `sma-allocation-scenario-studio` | Strategic/tactical allocation under scenarios | Allocation what-if charts, regime comparison |
| `sma-portfolio-construction-optimizer` | Constrained portfolio construction | Optimized weights, constraint diagnostics |
| `sma-rebalancing-trade-workbench` | Drift-aware rebalance and trade generation | Trade lists, turnover/cost impact |
| `sma-performance-attribution-studio` | Benchmark-relative performance attribution | Attribution waterfall, sleeve diagnostics |
| `sma-compliance-monitoring-console` | Guideline and rule monitoring | Breach log, pre/post-trade checks |
| `sma-client-customization-lab` | Client restrictions and customization overlays | Constraint impact analysis, custom proposals |
| `sma-data-foundation-platform` | Ingestion, quality controls, and data contracts | Validated datasets, quality reports |

## Standard workflow

1. Define decision question and portfolio context.
2. Run data/pipeline steps and validate quality checks.
3. Generate visual diagnostics and summary tables.
4. Write interpretation and action recommendation.

## Decision memo format

- **Question:** What portfolio decision is being evaluated?
- **Evidence:** Which charts/tables support the conclusion?
- **Interpretation:** What changed and why it matters?
- **Action:** Rebalance, hedge, monitor, or defer.

## Submodule usage

After cloning this parent repository:

```bash
git submodule update --init --recursive
```

