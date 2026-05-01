[🇧🇷 Versão em Português](README.pt.md)
 
# ✈️ AirPassengers SARIMA Forecast
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-3B82F6?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
 
Forecasting international airline passenger numbers for 1961 using a SARIMA model with Box-Cox transformation.
 
---
 
## 📋 Description
 
This project applies a SARIMA (Seasonal AutoRegressive Integrated Moving Average) model to forecast monthly international airline passenger numbers. The dataset contains records from 1949 to 1960, and the goal is to predict the 12 months of 1961.
 
The project covers the full time series modeling pipeline: exploratory analysis, variance stabilization, stationarity testing, parameter selection, model fitting, validation, and forecasting.
 
---
 
## 🛠️ Built With
 
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
---
 
## 📦 Dataset
 
- **Source:** [Kaggle — AirPassengers](https://www.kaggle.com/datasets/rakannimer/air-passengers)
- **Description:** Monthly totals of international airline passengers from 1949 to 1960
- **File:** `airpassengers.csv` — place it in the same folder as the notebook
---
 
## ⚙️ How to Run
 
### Prerequisites
 
```bash
pip install pandas numpy matplotlib statsmodels
```
 
### Steps
 
1. Clone the repository
```bash
git clone https://github.com/Marques07/airpassengers-sarima.git
```
 
2. Place `airpassengers.csv` in the project folder
3. Open and run the notebook
```bash
jupyter notebook Sarima1.ipynb
```
 
---
 
## 📊 Results
 
| Metric | Value |
|--------|-------|
| MAPE | ~10% |
| Confidence Interval | 95% |
| Forecast Period | 12 months (1961) |
 
The real values stayed within the 95% confidence interval throughout the forecast period. Residual diagnostics confirmed the model errors behave as white noise.
 
---
 
## 📄 License
 
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.