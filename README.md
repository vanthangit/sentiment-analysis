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
│   │   ├── linearsvm_model
│   │   ├── logisticregression_model
│   │   └── randomforest_model
│   └── dl/
│       ├── bilstm_model.pt
|       ├── lstm_model.pt
│       └── bert_sentiment_model/
│           ├── logs/
│           ├── results/
│           ├── config.json
│           ├── model.safetensors
│           ├── special_tokens_map.json
│           ├── tokenizer_config.json
│           ├── tokenizer.json
│           └── vocab.txt
│
├── 📁 requirements/
│   └── requirements.txt                # pyspark, numpy, pandas, matplotlib, seaborn, nltk,...
│
├── config.yaml                         # Đường dẫn dữ liệu, thông số mô hình, tham số Spark
├── README.md                           # Giới thiệu project, hướng dẫn chạy
└── .gitignore
```
