# 🛒 Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior. Customer segmentation helps businesses understand their customers better, enabling targeted marketing strategies and personalized services.

## 🎯 Objectives

* Preprocess customer transaction data.
* Apply **K-Means Clustering** to group customers.
* Visualize clusters to interpret customer segments.
* Explore real-world business use cases of clustering.

## 📂 Dataset

This project uses the **Online Retail II** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail+ii).

➡️ Download the dataset from the link above and place the Excel file inside a folder named `data/` at the root of the repository.

Expected path:

```bash
./data/online_retail_II.xlsx
```

⚠️ Note: The dataset is too large to be stored directly in this repository. Please download it manually.

## ⚙️ Steps Involved

1. **Data Cleaning & Preprocessing**

   * Handling missing values.
   * Scaling numerical features to ensure fair distance calculation.

2. **Exploratory Data Analysis (EDA)**

   * Distribution plots, feature correlations.
   * Understanding customer behavior patterns.

3. **K-Means Clustering**

   * Intuition: assign → update → repeat until convergence.
   * Determining optimal clusters using the **Elbow Method** and validating with the **Silhouette Score** (measures cluster separation and cohesion).
   * Fitting K-Means and generating customer clusters.

4. **Visualization**

   * Scatter plots of clusters.
   * Interpretation of different customer groups (e.g., frequent buyers, budget shoppers, high-value customers).

## 📊 Results & Insights

* Identified distinct customer groups with unique purchasing patterns.
* Example segments:

  * **Cluster 1**: High-spending, frequent customers.
  * **Cluster 2**: Occasional, budget-conscious buyers.
  * **Cluster 3**: Medium-value, loyal customers.

*(Exact cluster interpretation depends on dataset used)*

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Visualization
* **Scikit-learn** – K-Means implementation

## 📈 Key Learnings

* Importance of **feature scaling** in distance-based algorithms.
* How to select the optimal number of clusters (Elbow Method & Silhouette Score).
* Strengths and limitations of K-Means (efficient but sensitive to outliers).
* Real-world application of clustering in **customer analytics**.

## 🚀 How to Run

1. Clone the repo

   ```bash
   git clone https://github.com/Ayush-sinha44/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset (see Dataset section above) and place it in the `data/` folder.
4. Run the notebook/script to reproduce results.

## 📌 References

* https://youtu.be/afPJeQuVeuY?si=Syb1sbUPZCP0xxnB
* Scikit-learn Documentation: [https://scikit-learn.org/stable/modules/clustering.html#k-means](https://scikit-learn.org/stable/modules/clustering.html#k-means)

