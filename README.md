# Mall Customer Segmentation Analysis - Unsupervised Machine Learning Project

Este projeto aplica técnicas de *unsupervised machine learning* para segmentar clientes de um centro comercial, com o objetivo de identificar padrões de comportamento, perfis de consumo e oportunidades de negócio.

A análise combina EDA, clustering, validação de modelos e interpretacção de segementos para gerar insights.

-------------------------------------------------------------------------------------------------------------------------------------

### 🎯 Objectivos do Projeto

Segmentar clientes com base em:
- Idade
- Rendimento Anual
- Score de Gastos

De forma a:
- Identificar grupos com comportamentos semelhantes
- Apoiar decisões de marketing
- Descobrir oportunidades de crescimento
- Personalizar campanhas e experiências

### 📊 Dataset e insights da EDA

- Mall_customers dataset extraído do Kaggle.
- O dataset contem 200 clientes, entre os 18 e 70 anos, com rendimentos entre 15k e 137k.
- 56% são mulheres, e esta proporção mantém se em quase todos os clusters.
- Existe um paradoxo:
    - Rendimento elevado não implica gastos elevados, especialmente em clientes mais velhos e homens.
- A distribuição de género não é um fator diferenciador forte.

### 🤖 Modelo e Validação

Foram testados três algoritmos:
- K-Means
- Hierarchical Clustering
- Gaussian Mixture Models

A comparação foi feita com:
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Score

### 🧩 Results

Perfis dos Segmentos:

🔴 Cluster 0 — Young & Impulsive
- Idade: 18–25
- Rendimento: baixo
- Spending Score: alto
Insight: gastam muito apesar de terem pouco rendimento.

🔵 Cluster 1 — Premium Customers
Idade: 26–35
Rendimento: alto
Spending Score: muito alto
Insight: o segmento mais valioso.

🟢 Cluster 2 — Budget Conscious
Idade: 46–55
Rendimento: baixo
Spending Score: baixo
Insight: limitados financeiramente.

🟠 Cluster 3 — Untapped Potential
Idade: 36–45
Rendimento: alto
Spending Score: baixo
Insight: a maior oportunidade do shopping.

🟣 Cluster 4 — Mature & Balanced
Idade: 46–70
Rendimento: médio
Spending Score: moderado
Insight: estáveis e previsíveis.

-------------------------------------------------------------------------------------------------------------------------------------

### 💡 Recomendação de Negócio
O segmento Untapped Potential é o mais estratégico:
- têm rendimento comparável aos Premium
- mas gastam como Budget Conscious
- estão completamente subaproveitados
 
Investir em experiências premium, campanhas personalizadas e incentivos de fidelização para aumentar o Spending Score deste grupo — impacto direto na receita do shopping.

