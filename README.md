# Comparable Company Analysis Models

A professional investment-banking portfolio covering **Trading Comparable Company Analysis (Trading Comps)** and **Precedent Transaction Analysis (PTA)**.

## Models

| Company / Case | Workbook | Focus |
|---|---|---|
| Airbus | `models/Airbus_Trading_Comps.xlsx` | Trading multiples, comparable-company benchmarking and implied valuation |
| LVMH | `models/LVMH_Trading_Comps.xlsx` | Trading multiples, luxury-sector benchmarking and implied valuation |
| Baker Hughes | `models/Baker_Hughes_Chart_Precedent_Transactions_Analysis_Model.xlsx` | Precedent transactions, transaction multiples, premium analysis and implied PTA valuation |

## Baker Hughes — Precedent Transaction Analysis

The Baker Hughes workbook is structured as a complete transaction-comps valuation workflow:

- **Dashboard** — key outputs and transaction-level overview
- **Transaction Overview** — deal characteristics and transaction context
- **Target Financials** — target operating and financial metrics
- **Target Capitalization** — capital structure and equity-value bridge
- **Precedent Transactions** — screened transaction set and deal inputs
- **Transaction Multiples** — transaction valuation multiples and benchmarking
- **Premium Analysis** — acquisition-premium analysis
- **PTA Valuation** — implied valuation using selected precedent multiples
- **Sensitivity Analysis** — valuation sensitivity to key assumptions
- **Football Field** — visual valuation range presentation
- **Transaction Screening** — precedent transaction screening framework
- **Sources & Checks** — source tracking and model integrity checks

## Core investment-banking techniques

- Comparable-company selection and benchmarking
- Precedent transaction screening
- Transaction value and deal-date analysis
- LTM / TTM financial metric normalization
- Enterprise Value and Equity Value analysis
- EV / Revenue and EV / EBITDA multiples
- Mean and median multiple analysis
- Selected-multiple valuation
- Premium analysis
- Implied Enterprise Value and Equity Value
- Implied share-price analysis
- Sensitivity analysis
- Football field valuation presentation
- Source documentation and assumptions discipline
- Integrated model quality control

## Repository structure

```text
.
├── models/
│   ├── Airbus_Trading_Comps.xlsx
│   ├── LVMH_Trading_Comps.xlsx
│   └── Baker_Hughes_Chart_Precedent_Transactions_Analysis_Model.xlsx
├── .github/
│   └── workflows/
│       └── validate-valuation-models.yml
└── README.md
```

## Automated quality control

GitHub Actions validates the valuation workbooks on every push and pull request. The workflow checks that the Excel files exist, open successfully, contain their expected core worksheets, and do not contain obvious Excel error literals such as `#REF!`, `#DIV/0!`, `#VALUE!`, or `#NAME?`.

## Investment-banking skills demonstrated

**Valuation:** Trading Comps, Precedent Transactions, EV/Revenue, EV/EBITDA, implied valuation and equity-value bridges.

**Financial analysis:** peer benchmarking, transaction screening, metric normalization, premium analysis, assumptions and sensitivity analysis.

**Professional workflow:** structured Excel models, source tracking, presentation-ready outputs and automated repository-level quality control.

## Disclaimer

These models are for educational and portfolio purposes only and are not investment advice. Market data, company metrics, assumptions and valuation outputs are time-sensitive and should be independently verified before real-world use.
