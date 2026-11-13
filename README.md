<p align="center">
  <img src="header.svg" width="100%" alt="Nadir Sayed. Market finance student, M1 Financial Markets, ESCE Paris. Available for a summer internship, June to August 2027.">
</p>

I study market finance and I like numbers that reconcile. Two finance internships taught me
month-end closes, reconciliations and variance analysis. I now apply the same discipline to
market positions: price them, explain the day's P&L, measure the risk, and write down every
assumption.

## Featured project

### [minibook](https://github.com/nadirsayed/minibook): a derivatives book, risk-managed every business day

[![CI](https://github.com/nadirsayed/minibook/actions/workflows/ci.yml/badge.svg)](https://github.com/nadirsayed/minibook/actions/workflows/ci.yml)
[![Daily report](https://github.com/nadirsayed/minibook/actions/workflows/daily.yml/badge.svg)](https://github.com/nadirsayed/minibook/actions/workflows/daily.yml)

<table>
  <tr>
    <td width="50%" valign="top">
      <b>The book</b><br>
      A 5Y EUR interest rate swap, EUR/USD and USD/JPY forwards, and four European options
      on equity indices, traded on 2 November 2026.
      <br><br>
      <b>Every TARGET business day</b><br>
      Valuation from public data (ECB, U.S. Treasury, Japan MoF), Greeks and DV01, actual
      vs explained P&amp;L, 1-day 99% VaR and 97.5% ES by historical simulation, and a PDF
      risk report committed by GitHub Actions.
      <br><br>
      <b>How it is built</b><br>
      Curves, calendars, pricers and risk written from scratch with numpy and scipy.
      QuantLib is used only in the tests, as an independent cross-check.
      <br><br>
      <a href="https://github.com/nadirsayed/minibook/tree/main/reports"><b>Daily reports</b></a> ·
      <a href="https://github.com/nadirsayed/minibook/blob/main/docs/methodology.md"><b>Methodology</b></a> ·
      <a href="https://github.com/nadirsayed/minibook/blob/main/docs/decisions.md"><b>Design decisions</b></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/nadirsayed/minibook/tree/main/reports">
        <img src="https://raw.githubusercontent.com/nadirsayed/minibook/main/docs/img/report_2026-11-11_p4.png" alt="Page 4 of the 11 November 2026 report: VaR and ES histogram, history and worst scenarios">
      </a>
    </td>
  </tr>
</table>

## Project blotter

| Project | What it does | Tools | Status |
|---|---|---|---|
| [**minibook**](https://github.com/nadirsayed/minibook) | Daily valuation, Greeks, P&L explain, VaR/ES and PDF report for a seven-instrument book | Python, numpy, scipy, GitHub Actions | 🟢 Live, daily since Nov 2026 |
| **Reconciliation tool** | Imports two extracts, matches them automatically and lists the breaks | Excel VBA, Power Query | 🟡 In progress |
| **Pre-registered market log** | Timestamped probabilities ahead of Fed, ECB and BoJ decisions, compared with market pricing and scored with the Brier score. Simulation only, no real capital | Python, Git | 🟡 In progress |

## Toolbox

- **Markets:** interest rate swaps, FX forwards, options and Greeks · zero curves, duration, DV01 · historical VaR, Expected Shortfall · P&L explain
- **Banking and control:** bank balance sheet, liquidity (LCR, NSFR), Basel · month-end close, reconciliations, variance analysis, reporting
- **Tools:** Python (pandas, numpy, matplotlib, automated tests) · Excel (Power Query, VBA) · Power BI (DAX) · Git and GitHub Actions

## Background

- **SAMOUH**, Casablanca (2026): finance and accounting intern. Month-end closes, bank
  reconciliations, budget variance control by project.
- **The Kooples**, Paris (2025): reporting and performance analysis. Weekly Excel reporting
  and variance analysis vs budget and prior year, on EUR 18.6m of revenue and 148,000 orders.
- **ESCE International Business School**, Paris: Programme Grande École, Financial Markets
  (graduating 2028). Exchange semester at **Kansai Gaidai University**, Osaka (Jan to May 2027).
  Science preparatory year at **Université de Montréal** (2022 to 2023).
- Bloomberg Market Concepts · French and Arabic (native), English (C1, IELTS 7.0).

## Contact

Open to a **summer internship, June to August 2027**, in market risk, product control,
middle office or ALM/treasury (France, Morocco or abroad), then an end-of-studies
internship from January 2028.

[LinkedIn](https://www.linkedin.com/in/nadirsayed/)
