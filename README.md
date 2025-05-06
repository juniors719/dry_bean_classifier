# 🫘 Dry Bean Classification with Machine Learning

Este repositório contém a análise e construção de modelos de Machine Learning para classificação de sementes de feijão seco (Dry Beans), utilizando um conjunto de dados com 13.611 amostras de 7 tipos diferentes de feijões.

## 📁 Dataset

- **Nome:** Dry Bean Dataset
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/dry+bean+dataset)
- **Número de amostras:** 13.611
- **Número de atributos:** 16 características extraídas de imagens (área, perímetro, formato, etc) + 1 coluna de classe (tipo de feijão)
- **Classes:** Seker, Barbunya, Bombay, Cali, Dermosan, Horoz e Sira

## 🧪 Objetivo

Desenvolver e avaliar diferentes modelos de classificação para identificar corretamente o tipo de feijão com base em suas características físicas e geométricas.

## 📌 Etapas do Projeto

- ✅ Importação e exploração dos dados (EDA)
- ✅ Pré-processamento e preparação dos dados
- ✅ Validação cruzada com k-Fold (k=5)
- ✅ Testes com e sem escalonamento (StandardScaler)
- ✅ Treinamento de 3 algoritmos diferentes:
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Support Vector Machine (SVM)
- ✅ Otimização de hiperparâmetros com `GridSearchCV`
- ✅ Avaliação com múltiplas métricas:
  - Acurácia
  - Precisão
  - Recall
  - F1-Score
- ✅ Comparação dos resultados por tabelas e gráficos

## 📊 Resultados

Os modelos foram avaliados com e sem o uso de escalonamento de características. Os resultados são apresentados em forma de tabela comparativa e gráfico de barras, destacando os algoritmos com melhor desempenho.
