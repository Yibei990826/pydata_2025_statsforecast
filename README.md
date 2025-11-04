# PyData 2025 — StatsForecast Demo
This repository contains the demo notebook presented at PyData Seattle 2025, showcasing how to build fast, interpretable, and scalable retail demand forecasts using StatsForecast, an open-source Python library developed by Nixtla.

## Overview

The notebook walks through a complete forecasting workflow — from model setup and cross-validation to conformal prediction and comparison with TimeGPT-2, Nixtla’s foundation model for time series forecasting.


## Environment Setup
1️⃣ Clone the repo
```
git clone https://github.com/<your-username>/pydata_2025_statsforecast.git
cd pydata_2025_statsforecast
```

2️⃣ Install dependencies
```
pip install -U pip
pip install -e .
```

3️⃣ Configure API keys

Create a .env file in the project root. Get your API key here::
```
NIXTLA_API_KEY=your_nixtla_api_key_here
```
