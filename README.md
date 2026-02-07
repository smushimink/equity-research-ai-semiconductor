# equity-research-ai-semiconductor
Equity research reports & valuation models for AI and semiconductor companies (NVDA, TSM, ASML, AVGO). Includes DCF, comps, KPI dashboards.

equity-research-ai-semiconductor/
├── README.md
├── LICENSE
├── .gitignore
├── reports/
│   ├── company/
│   │   ├── NVDA/
│   │   ├── TSM/
│   │   ├── ASML/
│   │   └── AVGO/
│   ├── industry/
│   │   ├── ai-infrastructure/
│   │   ├── semiconductor-cycle/
│   │   └── competitive-landscape/
│   └── templates/
├── models/
│   ├── valuation/
│   │   ├── dcf/
│   │   ├── comps/
│   │   └── sotp/
│   ├── drivers/
│   └── sensitivity/
├── data/
│   ├── raw/
│   ├── processed/
│   ├── sources.md
│   └── data_dictionary.md
├── notebooks/
│   ├── 01_data_pull_clean.ipynb
│   ├── 02_kpi_dashboard.ipynb
│   ├── 03_valuation_inputs.ipynb
│   └── 04_sensitivity.ipynb
├── src/
│   ├── __init__.py
│   ├── fetch.py
│   ├── clean.py
│   ├── kpis.py
│   ├── valuation.py
│   └── plots.py
└── docs/
    ├── methodology.md
    ├── risk-framework.md
    ├── ai-semi-value-chain.md
    └── glossary.md
