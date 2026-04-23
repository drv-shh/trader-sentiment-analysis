# Trader Behavior vs Market Sentiment
This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance using real execution-level trading data.

The goal is to understand:

Do traders perform better in Fear or Greed?
How does behavior (risk, activity) change with sentiment?
Which types of traders perform best under different conditions?

## Setup
### 1. Clone the repository

```bash
git clone <your-repo-link>
cd trader-sentiment-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```
---

## Project Structure

```bash
data/        # input CSV files  
notebook/    # analysis notebook  
outputs/     # saved charts  
```

---
## How to Run
### Option 1: Jupyter Notebook (recommended)

```bash
jupyter notebook
```
* Open: `notebook/main.ipynb`
* Run all cells (top → bottom)
---
### Option 2: VS Code
* Open project folder
* Open `main.ipynb`
* Click **Run All**

---

## Output
After running:
* Charts will be saved in `Outputs/`
* Key results will be printed in the notebook

---

## Notes

* Ensure CSV files are inside `Data/` folder
* Update file paths if running from a different directory

Methodology

1. Data Preparation
2. Feature Engineering
3. Analysis
