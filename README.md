#Customer Segmentation using KMeans and DBSCAN
This project implements customer segmentation on the Mall Customers dataset using KMeans and DBSCAN clustering algorithms. It includes data cleaning, exploratory analysis, optimal cluster selection, visualization of clusters, and detailed output showing which customers belong to which cluster.

📂 Dataset
The dataset contains customer details like:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

✅ Dataset path: /content/drive/My Drive/ML/project/Mall_Customers.csv

🚀 Features
✅ Clean and preprocess data
✅ Handle inconsistent Gender entries
✅ Elbow Method to determine optimal KMeans clusters
✅ Apply KMeans and DBSCAN clustering
✅ Visualize clusters with matplotlib
✅ Print customers grouped by cluster for both algorithms
✅ Handle outliers and noise in DBSCAN

🖥️ How to Run
Upload the Mall_Customers.csv dataset to your Google Drive

Open the notebook in Google Colab

Mount Google Drive:

drive.mount('/content/drive')
Set file_path in the code to point to your dataset location

Run the notebook cell by cell

📝 Output
The program outputs:

Elbow method plot to select KMeans cluster count

Cluster visualization plots for KMeans and DBSCAN

A detailed printed list of customers in each cluster:


=== Customers in each KMeans Cluster ===
Cluster 1 (Total: 20 customers):
 CustomerID  Gender  Age  Annual Income (k$)  Spending Score (1-100)
       1     Male    19            15                  39
       5   Female    23            16                  81
       ...
Similarly, for DBSCAN, including Noise (-1) cluster.

🏗️ Project Structure

📁 Customer-Segmentation-ML
 ├── Mall_Customers.csv
 ├── customer_segmentation.ipynb
 └── README.md
📊 Algorithms Used
KMeans Clustering

Elbow Method for optimal k

DBSCAN Clustering

Tuned eps and min_samples parameters

Matplotlib/Seaborn for visualization

📚 Requirements
✔ Python 3.x
✔ pandas, matplotlib, seaborn
✔ scikit-learn
✔ Google Colab (optional, or use local Jupyter Notebook)

Install dependencies (if running locally):


pip install pandas matplotlib seaborn scikit-learn

✍️ Author
👤 [Dhanavath Akhil]
🔗 [https://github.com/DhanavathAkhil]
📧 [dhanavathakhil2004@gmail.com]

🎉 License
MIT License – Feel free to use and modify!

⭐ Feel free to star this repo if you find it useful!
