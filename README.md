# Chaney Place Townhomes — BI Dashboard

An interactive Business Intelligence dashboard for the Chaney Place Townhomes underwriting model, built with Streamlit and Plotly.

## Features

- **Deal Overview** — Key investment metrics (IRR, equity multiple, cap rates, purchase price) and projected NOI/cash flow charts
- **Property Cash Flow** — Annual revenue, expense, and NOI projections with occupancy trends
- **Historical Performance** — Trailing period (T12/T9/T6/T3/T1) comparisons vs. Pro Forma
- **Monthly T12 Detail** — Month-by-month actuals for income, expenses, and NOI
- **Sources & Uses** — Capital structure at closing with pie charts and tables
- **Sensitivity Analysis** — Purchase price and exit cap rate sensitivity on IRR and equity multiple

## Running Locally

```bash
pip install -r requirements.txt
streamlit run dashboard.py
```

## Data Source

Data is sourced from the redIQ underwriting model: `Chaney_Place_Townhomes_0757_UNPROTECTED.xlsm`

**Property:** 1060 Southeast Chaney Place Drive, Huntsville, AL  
**Units:** 80 (63 × 2BR + 17 × 3BR)  
**Year Built:** 2014
