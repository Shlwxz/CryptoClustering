# 💹 Crypto Clustering – Alternate Solution

**Author:** Shahla Shahnawaz  
**Project:** Module 19 – Unsupervised Machine Learning Challenge  
**Notebook:** Crypto_Clustering.ipynb

---

## 🧠 Overview

In this analysis, we use unsupervised learning to explore how cryptocurrencies can be grouped based on their short-term price behavior. Specifically, we apply K-means clustering to assess patterns using both scaled data and data reduced by PCA (Principal Component Analysis).

---

## 📊 Objectives

- Normalize crypto performance metrics using `StandardScaler`
- Identify optimal `k` for clustering using the elbow method
- Apply K-means clustering on both scaled and PCA-transformed datasets
- Visualize crypto groupings based on 24h and 7d percentage changes
- Evaluate the impact of dimensionality reduction via PCA

---

## 🛠️ Key Tools Used

- **Pandas** and **NumPy** for data handling  
- **scikit-learn** for clustering and PCA  
- **hvPlot** for interactive scatter plots and elbow curves  

---

## 🔍 Key Findings

- Elbow plots help identify the optimal number of clusters for both raw and PCA-reduced datasets  
- PCA explained variance shows that 3 components capture most of the structure  
- Clustering results differ slightly between full-dimensional and reduced feature sets  
- Fewer features result in **less granular but clearer clusters**

---

## 📁 File Descriptions

| File                                | Description                                      |
|-------------------------------------|--------------------------------------------------|
| `Crypto_Clustering_ALT_Solution.ipynb` | Main notebook with all steps completed         |
| `README.md`                         | Project summary, goals, methods, and findings   |
| `Resources/crypto_market_data.csv`  | Raw input data (not included in zip)            |

---

## 🧠 Questions Answered

- What is the optimal number of clusters (`k`) for this dataset?  
- Does PCA reduction affect clustering accuracy?  
- Which features drive the strongest grouping signals?

---

## 🗃️ Deliverables Recap

✔️ Scaled DataFrame and PCA DataFrame  
✔️ Elbow curve analysis  
✔️ K-means clustering applied to both data formats  
✔️ Cluster visualizations using `hvPlot`  
✔️ Composite plots comparing PCA and full data clustering  
✔️ Commentary included in markdown cells for interpretation

---

## 🚀 Instructions to Run

1. Install dependencies:
   ```bash
   pip install pandas scikit-learn hvplot
