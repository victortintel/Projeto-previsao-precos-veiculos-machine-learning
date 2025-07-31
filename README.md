# Previsão de Preços de Veículos com Machine Learning 🚗📊

Projeto de Ciência de Dados com foco em modelagem preditiva para estimar o valor de venda de veículos usados. Aplicamos diferentes algoritmos de regressão, incluindo XGBoost, Random Forest e Regressão Linear, buscando o modelo com melhor performance.

## 📌 Objetivo

Criar um modelo de Machine Learning capaz de prever com precisão o valor de venda de veículos, utilizando um conjunto de dados com variáveis como ano, preço atual, quilometragem, tipo de combustível e transmissão.

## 📁 Fonte dos Dados

Os dados utilizados foram extraídos do Kaggle:  
🔗 [Kaggle - Car Data](https://www.kaggle.com/datasets/athirags/car-data)

## 🧠 Modelos Utilizados

- Regressão Linear
- Random Forest Regressor
- XGBoost Regressor
- Gradient Boosting Regressor

## 🛠️ Tecnologias e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- XGBoost
- Joblib

## 🔍 Etapas do Projeto

1. **Importação dos dados**
2. **Análise exploratória (EDA)**
3. **Pré-processamento**
   - Tratamento de valores nulos
   - Normalização/Padronização
   - Encoding de variáveis categóricas
4. **Divisão entre treino e teste**
5. **Treinamento com múltiplos modelos**
6. **Comparação de performance (MAE, MAPE)**
7. **Salvamento do melhor modelo (joblib)**

## 📊 Métricas Avaliadas

- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)
- Score R² (quando aplicável)

## 💾 Salvando o modelo

O modelo final é salvo usando o pacote `joblib` para ser reutilizado futuramente em APIs ou aplicações web.

## 🙋‍♂️ Autor

Victor Tintel Martins  



