# Orchestrated Data Engineering Pipeline

## Overview
This project is an orchestrated data engineering pipeline featuring dependent tasks, retries, timeouts, data quality validations, quarantine handling, idempotency, and comprehensive audit/reconciliation reporting.

## Setup & Execution

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt


Generate Datasets:
python generator.py


Run the Pipeline:
python pipeline.py


Run Tests:
pytest -v
