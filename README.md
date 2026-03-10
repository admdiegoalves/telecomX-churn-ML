# 📊 Previsão de Evasão de Clientes (Churn) com Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-red)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 📌 Sobre o Projeto

Este projeto tem como objetivo **identificar os fatores que mais influenciam a evasão de clientes (Churn)** em uma empresa de telecomunicações e desenvolver modelos de **Machine Learning capazes de prever quais clientes possuem maior probabilidade de cancelamento**.

A evasão de clientes representa um dos principais desafios para empresas baseadas em assinatura. Identificar clientes com risco de churn permite que a empresa **implemente ações preventivas de retenção**, reduzindo perdas de receita.

Este projeto demonstra como **análise de dados e Machine Learning podem apoiar decisões estratégicas de negócio**.

---

# 🧠 Storytelling do Projeto

Imagine uma empresa de telecomunicações com milhões de clientes.

Todos os meses, parte desses clientes cancela seus serviços. Cada cancelamento representa:

- perda de receita recorrente
- aumento no custo de aquisição de novos clientes
- redução do valor de vida do cliente (Customer Lifetime Value)

A pergunta principal é:

> **Quais clientes têm maior probabilidade de cancelar seus serviços?**

E mais importante:

> **Quais fatores estão por trás dessa decisão?**

Para responder essas perguntas, foi desenvolvido um pipeline completo de Data Science:

1️⃣ Exploração e entendimento dos dados  
2️⃣ Identificação de padrões de evasão  
3️⃣ Construção de modelos preditivos  
4️⃣ Extração de insights estratégicos  

---

# 🎯 Objetivos do Projeto

- Identificar **variáveis que influenciam a evasão de clientes**
- Construir modelos de **Machine Learning para prever churn**
- Comparar desempenho entre algoritmos
- Gerar **insights acionáveis para retenção de clientes**

---

# 🛠️ Tecnologias Utilizadas

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE)**

Ferramentas utilizadas:

- **Google Colab Notebook**
- **GitHub**

---

# 📂 Estrutura do Projeto

```
telecom-churn-ml/
│
├── data/
│ └── dados_tratados.csv
│
├── notebook/
│ └── telecomX_parte2.ipynb
│
├── images/
│ ├── correlacao.png
│ ├── churn_distribution.png
│ └── comparação modelos.png
│
└── README.md
```
---

# 🔎 Etapas da Análise

## 1️⃣ Entendimento e Preparação dos Dados

Nesta etapa foram realizadas:

- limpeza dos dados
- remoção de variáveis irrelevantes
- transformação de variáveis categóricas
- normalização de variáveis numéricas

Também foi aplicado **SMOTE (Synthetic Minority Oversampling Technique)** para balancear o dataset, já que problemas de churn geralmente apresentam **desbalanceamento entre as classes**.

---

## 2️⃣ Análise Exploratória dos Dados (EDA)

A análise exploratória permitiu identificar padrões relevantes relacionados à evasão.

Principais observações:

- Clientes com **menos tempo de contrato apresentam maior probabilidade de churn**
- Contratos **mensais possuem maior taxa de cancelamento**
- Planos com **valor mensal mais alto apresentam maior risco de evasão**
- Clientes com **baixo valor total acumulado apresentam menor fidelização**

Esses padrões indicam que o churn está fortemente relacionado ao **tempo de relacionamento com a empresa e à percepção de custo do serviço**.

---

# 🤖 Modelagem Preditiva

Foram utilizados dois algoritmos de Machine Learning para prever churn.

## 📉 Regressão Logística

Modelo amplamente utilizado para problemas de classificação binária.

Vantagens:

- Alta interpretabilidade
- Permite entender o impacto de cada variável no churn

---

## 🌲 Random Forest

Modelo baseado em múltiplas árvores de decisão.

Vantagens:

- Captura relações não lineares
- Alta robustez
- Melhor desempenho preditivo em muitos cenários

---

# 📊 Avaliação dos Modelos

Os modelos foram avaliados utilizando:

- Accuracy
- Precision
- Recall
- F1-score
- AUC-ROC

Essas métricas permitem avaliar a capacidade do modelo de identificar clientes com risco de evasão.

---

# 🔑 Principais Fatores que Influenciam o Churn

A análise dos modelos revelou que os fatores mais relevantes para churn são:

- **Tempo de contrato (tenure)**
- **Valor mensal do plano**
- **Valor total gasto**
- **Tipo de contrato**
- **Forma de pagamento**

Clientes **com menor tempo de relacionamento e contratos mensais apresentam maior probabilidade de cancelamento**.

---

# 💼 Business Impact

A aplicação de modelos preditivos de churn permite que empresas adotem uma abordagem **proativa na retenção de clientes**.

Com base nos resultados deste projeto, algumas ações estratégicas podem ser implementadas:

### 🎯 Programa de retenção para novos clientes

Os primeiros meses apresentam maior risco de churn.

Possíveis ações:

- onboarding estruturado
- acompanhamento nos primeiros 90 dias
- benefícios iniciais

---

### 🎯 Incentivo a contratos de longo prazo

Clientes com contratos longos apresentam menor evasão.

Estratégias:

- descontos em planos anuais
- benefícios de fidelidade
- upgrades de serviço

---

### 🎯 Identificação de clientes com risco de churn

O modelo pode ser integrado a sistemas da empresa para:

- identificar clientes com **alta probabilidade de cancelamento**
- priorizar ações de retenção
- oferecer **ofertas personalizadas**

---

# 🚀 Próximos Passos

Possíveis melhorias para evolução do projeto:

- Testar modelos mais avançados (XGBoost, LightGBM)
- Otimização de hiperparâmetros
- Deploy do modelo via API
- Criação de dashboard de churn
- Integração com sistemas de CRM

---

# 👨‍💻 Autor

**Diego Alves**

Data Scientist com foco em:

- Machine Learning
- Análise de Dados
- Estratégia de Negócios orientada por dados

🔗 [LinkedIn](https://www.linkedin.com/in/admdiegoalves/)
🔗 [Email](admdiegoalves@gmail.com)

---

# 📌 Conclusão

Este projeto demonstra como **Data Science pode gerar valor estratégico para empresas** ao transformar dados em insights acionáveis.

A identificação antecipada de clientes com risco de churn permite que organizações implementem **estratégias de retenção mais eficientes**, reduzindo perdas de receita e aumentando o valor de vida do cliente.

---
