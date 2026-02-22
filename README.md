
📊 Telecom X – Previsão de Evasão de Clientes (Churn)
📌 Sobre o Projeto

Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever a evasão de clientes (churn) na Telecom X.

A proposta é identificar clientes com maior probabilidade de cancelar seus serviços, permitindo que a empresa atue de forma preventiva com estratégias de retenção.

🎯 Objetivo

Antecipar o cancelamento de clientes utilizando técnicas de análise de dados e modelos de classificação.

🧠 Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

⚙️ Etapas do Projeto
1️⃣ Importação e Limpeza de Dados

Remoção de colunas irrelevantes

Tratamento de valores ausentes

Conversão de tipos de dados

2️⃣ Pré-processamento

Encoding de variáveis categóricas (One-Hot Encoding)

Normalização com StandardScaler

3️⃣ Seleção de Variáveis

Análise de correlação

Avaliação de importância das variáveis

4️⃣ Modelagem

Modelos aplicados:

Regressão Logística (baseline)

Random Forest (melhor desempenho)

5️⃣ Avaliação

Métricas utilizadas:

Accuracy

Precision

Recall (métrica prioritária)

F1-score

ROC-AUC

📊 Principais Insights

Clientes com maior risco de churn apresentam:

Contrato mensal

Baixo tempo de permanência

Alta mensalidade

Internet fibra óptica

Pagamento via cheque eletrônico

Ausência de serviços adicionais

🚀 Recomendações Estratégicas

Incentivar contratos anuais

Criar programas de fidelização nos primeiros meses

Oferecer pacotes com serviços adicionais

Implementar monitoramento de clientes de alto risco

📈 Resultado

O modelo Random Forest apresentou melhor desempenho geral, especialmente na identificação de clientes com maior probabilidade de evasão, permitindo ações estratégicas de retenção.

📂 Estrutura do Projeto
📁 telecom-churn
│
├── data/
├── notebooks/
├── models/
├── README.md
└── requirements.txt
👩🏽‍💻 Autora

Priscila Souza
Projeto desenvolvido para estudo e aplicação prática de Machine Learning em problemas de negócio.
