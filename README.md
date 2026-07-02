# Shelly Group (BSE: SLYG / OTC: SHELY) — Investment Analysis

Independent investment analysis of Shelly Group SE, a Bulgarian-headquartered IoT company that designs and distributes smart home devices sold under the "Shelly" brand in over 130 countries, featuring an open-ecosystem, local-first architecture with Wi-Fi/Bluetooth/Matter connectivity.

## Contents

| File | Description |
|------|-------------|
| [SHELY_investment_thesis.md](SHELY_investment_thesis.md) | Full investment thesis (markdown) |
| [SHELY_investment_thesis.pdf](SHELY_investment_thesis.pdf) | Investment thesis (PDF) |
| [shely_financial_model.ipynb](shely_financial_model.ipynb) | Bottom-up financial model (Jupyter notebook) |

## Thesis Summary

**Date:** March 2026 | **Data basis:** FY2025 financial results

Shelly has compounded revenue at ~45% CAGR over 2022-2025 (EUR 47.6M to EUR 149.7M), maintaining ~25% EBIT margins and benefiting from Bulgaria's 10% corporate tax rate. The company has sold 30M+ cumulative devices with 2.7M cloud users.

### DCF Valuation (EUR, diluted) — 15-year, three-phase DCF

| Scenario | Implied Price | Upside vs EUR 57.60 | 2040E Revenue | Terminal EBIT margin |
|----------|--------------|--------------------|---------------|---------------------|
| Bull     | EUR 179.11   | +211%              | EUR 1,851M    | 36.1%               |
| Base     | EUR 92.38    | +60%               | EUR 1,034M    | 31.1%               |
| Bear     | EUR 36.72    | −36%               | EUR 443M      | 25.5%               |

Probability-weighted fair value (25/50/25 Bull/Base/Bear): **~EUR 100 (+74%)**.

### Key Investment Pillars

1. **Massive underpenetrated smart home TAM** with differentiated open-ecosystem, low-price-point products
2. **Device-to-cloud flywheel** — nascent subscription revenue (Shelly Cloud) that could transform the margin profile
3. **Fortress balance sheet** with net cash, low capex, and a structurally advantaged 10% Bulgarian corporate tax rate

## Methodology

- **15-year, three-phase DCF** (detailed 2026-2030, transition 2031-2035, maturation 2036-2040) with a Damodaran-convergence terminal value (WACC 10.0%, terminal growth 3.0%, terminal ROIC 15-24%). Chosen over a 5-year DCF because the latter placed ~80% of value in a terminal computed off a cash flow still growing ~17% — truncating a decade of compounding.
- SBC-expensed unlevered FCF (NOPAT on reported EBIT; equity ÷ current diluted shares)
- Bottom-up operating model anchored in device shipment growth, ASP trends, and cloud/subscription revenue
- Cross-checked with a year-5 (2030) EV/EBITDA and P/E exit-multiple *floor* (interim FCF included), plus an implied terminal EV/EBITDA sanity check
- Scenario analysis across bull, base, and bear cases

## Data Sources

- [Investor Relations](https://shellygroup.com/investors)
- [Bulgarian Stock Exchange (SLYG)](https://www.bse-sofia.bg/en/issuer-profile/SLYG)
- [Annual & Quarterly Reports](https://shellygroup.com/investors/reports)
- [Company Website](https://shellygroup.com/)
- Analyst coverage: Montega AG (Buy, EUR 61), Berenberg (Buy, EUR 73)

## Disclaimer

This repository is an analytical exercise based on publicly available financial data and a proprietary financial model. It is **not investment advice**. All projections are estimates and subject to significant uncertainty. Past performance does not guarantee future results. Shelly Group trades on the Bulgarian Stock Exchange with limited liquidity, and is subject to hardware cyclicality, FX, and competitive risks. The author may hold positions in the securities discussed.
