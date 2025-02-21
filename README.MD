# Prevendo Riscos em Empresas com CatBoost

## Sobre o Projeto

Este projeto tem como objetivo desenvolver um modelo de Machine Learning para prever a probabilidade de três tipos de riscos para empresas: crédito, compliance e mercado. Utilizamos o algoritmo CatBoost para lidar eficientemente com a grande quantidade de variáveis categóricas presentes nos dados. Além disso, exploramos a interpretabilidade do modelo para identificar os principais fatores que influenciam cada risco.

## Contexto do Problema

Uma empresa do setor financeiro deseja aprimorar seu modelo de avaliação de risco para clientes pessoa jurídica. O objetivo é conceder crédito com mais segurança e reduzir a exposição a riscos.

Os desafios incluem:

- Prever três tipos de risco (crédito, compliance e mercado).
- Classificar de forma binária se cada risco é presente ou ausente.
- Analisar quais variáveis impactam mais cada risco, de forma global e individual.

## Tecnologias Utilizadas

- Python
- Pandas, NumPy, SciPy (para manipulação e análise estatística dos dados)
- Matplotlib, Plotly (para visualização dos dados)
- Scikit-Learn (para avaliação do modelo)
- CatBoost (modelo de Machine Learning utilizado)
- SHAP (para interpretabilidade dos modelos)

## Etapas do Projeto

### Exploração e Tratamento de Dados

- Análise exploratória dos dados (EDA)
- Tratamento de valores ausentes e transformação de variáveis categóricas
- Testes estatísticos para verificar relações entre features e os riscos

### Modelagem com CatBoost

- OneVsRestClassifier para treinar um modelo independente para cada risco
- Ajuste de hiperparâmetros utilizando GridSearchCV
- Predição das probabilidades de risco para cada empresa

### Avaliação do Modelo

- Matriz de confusão para cada risco
- Métricas de desempenho: Log Loss, F1-Score, Precisão e Recall

### Interpretabilidade do Modelo

- Importância das Features para entender quais variáveis impactam cada risco

## Principais Resultados

- Identificamos as variáveis mais influentes para cada risco, auxiliando na tomada de decisão.
- O modelo apresentou boas métricas de desempenho, com alta capacidade preditiva.
- A interpretabilidade mostrou que fatores como endividamento e rating de crédito são determinantes para a classificação de risco.

## Contato

Caso tenha dúvidas ou sugestões, entre em contato comigo via LinkedIn ou pelo meu GitHub.

Matheus Pedra[https://www.linkedin.com/in/matheus-gustavo11/]
