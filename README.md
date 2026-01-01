# Customer Segmentation Project

## Description
This project performs customer segmentation on mall customers using unsupervised machine learning techniques. The analysis focuses on clustering customers based on their annual income and spending score to identify distinct customer groups for targeted marketing strategies.

## Purpose
The main objective is to segment mall customers into meaningful groups based on their purchasing behavior and income levels. This helps in understanding customer patterns, enabling personalized marketing, improving customer satisfaction, and optimizing business strategies.

## Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - pandas: For data manipulation and analysis
  - matplotlib: For data visualization
  - scikit-learn: For machine learning algorithms (KMeans clustering and data preprocessing)
- **Environment**: Jupyter Notebook

## Data Source
The dataset used in this project is sourced from Kaggle: "Mall Customer Segmentation Data". It contains information about mall customers including their age, gender, annual income, and spending score.

**Dataset Details**:
- **File**: Mall_Customers.csv
- **Number of Records**: 200
- **Columns**:
  - CustomerID: Unique identifier for each customer
  - Gender: Customer's gender (Male/Female)
  - Age: Customer's age
  - Annual Income (k$): Annual income in thousands of dollars
  - Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature

## Features Highlights
- **Data Preprocessing**: 
  - Column renaming for better readability
  - Feature selection (Annual Income and Spending Score)
  - Data scaling using StandardScaler for optimal clustering performance
- **Clustering Algorithm**: KMeans clustering with 5 clusters
- **Visualization**: Scatter plots showing customer clusters and cluster centers
- **Evaluation**: Elbow method implementation to determine optimal number of clusters using Within-Cluster Sum of Squares (WCSS)

## Installation
1. Ensure Python 3.x is installed on your system
2. Install required libraries:
   ```
   pip install pandas matplotlib scikit-learn
   ```
3. Download the dataset from Kaggle or use the provided Mall_Customers.csv file

## Usage
1. Open the Jupyter notebook `main.ipynb`
2. Run the cells sequentially to:
   - Load and explore the dataset
   - Preprocess the data
   - Apply KMeans clustering
   - Visualize the results
   - Evaluate the clustering using the Elbow method

## Results
The analysis identifies 5 distinct customer segments:
- Cluster visualization shows clear groupings based on annual income and spending score
- Elbow method plot helps in determining the optimal number of clusters
- Cluster centers provide insights into the characteristics of each segment


