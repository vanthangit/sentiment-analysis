Sentiment_Analysis/
│
├── 📁 data/
│   ├── raw/                     # Dữ liệu gốc (Amazon Reviews - CSV/JSON)
│   │   └── amazon_reviews_raw.csv
│   ├── processed/               # Dữ liệu sau xử lý với Spark
│   │   └── amazon_reviews_clean.parquet
│
├── 📁 notebooks/
│   ├── sentiment_analysis.ipynb
│
├── 📁 models/
│   ├── ml/
│   │   ├── logistic_regression.pkl
│   │   ├── svm_model.pkl
│   │   └── random_forest.pkl
│   └── dl/
│       ├── lstm_model.pt
│       └── bert_model/
│           ├── config.json
│           └── pytorch_model.bin
│
├── 📁 reports/
│   ├── proposal.docx
│   ├── final_report.docx
│   └── presentation.pptx
│
├── 📁 requirements/
│   └── requirements.txt                # pyspark, numpy, pandas, matplotlib, seaborn, nltk,...
│
├── config.yaml                         # Đường dẫn dữ liệu, thông số mô hình, tham số Spark
├── README.md                           # Giới thiệu project, hướng dẫn chạy
└── .gitignore
