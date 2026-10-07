## Soentke Blindow

Quantitative analyst working on probabilistic forecasting for power markets. Five years of independent model validation in banking — credit, market and liquidity risk — now building forecasting systems and holding them to the same standard.

What I care about is whether a forecast still holds up once you backtest it honestly: calibration rather than point accuracy alone, no lookahead, information as it was actually available at decision time, and live benchmarks instead of self-reported results.

### Projects

**[day-ahead-forecast-live-ops](https://github.com/soentkeblindow/day-ahead-forecast-live-ops)** — Day-ahead electricity price forecasting for the German bidding zone (DE-LU), running unattended since September 2026. Daily automated submissions to a public forecasting competition via GitHub Actions, with monitoring and fallback handling. Point and quantile tracks.

**[energy-price-forecast-risk-validation](https://github.com/soentkeblindow/energy-price-forecast-risk-validation)** — End-to-end study behind it: reproducible ENTSO-E data pipeline, LightGBM quantile regression benchmarked against linear models and ARIMAX in a leakage-free walk-forward backtest, conformal calibration of the forecast intervals, and VaR / Expected Shortfall backtesting of a hypothetical 10 MW trading book. Conditional coverage breaks are reported, not smoothed over. Typed and tested (469 tests, CI). → [Live demo](https://energy-price-forecast-azetvtdc9hgc7yylhqp84q.streamlit.app/)

### Background

M.Sc. Mathematics, TU Berlin and Université de Montpellier · five years quantitative risk at Deutsche Kreditbank AG, including sub-project lead for the bank's IRB implementation.

[LinkedIn](https://www.linkedin.com/in/soentke-blindow-086425386) · Berlin
