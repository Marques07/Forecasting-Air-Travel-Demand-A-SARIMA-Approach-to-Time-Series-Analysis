[🇺🇸 English Version](README.md)
 
# ✈️ Previsão de Passageiros Aéreos com SARIMA
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-3B82F6?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![Licença](https://img.shields.io/badge/Licença-MIT-blue?style=for-the-badge)
 
Previsão do número de passageiros aéreos internacionais para 1961 utilizando modelo SARIMA com transformação Box-Cox.
 
---
 
## 📋 Descrição
 
Este projeto aplica um modelo SARIMA (Seasonal AutoRegressive Integrated Moving Average) para prever o número mensal de passageiros aéreos internacionais. O dataset contém registros de 1949 a 1960, e o objetivo é prever os 12 meses de 1961.
 
O projeto cobre o pipeline completo de modelagem de séries temporais: análise exploratória, estabilização de variância, teste de estacionaridade, seleção de parâmetros, ajuste do modelo, validação e previsão.
 
---
 
## 🛠️ Construído Com
 
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
---
 
## 📦 Dataset
 
- **Fonte:** [Kaggle — AirPassengers](https://www.kaggle.com/datasets/rakannimer/air-passengers)
- **Descrição:** Totais mensais de passageiros aéreos internacionais de 1949 a 1960
- **Arquivo:** `airpassengers.csv` — coloque na mesma pasta do notebook
---
 
## ⚙️ Como Executar
 
### Pré-requisitos
 
```bash
pip install pandas numpy matplotlib statsmodels
```
 
### Passos
 
1. Clone o repositório
```bash
git clone https://github.com/Marques07/airpassengers-sarima.git
```
 
2. Coloque o arquivo `airpassengers.csv` na pasta do projeto
3. Abra e execute o notebook
```bash
jupyter notebook Sarima1.ipynb
```
 
---
 
## 📊 Resultados
 
| Métrica | Valor |
|---------|-------|
| MAPE | ~10% |
| Intervalo de Confiança | 95% |
| Período Previsto | 12 meses (1961) |
 
Os valores reais permaneceram dentro do intervalo de confiança de 95% durante todo o período de previsão. O diagnóstico dos resíduos confirmou que os erros se comportam como ruído branco.
 
---
 
## 📄 Licença
 
Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.