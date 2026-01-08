# FedEx-DCA-SMART
An AI-driven platform to digitize and optimize Debt Collection Agency (DCA) management by automating case prioritization, urgency classification, SLA tracking, and performance analytics through real-time dashboards.
## Problem Statement
FedEx manages thousands of overdue customer accounts through external Debt Collection Agencies (DCAs).
The current process is manual, spreadsheet-driven, and lacks real-time visibility, accountability,
and predictive intelligence.

## Our Solution
We propose an AI-driven DCA management platform that:
- Automatically prioritizes overdue cases
- Predicts recovery probability
- Identifies SLA breach risks
- Evaluates DCA performance using data-driven KPIs

## Key Features
- AI-based case prioritization & urgency classification
- Recovery probability prediction
- SLA risk scoring
- DCA performance analytics & leaderboard
- Scalable and explainable scoring logic

## Architecture Overview
Input Data → AI Scoring Engine → Priority & Risk Buckets → Allocation Decisions → Analytics Dashboard

## Technology Stack
- Python
- Pandas, NumPy
- Matplotlib
- Streamlit (UI)
- Jupyter Notebook

## Repository Structure
```text
FedEx-DCA-SMART/
│
├── app.py                 # Streamlit UI (main entry point)
│
├── models/                # AI scoring & prioritization logic
│   ├── priority_engine.py
│   └── urgency_classifier.py
│
├── analytics/              # DCA performance analytics & KPIs
│   ├── dca_performance.py
│   └── visualizations.py
│
├── data/                   # Sample / synthetic input data
│   └── sample_cases.csv
│
├── FEDEX1.ipynb            # End-to-end prototype notebook
├── requirements.txt        # Required libraries
├── README.md               # Project documentation
```

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
