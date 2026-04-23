# Trader Behavior vs Bitcoin Fear & Greed Sentiment Analysis

This project analyzes whether crypto traders behave differently under Fear vs Greed market sentiment conditions using historical transaction data and Bitcoin Fear & Greed Index values.

Key objectives:

- Compare profitability across sentiment regimes
- Measure leverage, trade size, and long/short bias shifts
- Segment traders by frequency, profitability, and consistency
- Generate actionable trading rules based on market psychology

## Key Findings

- Greed periods showed slightly higher average realized profits.
- Fear periods had stronger win rates.
- Traders used larger average position sizes during Fear.
- Fear favored long exposure; Greed favored short exposure.
- High win rate alone did not guarantee top profitability.
- A small group of traders generated outsized total profits.

I built a behavioral analytics project using crypto trading data and Bitcoin Fear & Greed sentiment data.

I wanted to understand whether trader profitability and decision-making changed based on market psychology.

I cleaned and merged large datasets, engineered sentiment regimes, compared PnL and win rates, and segmented traders by performance.

One interesting insight was that Fear periods had higher win rates, while Greed periods had slightly higher profits, showing that confidence and profitability are not always aligned.

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/iamkaus/assignment.git
cd assignment

### 2. Create virtual environment (Optional if using pycharm)
```bash
python -m venv .venv
source .venv/bin/activate

For Windows
```bash
.venv\Scripts\activate

### 3. Install dependencies 
```bash
pip install -r requirement.txt

### 4. Launch Jupyter Notebook
```bash
jupyter notebook

### 5. Rub the cells 
Open the notebook file and run all cells to reproduce the complete analysis.