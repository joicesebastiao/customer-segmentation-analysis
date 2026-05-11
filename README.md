# Mall Customer Segmentation Analysis - Unsupervised Machine Learning Project

This project applies *unsupervised machine learning techniques* to target clients of a specific mall. The main goal is to identify behavioral patterns, consumer profiles and business oportunities.
This analysis combines EDA, clustering, modelling validation and interpretability of clusters to generate insights. 

-------------------------------------------------------------------------------------------------------------------------------------

### 🎯 Objectives of the project

Group clients based on:
- Age
- Annual Income
- Spending Score

In order to:
- Identify groups with similar behaviors
- Support marketing decisions
- Find growth opportunities 
- Deliver personalized campaigns and experiences

### 📊 Dataset and EDA insights

- Mall_Customers dataset from Kaggle.
- The dataset contains 200 clients, between the ages of 18 and 70, with annual incomes varying between 15k and 137k.
- 56% are females, and this proportion is the same in almost all clusters. 
- There's one paradox:
    - High income does not imply high spending scores, especially in older clients and males.
- Gender distribution is not a strong differenciated factor.

### 🤖 Modelling and Validation

Three algorithms were tested:
- K-Means
- Hierarchical Clustering
- Gaussian Mixture Models

The comparison was made using:
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Score

### 🧩 Results

**Client profile:**

🔴 *Cluster 0 — Young & Impulsive*
- Age: 18–25
- Income: low
- Spending Score: high

**Insight:** high spending despite low income.

🔵 *Cluster 1 — Premium Customers*
- Age: 26–35
- Income: high
- Spending Score: very high

**Insight:** the most valuable segment.

🟢 *Cluster 2 — Budget Conscious*
- Age: 46–55
- Income: low
- Spending Score: low

**Insight:** financially limited.

🟠 *Cluster 3 — Untapped Potential*
- Age: 36–45
- Income: high
- Spending Score: low

**Insight:** mall's biggest oportunity.

🟣 *Cluster 4 — Mature & Balanced*
- Age: 46–70
- Income: moderate
- Spending Score: moderate

**Insight:** stable and predictable.

-------------------------------------------------------------------------------------------------------------------------------------

### 💡 Business Recomendation
*Cluster Untapped Potential* is the most strategic: 
- Annual Income similar to Premium
- but Spending Scores similiar to Budget Conscious
 
Invest in premium experiences, personalized campaigns and fidelity incentives to increase the Spending Scores of this group.
