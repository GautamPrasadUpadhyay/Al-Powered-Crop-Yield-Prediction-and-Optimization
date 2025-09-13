# Al-Powered-Crop-Yield-Prediction-and-Optimization
This is for Smart India Hackathon 2025.

Layout of Our poject.

crop-yield/
├─ data/
│  └─ processed/
│     └─ train_small.csv
├─ notebooks/
│  ├─ train_lightgbm.ipynb
│  └─ uplift_backtest.ipynb
├─ src/
│  ├─ ml/
│  │  ├─ features.py
│  │  ├─ train.py
│  │  └─ models/
│  │     ├─ lightgbm_model.pkl
│  │     └─ feature_list.pkl
│  ├─ api/
│  │  ├─ weather_client.py
│  │  ├─ soil_client.py
│  │  └─ app.py
│  └─ inference/
│     └─ predictor.py
├─ frontend/
│  ├─ package.json
│  ├─ public/index.html
│  └─ src/
│     ├─ index.js
│     ├─ App.js
│     ├─ api/apiClient.js
│     ├─ components/
│     │  ├─ YieldPredictor.jsx
│     │  ├─ WhatIfSlider.jsx
│     │  └─ PredictionCard.jsx
│     ├─ i18n/translations.js
│     └─ styles/predictor.css
├─ tests/
│  ├─ test_featurizer.py
│  └─ test_predict_smoke.py
├─ requirements.txt
├─ frontend/README_FRONTEND.md
├─ Dockerfile
└─ README.md
