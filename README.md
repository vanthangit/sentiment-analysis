```bash
Sentiment_Analysis/
│
├── 📁 data/
│   ├── raw/                     # Dữ liệu gốc (Amazon Reviews - CSV/JSON)
│   │   └── amazon_reviews_raw.csv
│   ├── processed/               # Dữ liệu sau xử lý với Spark
│   │   └── amazon_reviews_clean.parquet
│   ├── external/               
│   │   └── NRC.csv
│
├── 📁 notebooks/
│   ├── sentiment_analysis.ipynb
│
├── 📁 models/
│   ├── ml/
│   │   ├── logistic_regression
│   │   ├── svm_model
│   │   └── random_forest
│   └── dl/
│       ├── lstm_model.pt
│       └── bert_model/
│           ├── config.json
│           └── pytorch_model.bin
│
├── 📁 requirements/
│   └── requirements.txt                # pyspark, numpy, pandas, matplotlib, seaborn, nltk,...
│
├── config.yaml                         # Đường dẫn dữ liệu, thông số mô hình, tham số Spark
├── README.md                           # Giới thiệu project, hướng dẫn chạy
└── .gitignore
```
