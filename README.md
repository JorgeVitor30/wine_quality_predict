# Predição da Qualidade do Vinho

Este simples projeto tem como objetivo demonstrar o uso de diferentes modelos de machine learning do Scikit-Learn para prever a qualidade de vinho com base em diversas características. Foram utilizados os seguintes modelos:

- Naive Bayes
- Árvore de Decisão
- Random Forest
- K-Nearest Neighbors (KNN)
- Regressão Logística

## Descrição do Projeto

O script fornecido neste repositório realiza o treinamento e teste dos modelos mencionados acima para prever a qualidade do vinho com base em um conjunto de dados de qualidade de vinho vermelho. O desempenho de cada modelo é avaliado utilizando métricas de acurácia.

## Conjunto de Dados

O conjunto de dados utilizado é o conjunto de qualidade de vinho vermelho disponível publicamente, que contém diversas características físico-químicas de vinhos.

## Métricas de Avaliação

As métricas de avaliação utilizadas para cada modelo incluem:

- Acurácia (Accuracy)
- Precisão (Precision)
- Revocação (Recall)
- F1-Score

## Resultados

Aqui está o ranking dos modelos em ordem crescente de acurácia:

1. Random Forest
2. Regressão Logística 
3. Árvore de Decisão
5. KNN 
6. Naive Bayes

### Acurácia dos Modelos

- Naive Bayes: [54.06 %]
- Árvore de Decisão: [60.31 %]
- Random Forest: [72.19 %]
- KNN: [60.63 %]
- Regressão Logística: [63.13 %]

## Conclusão

Com base nos resultados obtidos ao avaliar os diferentes modelos de machine learning para prever a qualidade do vinho, podemos destacar algumas observações:
- O modelo Random Forest apresentou a maior acurácia de 72.19 %, indicando uma melhor capacidade de generalização para prever a qualidade do vinho com base nas características fornecidas.
- A Regressão Logística também obteve uma boa acurácia de 63.13 %, demonstrando uma capacidade significativa de aprendizado e predição.
- Os modelos Naive Bayes, Árvore de Decisão e KNN obtiveram acurácias relativamente inferiores.
