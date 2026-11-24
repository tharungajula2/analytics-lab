# Retail Credit Risk

A Python project covering the retail credit-risk chain: PD scorecard, LGD, EAD, monitoring, ECL and Basel-style capital formulas.

## What's inside

- WoE/IV binning and a logistic PD model with a points-based scorecard.
- LGD and EAD building blocks and monitoring checks.
- ECL and Basel capital calculations as illustrations.
- Unit tests on synthetic data, plus notebooks and saved historical outputs.

## Status

Prototype. The original LendingClub data is not in the repo; saved results are historical and not reproduced. ECL and capital figures are illustrations.

## Built with

Python, pandas, statsmodels, scikit-learn, Jupyter.

## Run it

```
pip install -r requirements.txt
python -m unittest discover -s tests
```
