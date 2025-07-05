# AI-ML-TASK-8
# K-Means Clustering on Mall Customers Dataset
This project applies **K-Means Clustering** to perform **unsupervised learning** on the *Mall Customers* dataset, identifying distinct customer segments based on spending behavior and demographics. The goal is to group customers into meaningful clusters to help businesses better understand their target audience.

---

## Dataset

**Mall_Customers.csv**  
The dataset contains 200 entries with the following features:
- `CustomerID`: Unique ID assigned to each customer
- `Gender`: Male or Female
- `Age`: Customer's age
- `Annual Income (k$)`: Annual income in thousands
- `Spending Score (1–100)`: Score assigned based on customer behavior

---

##  Tools & Technologies

- **Language**: Python
- **Libraries**:
  - `pandas` – data handling
  - `matplotlib` & `seaborn` – data visualization
  - `scikit-learn` – machine learning (K-Means, PCA, evaluation)

---

##  Steps Performed

1. **Data Loading & Preprocessing**  
   - Removed `CustomerID` column  
   - Encoded `Gender` (Male → 0, Female → 1)  

2. **Elbow Method**  
   - Calculated WCSS (Within-Cluster Sum of Squares)  
   - Determined the optimal number of clusters (K) visually  

3. **K-Means Clustering**  
   - Fitted the model with optimal `K`  
   - Assigned cluster labels to each customer  

4. **PCA & Visualization**  
   - Reduced features to 2D using PCA  
   - Visualized clusters with color-coded scatter plots  

5. **Model Evaluation**  
   - Evaluated clustering quality using **Silhouette Score**  

---

##  Output Highlights

- **Optimal Clusters (K)**: 5 (based on the Elbow Curve)
- **Silhouette Score**: *~0.45 to 0.55* (depending on the final `K`)
- **Visualized clusters** clearly show distinct customer groupings

---

##  Visuals

> Elbow Curve  
>  Cluster Scatter Plot using PCA  

These plots help determine optimal clusters and visualize the segmentation in a simplified 2D space.

---

##  How to Run (on Google Colab)

1. Upload the `Mall_Customers.csv` file to Colab.
2. Run the notebook step-by-step.
3. Visualizations and clustering results will be displayed inline.

---

##  Outcome

Successfully segmented mall customers into distinct behavioral groups using K-Means clustering. This analysis can support targeted marketing, personalized promotions, and strategic decision-making in retail.

---
