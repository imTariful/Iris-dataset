# Iris-dataset

This project applies unsupervised machine learning techniques to the classic Iris dataset to explore and analyze the performance of different clustering algorithms. We compare K-Means, Agglomerative Clustering, and DBSCAN using the Adjusted Rand Index (ARI) and visualize the cluster formations using PCA.

📌 Project Goals

Perform clustering on the Iris dataset

Visualize high-dimensional data using PCA

Compare clustering results using ARI

Identify which model best matches the ground truth labels

📊 Algorithms Used

K-Means Clustering

Agglomerative (Hierarchical) Clustering

DBSCAN (Density-Based Spatial Clustering)

📈 Evaluation Metric

Adjusted Rand Index (ARI): Measures the similarity between predicted clusters and true labels.

🛠️ Technologies

Python

Scikit-learn

Pandas

Matplotlib

Seaborn

📁 File Structure

IRIS_DATASET.ipynb: Jupyter notebook containing the full code and analysis.

📌 Key Findings

K-Means achieved a high ARI score, closely matching actual labels.

Agglomerative Clustering showed reasonable results with distinguishable clusters.

DBSCAN required tuning but performed well in identifying core samples and noise.

📷 Visualizations

PCA 2D plots for all models

Color-coded cluster comparisons

True label distributions

🚀 How to Run

Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/iris-clustering-analysis.git
cd iris-clustering-analysis
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook IRIS_DATASET.ipynb
📬 Contact

Feel free to connect with me on LinkedIn or raise an issue if you have any questions or suggestions.
