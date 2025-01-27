# 📊 Customer Segmentation Analysis

Welcome to the **Customer Segmentation Analysis** project! This repository showcases a detailed analysis and clustering of customer data, leveraging machine learning techniques to derive meaningful insights. 🚀

---

## 🌟 **Objective**
The goal of this project is to:
- Segment customers into distinct groups using their profile and transactional data.
- Provide actionable insights to enhance marketing strategies and customer engagement.
- Evaluate clustering performance using metrics like Davies-Bouldin Index, Silhouette Score, and Calinski-Harabasz Score.

---

## 📂 **Project Structure**
Here's an overview of the project files and folders:

```
├── data/                  # Input datasets (Customers.csv, Transactions.csv)
├── notebooks/             # Jupyter Notebook for analysis and clustering
├── visuals/               # Visualizations (plots, PCA clusters, etc.)
├── results/               # Output files (clustered data, metrics)
├── README.md              # Project documentation
```

---

## 🛠️ **Tools & Libraries Used**
This project is built using Python and the following libraries:

- **Pandas**: Data manipulation and analysis 🐼
- **NumPy**: Numerical computations 🔢
- **Scikit-learn**: Clustering and evaluation metrics 🤖
- **Matplotlib**: Data visualization 📈
- **Seaborn**: Enhanced plotting 🎨
- **Scipy**: Dendrogram visualization for hierarchical clustering 🧬

---

## 🔍 **Key Steps in Analysis**
1. **Data Preprocessing**:
   - Merging customer profiles and transactional data.
   - Handling missing values and encoding categorical features.
   - Standardizing features for clustering.

2. **Clustering Techniques**:
   - Performed **K-Means Clustering** to group customers.
   - Determined optimal clusters using the **Elbow Method** and **Davies-Bouldin Index**.

3. **Metrics Evaluation**:
   - Calculated clustering quality using:
     - 📉 **Davies-Bouldin Index**
     - 📈 **Silhouette Score**
     - 📊 **Calinski-Harabasz Score**

4. **Visualization**:
   - Elbow plot to determine the optimal cluster count.
   - PCA-reduced scatter plot to visualize clusters.

---

## 📈 **Clustering Results**
- **Optimal Clusters**: 4️⃣
- **Davies-Bouldin Index**: 1.1926 (indicating compact, well-separated clusters)
- **Silhouette Score**: 0.3197
- **Calinski-Harabasz Score**: 68.6363

---

## 📜 **How to Run**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/customer-segmentation-analysis.git
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   - Navigate to the `notebooks/` folder and open the `.ipynb` file.

4. **Explore results**:
   - Check the `results/` folder for cluster labels and metrics.

---

## 🤝 **Contributions**
Contributions are welcome! Feel free to fork this repository, submit issues, or create pull requests. 💡

---

## 📧 **Contact**
For any questions or suggestions, feel free to reach out:
- **Email**: divyannsh.khare.com
- **GitHub**: [Divyansh khare](https://github.com/khare-divyansh)

---

