## Adrien Liao

Student at **Imperial College London**, looking for graduate roles in **quantitative research, data science and machine learning**.

I like building things from first principles and then trying to break them: pricing models checked against closed forms, backtests checked for lookahead bias, Sharpe ratios checked for luck, and machine learning results checked for leakage.

### Featured projects

| Project | What it shows | Stack |
| --- | --- | --- |
| [**deep-hedging**](https://github.com/adrienliao/deep-hedging) | A neural network learns to hedge a short option under transaction costs by minimising CVaR directly. It rediscovers Black-Scholes delta when trading is free, and cuts tail risk by 15% against delta hedging at 50 bp of costs. | PyTorch |
| [**ml-return-prediction**](https://github.com/adrienliao/ml-return-prediction) | Cross-sectional stock ranking with gradient boosting, ridge and an MLP. A shuffled K-fold makes the model look 4x better than it is; with purged walk-forward validation it keeps a significant IC and a 0.50 net Sharpe. | scikit-learn, pandas |
| [**financial-news-nlp**](https://github.com/adrienliao/financial-news-nlp) | Fine-tuned transformers reach 88% accuracy on financial headline sentiment, ahead of FinBERT. An event study on 55k headlines shows the market reacts before you can trade, and that bad news partially reverses. | Hugging Face, PyTorch |
| [**walk-forward-backtester**](https://github.com/adrienliao/walk-forward-backtester) | Backtesting on 22 years of sector ETF data with a turnover cost model, lookahead tests, block bootstrap and the deflated Sharpe ratio. | pandas, scipy |
| [**option-pricing-engine**](https://github.com/adrienliao/option-pricing-engine) | Black-Scholes and Greeks, implied vol, American options on trees, Monte Carlo with variance reduction and error bars, discrete vs continuous barriers. 85 tests against analytic results. | numpy, scipy |
| **Polymarket order book recorder** (private, in progress) | Async service that discovers football prop markets, streams their order books over WebSocket and stores every change in SQLite, as the data layer for a market making model. | asyncio, SQLite |

### Toolbox

* **Languages** Python, SQL
* **ML and data** PyTorch, Hugging Face transformers, scikit-learn, pandas, numpy, scipy
* **Engineering** pytest, GitHub Actions, asyncio, reproducible experiments
* **Quant** derivatives pricing, Monte Carlo methods, backtesting, statistics for overfitting

### Contact

adrien.liao25@imperial.ac.uk
