# financial-anomaly-detector

A modular project for detecting anomalies in financial data from multiple sources (like Yahoo Finance and Binance), processing features, training models, and visualizing results on a dashboard.

## 📁 Project Structure

```text
financial-anomaly-detector/
├── data_ingest/
│   ├── fetch_yfinance.py
│   ├── fetch_binance.py
│   └── requirements.txt
├── db/
│   └── mongo_schema.md
├── features/
│   ├── compute_features.py
│   └── feature_tests.py
├── models/
│   ├── train.py
│   ├── predict.py
│   └── requirements.txt
├── dashboard/
│   └── app.py
├── infra/
│   ├── Dockerfile
│   └── deploy.md
├── scripts/
│   ├── run_ingest.sh
│   └── run_features.sh
├── tests/
│   └── unit_tests.py
├── Makefile
└── README.md



