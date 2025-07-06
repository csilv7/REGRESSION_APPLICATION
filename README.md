# 📊 Projeto de Comparação de Modelos de Regressão com Multicolinearidade

## 🎯 Objetivo
Avaliar o desempenho de diferentes técnicas de regressão aplicadas a um conjunto de dados que apresenta **multicolinearidade**, com o intuito de identificar o modelo que melhor se ajusta aos dados.

## 🧩 Etapas do Projeto

### 1. Exploração Inicial dos Dados
- Análise descritiva
- Identificação de multicolinearidade (ex: matriz de correlação, VIF)

### 2. Modelos a Serem Aplicados
- **Regressão Linear Múltipla**
  - Antes do tratamento da multicolinearidade
  - Após o tratamento (ex: remoção de variáveis, PCA)
- **Regressão Ridge**
- **Regressão Lasso**

### 3. Estratégia de Validação
- Divisão dos dados em **conjunto de treino e teste**
- Aplicação de **validação cruzada** (ex: K-Fold)

### 4. Avaliação de Desempenho
- Métricas de erro:
  - MAPE (Mean Absolute Percentage Error)
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
- Critérios de informação:
  - AIC (Akaike Information Criterion)
  - BIC (Bayesian Information Criterion)

## 🧠 Ferramentas e Tecnologias Sugeridas
- Linguagem: Python (bibliotecas como `scikit-learn`, `statsmodels`, `pandas`, `numpy`)
- Visualização: `matplotlib`, `seaborn`

## 📌 Resultados Esperados
- Comparativo entre os modelos com base nas métricas e critérios
- Discussão sobre o impacto da multicolinearidade
- Recomendação do modelo mais adequado para os dados analisados
