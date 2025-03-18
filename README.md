# Analysis of the Bitcoin's price data
[Dataset source](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)

In order to run the notebook you must:
- have a Unix-like system (Windows support coming with docker)
- have a valid 3.10+ python version
- clone the repo
- create a new virtual environment inside of the project's folder by running: `python3 -m venv .venv`
- activate the `.vevn` with `source <path-to-project>/.venv/bin/activate` (assuming that you have bash, sh or zsh)
- install the `requirements.txt` with `pip install -r requirements.txt`
- have your `kaggle.json` API key (for accessing [kaggle.com](https://www.kaggle.com/)) in your home directory ([More](https://github.com/Kaggle/kagglehub#option-3-read-credentials-from-kagglejson))
---
### This sript answers the Question: If you held Bitcoin for X days, what would your return be?

These are calculated by averaging the X days return over the bitcoin price data from 2012 to 2024.

Enjoy!
