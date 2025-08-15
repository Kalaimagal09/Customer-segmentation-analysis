# Customer Segmentation using K-Means Clustering 🛍️

This project is an introduction to **unsupervised learning**, focusing on customer segmentation using the **K-Means algorithm**. The goal is to identify distinct groups of customers within the Mall Customer Dataset based on their annual income and spending score, providing actionable insights for marketing strategies.

Unlike previous supervised learning tasks, this project involves finding hidden patterns in unlabeled data.

---

## ## Project Workflow

1.  **Data Preparation**: The dataset was loaded, and key features (`Annual Income`, `Spending Score`) were selected for analysis. **Feature scaling** (`StandardScaler`) was applied to ensure that the clustering algorithm was not biased by the different scales of the features.

2.  **Finding the Optimal K**: The **Elbow Method** was used to determine the ideal number of clusters. By plotting the model's inertia for a range of K values, the optimal K was identified as 5, indicating five distinct customer segments. 

3.  **Model Training & Visualization**: A final K-Means model was trained with **K=5**. The resulting customer segments were visualized on a 2D scatter plot, with each cluster color-coded and its centroid marked.

4.  **Cluster Evaluation**: The quality of the clusters was quantitatively evaluated using the **Silhouette Score**. The score confirmed that the five clusters were well-defined and distinct.

---

## ## Key Concepts Learned

* **Unsupervised Learning**: Hands-on experience with finding hidden structures in unlabeled data.
* **K-Means Clustering**: The core intuition and implementation of the K-Means algorithm.
* **The Elbow Method**: A practical technique for selecting the optimal number of clusters for a given dataset.
* **Silhouette Score**: A metric for evaluating the quality of clusters by measuring their density and separation.
* **Customer Segmentation**: A common and high-impact business application of clustering.

---

## ## Tools Used

* Python
* Scikit-learn
* Pandas
* Matplotlib
