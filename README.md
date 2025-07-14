# Wholesale Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment wholesale customers based on their annual spending across six product categories. It includes **data preprocessing**, **elbow method for optimal clusters**, **PCA for visualization**, and **silhouette score evaluation** to ensure meaningful, high-quality clusters.

---

## 📁 Dataset

- **Source:** Wholesale customers dataset (UCI Machine Learning Repository or similar)
- **Features:**
  - `Fresh`, `Milk`, `Grocery`, `Frozen`, `Detergents_Paper`, `Delicassen`
- **Goal:** Group customers with similar spending behavior.

---

## 🧪 Techniques Used

- **Unsupervised Learning:** K-Means Clustering
- **Dimensionality Reduction:** Principal Component Analysis (PCA)
- **Evaluation Metric:** Silhouette Score
- **Visualization:** 
  - Cluster plots
  - Pair plots
  - Spending pattern bar charts

---

## 🔧 Steps Performed

1. **Data Preprocessing**
   - Standardized features using `StandardScaler`.

2. **Optimal K Selection**
   - Elbow Method (Within-cluster SSE plot)
   - Silhouette Score analysis

3. **K-Means Clustering**
   - Applied KMeans with optimal cluster number
   - Assigned labels to customers

4. **PCA**
   - Reduced dimensions to 2D for cluster visualization

5. **Visualization**
   - Average Spending per Product Category by Cluster
     <img width="814" height="411" alt="Screenshot 2025-07-14 at 4 07 45 pm" src="https://github.com/user-attachments/assets/37d6feed-5200-4a41-aaaf-26167da113d7" />

   - Customer Segments Visualization (PCA)
     <img width="615" height="445" alt="Screenshot 2025-07-14 at 4 05 19 pm" src="https://github.com/user-attachments/assets/1943d874-1f39-4e31-9522-c9219fc9599e" />

   - Pairplot of Features by Cluster
     
     <img width="557" height="517" alt="Screenshot 2025-07-14 at 4 06 52 pm" src="https://github.com/user-attachments/assets/abc359d6-6f84-4ef6-827a-762563032134" />


---

## 📊 Results

- Identified distinct clusters of customer types:
  - **High Spenders**: Likely wholesale buyers
  - **Low-to-Average Spenders**: Possibly retail or seasonal buyers
- Clear separation of customer behaviors using PCA and scaled bar plots
- Clusters validated using **Silhouette Score**

---

## 📌 Conclusion

In this project, we successfully implemented K-Means Clustering to segment wholesale customers based on their annual spending behavior. Each cluster revealed unique spending patterns — helping understand different buyer personas.

✅ This project demonstrates how unsupervised learning can be used in business to:

- Identify customer segments
- Personalize marketing strategies
- Improve operational planning

---

## 🚀 Future Work

- Try different clustering algorithms: **DBSCAN**, **Hierarchical Clustering**
- Build a **Streamlit app** to make it interactive for business users
- Apply this approach to **retail**, **banking**, or **telecom** datasets

---

## 🏷️ Tags

`Python` `Clustering` `KMeans` `PCA` `Customer Segmentation`  
`Machine Learning` `Unsupervised Learning` `Silhouette Score` `Data Science`

---

## 📌 Author

**Insha Shaikh**  
Final-Year BSc IT | Aspiring Data Scientist  
[GitHub](https://github.com/shaikh-insha) • [LinkedIn](https://linkedin.com/in/shaikh-insha)

---
