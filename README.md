# Automated Market Research (Poshmark example)
Developed by Michael Phipps, 2025

A Python and github actions-based method to extract market data on a scheduled (daily) cadence. Script pulls data and updates (appends to previous data) via connected google sheet, entirely automated. 

Automated updates to sheets required authentication.

Example: Pulling top mens coat brands sold each day, when coat sold between $100-$500 (example output in posh_test.ipynb).

## Project Structure

* **`poshmark_data_pull.py`**: The core Python script responsible for automating the extraction of market and product data from Poshmark. 
* **`posh_test.ipynb`**: Jupyter notebook - testing the data extraction logic
* **`requirements.txt`**: All Python dependencies and libraries used to run the scripts & notebooks.

### Install

1. Clone repo:
   ```bash
   git clone [https://github.com/mp321/automated-market-research-example.git](https://github.com/mp321/automated-market-research-example.git)
   cd automated-market-research-example
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Data Pull
To execute py script, run the main script from your terminal:
```bash
python poshmark_data_pull.py
```

### Automation
Gitactions with appropriate authentication (including google sheet edit connection)

## Built With
* **Python** - Core logic and automation
* **Jupyter Notebook** - Data exploration / testing
