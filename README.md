# SC_ML_2
# Customer Segmentation using K-Means Clustering

This project was completed as part of my **Machine Learning Internship at SkillCraft Technology**.

## Task Objective

Create a K-Means clustering model to group retail-store customers based on their purchasing behaviour.

The goal is to identify customer segments using:

- Annual Income
- Spending Score

## Dataset

This project uses the **Mall Customer Segmentation Dataset**.

Key columns used:

| Column | Description |
|---|---|
| `CustomerID` | Unique ID for each customer |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Annual Income (k$)` | Customer's annual income in thousands of dollars |
| `Spending Score (1-100)` | Score assigned based on spending behaviour |

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. Upload and extract the Mall Customer dataset.
2. Load the dataset using Pandas.
3. Explore the dataset and check for missing values.
4. Select `Annual Income (k$)` and `Spending Score (1-100)` for clustering.
5. Standardize the selected features.
6. Use the Elbow Method to find the appropriate number of clusters.
7. Apply the K-Means clustering algorithm.
8. Visualize customer groups and cluster centroids.
9. Analyze the average income and spending score for each cluster.

## Elbow Method

The Elbow Method was used to identify the suitable number of clusters. Based on the plot, the dataset was segmented into **5 customer clusters**.

## Customer Segments

The model groups customers into different categories, such as:

- High income and high spending customers
- High income and low spending customers
- Low income and high spending customers
- Low income and low spending customers
- Average income and average spending customers

These segments can help businesses create better marketing campaigns and personalized offers.

## How to Run

1. Download or clone this repository.
2. Open the notebook file in Google Colab or Jupyter Notebook.
3. Upload the `archive.zip` dataset when prompted.
4. Run all cells in order.

## Result

The K-Means model successfully segments customers based on their annual income and spending score. The visualizations make it easier to understand customer purchasing patterns and identify valuable customer groups.

 
SkillCraft Technology
