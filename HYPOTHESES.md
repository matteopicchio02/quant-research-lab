# Market risk research hypotheses

## Research question

How well do four models estimate one-day downside risk for three ETF
portfolios, and how does model disagreement change during stress periods?

## H1 — Tail risk

We expect the normal models to underestimate tail risk, with more than
1% of daily losses exceeding the predicted 99% VaR. We expect the
Student-t GARCH model to be closer to the 1% exceedance rate.
We will examine VaR exceedance rates, Kupiec test results and the 97.5% ES ratio.

## H2 — Clustering of exceptions

We expect EWMA and GARCH to show less clustering of VaR exceptions than
the constant-volatility normal model and historical simulation.
We will examine consecutive exceptions and Christoffersen's independence test.

## H3 — Model disagreement under stress

We expect greater disagreement across the four 99% VaR estimates during
the specified stress periods. We will compare the coefficient of variation
across models during those periods and the rest of the evaluation sample.

## Data windows

- Warm-up: 2008–2009.
- Development: 2010–2017.
- Evaluation: 2018-01-01 to 2026-12-18, reserved until the model is frozen.

## Predefined stress periods

- COVID-19 market sell-off: 2020-02-20 to 2020-04-30.
- Rate-hiking episode: 2022-01-01 to 2022-10-31.
