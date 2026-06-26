# FMCG Retail Sales & Consumer Behavior Analysis

## Project Objective
This project analyzes retail supermarket transaction data to uncover purchasing patterns, optimize supply chain timing, and segment customers. The analysis specifically focuses on the **Health & Beauty** category to mirror FMCG industry dynamics, providing actionable insights for merchandising and customer retention.

## Technology Stack
* **Python** (Data Wrangling & Logic)
* **Pandas / NumPy** (Data Manipulation)
* **Seaborn / Matplotlib** (Data Visualization)
* **Scikit-Learn (K-Means)** (Unsupervised Machine Learning)

## Key Business Insights

### 1. Supply Chain Optimization (The "When")
* **Insight:** Health & Beauty sales experience a massive volume spike on **Saturdays at 1:00 PM** ($2,087 in a single hour).
* **Action:** High-velocity FMCG items (toothpaste, mouthwash, soaps) must be fully restocked and front-faced by Saturday morning to prevent stockouts during the weekend rush.

### 2. Loyalty vs. Geographic Anomalies (The "Where")
* **Insight:** Overall, Loyalty Members drive 71% more revenue in Health & Beauty. However, in the Giza branch, *non-members* actually have a higher Average Order Value ($327 vs $314 for members).
* **Action:** Launch a targeted loyalty-acquisition campaign specifically at the Giza location to convert high-basket casual shoppers into recurring members.

### 3. Predictive Customer Segmentation (The "Who")
Using an Unsupervised **K-Means Clustering** algorithm based on Total Spend and Satisfaction Ratings, the customer base was segmented into three distinct personas. 
* **The "Premium Cart Loaders" (High Risk):** This cohort spends the most per trip (Avg: $697) but reports mediocre satisfaction (6.5/10) compared to lower-spending cohorts (8.6/10). 
* **Action:** Introduce bulk-buy SKUs or premium member checkout lanes to improve the retail experience and prevent churn among the most valuable buyers.

## 📈 Visualizations
*(Note: Upload your heatmap.png and clusters.png to GitHub, then link them here!)*
