# customer-segmentation-kmeans
"Customer segmentation using K-Means clustering and Tableau for data visualization."
// Customer Segmentation Using K-Means & Tableau

##  Overview  
Understanding customer behavior is essential for businesses to optimize marketing strategies. This project applies **K-Means clustering** to segment customers based on **Annual Income & Spending Score** and visualizes the insights using **Tableau**.

🔹 **Goal**: Identify customer groups based on their spending habits  
🔹 **Tech Stack**: Python (ML), Tableau (Visualization)  
🔹 **Key Output**: Interactive Tableau Dashboard  

##  Dataset  
The dataset contains 200 mall customers with the following attributes:  
-  **CustomerID** – Unique identifier  
- 🏷**Genre** – Male / Female  
-   **Age** – Customer’s age
-   **Annual Income (k$)** – Yearly income in thousands  
-   **Spending Score (1-100)** – Customer's spending behavior  

 **Business Objective**  
The goal is to **group customers into meaningful segments** based on their spending behavior and income, helping businesses target them effectively.

---

##  **Technologies Used**
🔹 **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
🔹 **Machine Learning**: K-Means Clustering  
🔹 **Data Visualization**: Tableau  

---

##  **Clustering Insights**
K-Means clustering identified **5 unique customer groups**:  
| Cluster | Customer Type | Characteristics |
|---------|-----------------|--------------------------------|
|  Cluster 0 | Luxury Spenders | High Income, High Spending |
|  Cluster 1 | Impulse Buyers | Low Income, High Spending |
|  Cluster 2 | Careful Shoppers | High Income, Low Spending |
|  Cluster 3 | Budget Customers | Low Income, Low Spending |
|  Cluster 4 | Balanced Customers | Medium Income, Balanced Spending |

** Business Application:** Helps businesses create **personalized marketing strategies** for each segment.

---

##  **Tableau Dashboard**
 View the Interactive Dashboard:  
🔗 [Click Here] (https://public.tableau.com/views/customer_segmentation_17424117395940/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))**

This dashboard allows users to:  
✔ Filter customers by Age, Gender, and Cluster 
✔ Visualize spending trends across income levels  
✔ Identify high-value customer segments 

---

#  **How to Run This Project Locally**

1. **Clone the Repository**
```sh
git clone https://github.com/yourusername/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans

2. **Install Dependencies**
pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook
jupyter notebook

Open customer_segmentation.ipynb and run all cells to see the clustering results.

Future Improvements
🔹 Add Age-Based Clustering to refine segmentation
🔹 Experiment with Hierarchical & DBSCAN Clustering
🔹 Integrate Streamlit for a web-based ML dashboard

