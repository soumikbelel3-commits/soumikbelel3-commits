<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="Soumik Belel — data analyst becoming a data scientist" src="./assets/banner-light.svg">
</picture>

I'm a data analyst growing into data science. I take a messy dataset and a business question and
work through the whole analysis: SQL and Python pipelines, cleaning, EDA, statistics,
machine-learning models, and dashboards people can make decisions from.

Financial market data is the domain I know best. I'm putting all of it to work in
**Omni Terminal**, the market-analytics platform I'm building for Indian traders.

**[LinkedIn](https://www.linkedin.com/in/soumik-belel)** · **[X](https://x.com/SoumikBelel)** · **[Email](mailto:soumikbelel3@gmail.com)**

> **Open to remote Data Analyst / Data Scientist roles**, working from Kolkata. I'm strongest with financial data, and I'm just as comfortable with general analytics and ML work. Reach me at [soumikbelel3@gmail.com](mailto:soumikbelel3@gmail.com).

---

## Data I've worked with

|  |  |  |
| :--- | :--- | :--- |
| **5.8M** US domestic flights | **1.2M+** crypto perpetual-futures trades | **150K+** IPL ball-by-ball deliveries |
| **10K** bank customers | **10K+** global pharma shipments | **5K** shipments scored for disruption risk |

---

## Currently

|  |  |
| :--- | :--- |
| **Learning** | Machine learning: model selection, validation and explainability · statistics for inference · data engineering (pipelines, SQL at scale) · CFA Level 1–3 material, for the concepts rather than the charter. |
| **Building** | **Omni Terminal**: an end-of-day NSE/BSE data pipeline, options-chain and open-interest analytics, factor scoring, screening and backtesting. |
| **Writing** | Daily markets and finance content as **The Architect** (English) and **Baniyon Ka Guruji** (Hindi/Hinglish). |

---

## How I work

Every project starts with a question and ends with a decision. In between, I clean and check the
data before I trust it, look for the simplest explanation first, and validate models on data they
haven't seen. I also report results that disappoint: one of my models below predicts next-day
direction at roughly coin-flip accuracy, and that result is in the write-up.

---

## Selected work

### Machine learning & data science

| Project | Question → result | Stack |
| :--- | :--- | :--- |
| **[European Bank Churn](https://github.com/soumikbelel3-commits/european-bank-churn)** | Which customers will leave, and why? Compared 5 classifiers on 10K customers; Gradient Boosting was the champion (ROC-AUC 0.857, best F1). Explained with SHAP and served through a what-if risk simulator. | Python · scikit-learn · XGBoost · SHAP · Streamlit |
| **[Global Supply Chain Risk](https://github.com/soumikbelel3-commits/Global_supply_chain_risk_2026-)** | Can shipment disruption be predicted? Random Forest reached **AUC 0.817** on 5,000 shipments. Lead time, weather and geopolitical risk carry 42% of the model's importance. | Python · SQL · scikit-learn |
| **[Instructor Effectiveness Modeling](https://github.com/soumikbelel3-commits/Instructor-Effectiveness-Modeling)** | How do you measure effectiveness when there's no ground-truth label? Built a composite score across 2,000 batches and 120 instructors, then trained tier classifiers with stratified 5-fold CV. | Python · scikit-learn |
| **[Shopper Spectrum](https://github.com/soumikbelel3-commits/shopper-spectrum)** | Customer segmentation using RFM and K-Means (4 segments), plus an item-based collaborative-filtering recommender, packaged as an app. | Python · scikit-learn · Streamlit |
| **[Real Estate Investment Advisor](https://github.com/soumikbelel3-commits/real-estate-price-prediction)** | Two models: a classifier that flags good investments and a regressor that forecasts 5-year prices, with experiments tracked in MLflow. | Python · XGBoost · MLflow · Streamlit |

### Analytics & BI

| Project | Question → result | Stack |
| :--- | :--- | :--- |
| **[US Airline Performance](https://github.com/soumikbelel3-commits/us-airline-performance-analysis)** | What drives delays across 5.8M flights? Built a chunked SQL ingestion pipeline and pre-aggregated summary tables, which cut dashboard queries from **28 s to under 10 ms**. | Python · SQL · SQLite · Streamlit |
| **[Superstore Sales Analytics](https://github.com/soumikbelel3-commits/Superstore-sale-dashboard)** | Where is profit leaking? Across $2.26M of revenue, furniture runs at a 6% margin against 18% for technology. Identified **~$460K/yr** in revenue opportunities. | Python · SQL · Power BI |
| **[Retail Sales & Inventory Intelligence](https://github.com/soumikbelel3-commits/retail-sales-inventory-intelligence)** | Nine-table relational model with a Python ETL step, 7 reusable SQL views, RFM segmentation and an interactive web dashboard. | Python · SQL · Chart.js |
| **[FedEx Supply Chain EDA](https://github.com/soumikbelel3-commits/Fed-Ex-Supply-Chain)** | 10,324 shipments to 40+ countries: 88.5% arrive on time, and ocean freight is late 17.5% of the time against 9.6% for air. Includes 2 Power BI dashboards. | Python · Power BI |
| **[IPL Data Analysis](https://github.com/soumikbelel3-commits/IPL-Data-Analysis)** | 150K+ deliveries turned into a 3-page Power BI report with a relational data model and DAX measures. | Python · Power BI · DAX |
| **[Cricbuzz Live Stats](https://github.com/soumikbelel3-commits/Cricbuzz_livestats)** | Cricket stats app with a SQL analytics layer and admin CRUD. | Python · SQL · Streamlit |

### Financial & quantitative data

| Project | Question → result | Stack |
| :--- | :--- | :--- |
| **[Trader Behaviour vs Sentiment](https://github.com/soumikbelel3-commits/-trader-behavior-and-performance)** | Does market mood change how traders trade? I joined 1.2M+ trades to the Fear & Greed index. The long bias rises from 48% to 67% on Greed days, and win rate falls from 54% to 47% on Fear days. | Python · SQL · Power BI |
| **[TCS Quant Pipeline](https://github.com/soumikbelel3-commits/TCS-Quant-Trading-Guide)** | A six-stage workflow: data collection, EDA, 25+ indicators, backtests of 3 strategies, ML direction models, then VaR/CVaR and portfolio optimisation. | Python · pandas · scikit-learn · XGBoost |
| **[Gold Pre-Session Dashboard](https://github.com/soumikbelel3-commits/gold-trading-execution)** | A multi-factor briefing that runs in about 9 seconds. It covers 50+ indicators, a walk-forward-validated ML ensemble and a 20K-path Monte Carlo simulation. | Python · pandas · scikit-learn |
| **[AI Strategy Backtester](https://github.com/soumikbelel3-commits/ai-strategy-backtester)** | An event-driven backtest engine with no look-ahead. It reports 30+ performance metrics and includes Monte Carlo and walk-forward analysis. | TypeScript · React |

### Where it all goes: Omni Terminal

A research and analytics terminal for NSE/BSE. It applies everything above (ingestion, factor
models, options analytics, backtesting) to the Indian market. It explains the market and never
tells anyone what to buy. **[Take a look ↗](https://omni-terminal-nu.vercel.app)**

<sub>Stack: FastAPI · TimescaleDB · PostgreSQL · Redis · VectorBT · React</sub>

Other things I've built: [AI Resume Analyzer](https://github.com/soumikbelel3-commits/ai-resume-analyzer) ·
[ClearLedger](https://github.com/soumikbelel3-commits/clearledger) ·
[Sanatani Bhakti](https://github.com/soumikbelel3-commits/sanatani-bhakti)

---

## Toolkit

|  |  |
| :--- | :--- |
| **Languages & data** | Python · SQL · pandas · NumPy · Jupyter |
| **ML & statistics** | scikit-learn · XGBoost · statsmodels · SciPy · SHAP · MLflow |
| **BI & reporting** | Power BI · DAX · Tableau · Excel · Streamlit · Plotly |
| **Data stores & pipelines** | PostgreSQL · TimescaleDB · SQLite · Redis · pgvector · Docker |
| **Quant** | VectorBT · Alphalens · PyPortfolioOpt · py_vollib · QuantLib · FinBERT |
| **App development** | FastAPI · TypeScript · Next.js · React · Tailwind |

---

<sub>Kolkata, India · [linkedin.com/in/soumik-belel](https://www.linkedin.com/in/soumik-belel) · [@SoumikBelel](https://x.com/SoumikBelel) · [soumikbelel3@gmail.com](mailto:soumikbelel3@gmail.com)</sub>
