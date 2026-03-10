# Telecom X Churn Prediction

## Sobre o projeto

Este projeto tem como objetivo analisar e prever a evasão de clientes (churn) na empresa fictícia Telecom X utilizando técnicas de análise de dados e machine learning. A evasão de clientes é um problema relevante para empresas de telecomunicações, pois impacta diretamente a receita e a retenção de clientes.

Através da análise dos dados e da construção de modelos preditivos, busca-se identificar os fatores mais associados ao cancelamento dos serviços e apoiar estratégias de retenção.

## Objetivos

- Analisar os dados de clientes da Telecom X.
- Identificar fatores relacionados à evasão de clientes.
- Construir modelos de machine learning para prever churn.
- Avaliar o desempenho dos modelos utilizando métricas de classificação.

## Etapas do projeto

1. Preparação e limpeza dos dados.
2. Análise exploratória dos dados.
3. Transformação de variáveis categóricas em numéricas.
4. Divisão do conjunto de dados em treino e teste.
5. Treinamento de modelos de machine learning.
6. Avaliação do desempenho dos modelos.

## Modelos utilizados

### Regressão Logística
Modelo de classificação binária utilizado para prever a probabilidade de evasão de clientes. Foi aplicada normalização dos dados, pois o algoritmo é sensível à escala das variáveis.

### Random Forest
Algoritmo baseado em árvores de decisão que combina várias árvores para melhorar a capacidade de previsão e reduzir o risco de overfitting. Esse modelo não requer normalização dos dados.

## Métricas de avaliação

Os modelos foram avaliados utilizando as seguintes métricas:

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

## Principais fatores relacionados ao churn

A análise indicou que algumas variáveis possuem maior influência na evasão de clientes, entre elas:

- tempo de contrato (tenure)
- valor mensal do serviço
- valor total gasto
- tipo de contrato
- método de pagamento

## Estrutura do projeto
telecom-x-churn-2/
│
├── data/
│ └── telecom_churn_tratado.csv
│
├── notebook/
│
└── README.md


## Conclusão

Os modelos desenvolvidos permitiram identificar padrões associados à evasão de clientes. Esses resultados podem auxiliar a empresa na identificação de clientes com maior risco de cancelamento e no desenvolvimento de estratégias de retenção mais eficazes.

## 👩‍💻 Sobre Mim

Sou profissional de tecnologia com atuação em **Product Owner e Análise de Dados**, focada em transformar dados em decisões estratégicas.

Este projeto representa minha evolução prática em análise de dados, conectando:

- pensamento analítico  
- visão de produto  
- interpretação de métricas de negócio  

🔗 **GitHub:** https://github.com/Sabrinawsf  
🔗 **LinkedIn:** *https://www.linkedin.com/in/sabrinasfonseca/*

---

⭐ Feedbacks e conexões são sempre bem-vindos!
