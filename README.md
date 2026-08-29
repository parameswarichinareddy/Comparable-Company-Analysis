# Comparable Company Analysis Models

A portfolio of investment-banking-style **Comparable Company Analysis (CCA / Trading Comps)** models for Airbus and LVMH.

## Models

| Company | Workbook | Focus |
|---|---|---|
| Airbus | `models/Airbus_Trading_Comps.xlsx` | Trading multiples, comparable-company benchmarking and implied valuation |
| LVMH | `models/LVMH_Trading_Comps.xlsx` | Trading multiples, luxury-sector benchmarking, implied valuation and industry dashboard |

## What the models demonstrate

- Comparable-company selection and benchmarking
- LTM / TTM financial metric normalization
- Enterprise Value and Equity Value analysis
- EV / Revenue and EV / EBITDA trading multiples
- Mean and median trading-multiple analysis
- Selected-multiple valuation
- Implied Enterprise Value and Equity Value
- Implied share-price analysis
- Valuation sensitivity / cross-checks
- Source documentation and assumptions discipline
- Sector-specific benchmarking and dashboard presentation

## Workbook structure

### Airbus
- **Model Guide** — methodology, definitions and sources
- **Trading Comps** — comparable-company inputs and trading multiples
- **Implied Valuation** — selected multiples and implied valuation outputs

### LVMH
- **Model Guide** — methodology and model instructions
- **Assumptions** — key dates, conventions and modelling assumptions
- **Sources** — source documentation
- **Trading Comps** — comparable-company inputs and valuation multiples
- **Implied Valuation** — implied valuation outputs
- **Luxury Industry Dashboard** — sector and brand-portfolio overview

## Repository structure

```text
.
├── models/
│   ├── Airbus_Trading_Comps.xlsx
│   └── LVMH_Trading_Comps.xlsx
├── .github/
│   └── workflows/
│       └── validate-comps.yml
└── README.md
```

## Automated quality control

GitHub Actions validates that both workbooks are present, readable as Excel files, contain the expected core worksheets, and do not contain obvious Excel error literals such as `#REF!`, `#DIV/0!`, or `#VALUE!`.

## Investment-banking skills demonstrated

**Valuation:** Trading Comps, EV/Revenue, EV/EBITDA, implied valuation, equity-value bridge.

**Financial analysis:** peer benchmarking, metric normalization, assumptions, market-data organization and sensitivity analysis.

**Professional workflow:** structured Excel models, documentation, source tracking and automated repository-level quality control.

## Disclaimer

These models are for educational and portfolio purposes only and are not investment advice. Market data, company metrics, assumptions and valuation outputs are time-sensitive and should be independently verified before real-world use.
