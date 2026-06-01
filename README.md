# Pionix Scenarios Notebook Setup

This workspace is configured for Jupyter notebooks with API calls.

## Setup

1. Create and activate the virtual environment:
  - `python3 -m venv .venv`
  - `source .venv/bin/activate`
2. Install dependencies:
  - `pip install -r requirements.txt`
3. Register the Jupyter kernel (once):
  - `python -m ipykernel install --user --name=pionix-scenarios --display-name="pionix-scenarios"`
4. Copy `.env.example` to `.env` and set station id:
  - `cp .env.example .env`
5. Open one of the scenario notebooks in `notebooks/` and run the cells.

## Scenario notebooks

- `notebooks/charging_flow.ipynb` — Normal session: plugin → authorize → charge → plugout
