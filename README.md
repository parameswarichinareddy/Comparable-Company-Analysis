# Comparable Company Analysis Models

A professional investment-banking portfolio covering **Trading Comparable Company Analysis (Trading Comps)** for Airbus and LVMH.

## Models

| Company | Workbook | Focus |
|---|---|---|
| Airbus | `models/Airbus_Trading_Comps.xlsx` | Trading multiples, comparable-company benchmarking and implied valuation |
| LVMH | `models/LVMH_Trading_Comps.xlsx` | Trading multiples, luxury-sector benchmarking and implied valuation |

## Core investment-banking techniques

- Comparable-company selection and benchmarking
- LTM / TTM financial metric normalization
- Enterprise Value and Equity Value analysis
- EV / Revenue and EV / EBITDA multiples
- Mean and median multiple analysis
- Selected-multiple valuation
- Implied Enterprise Value and Equity Value
- Implied share-price analysis
- Sensitivity analysis
- Source documentation and assumptions discipline
- Integrated model quality control

## Repository structure

```text
.
├── models/
│   ├── Airbus_Trading_Comps.xlsx
│   └── LVMH_Trading_Comps.xlsx
├── .github/
│   └── workflows/
│       └── validate-valuation-models.yml
└── README.md
```

## Automated quality control

GitHub Actions validates the valuation workbooks on every push and pull request. The workflow checks that the Excel files exist, open successfully, contain their expected core worksheets, and do not contain obvious Excel error literals such as `#REF!`, `#DIV/0!`, `#VALUE!`, or `#NAME?`.

## Investment-banking skills demonstrated

**Valuation:** Trading Comps, EV/Revenue, EV/EBITDA, implied valuation and equity-value bridges.

**Financial analysis:** peer benchmarking, metric normalization, assumptions and sensitivity analysis.

**Professional workflow:** structured Excel models, source tracking, presentation-ready outputs and automated repository-level quality control.

## Disclaimer

These models are for educational and portfolio purposes only and are not investment advice. Market data, company metrics, assumptions and valuation outputs are time-sensitive and should be independently verified before real-world use.
