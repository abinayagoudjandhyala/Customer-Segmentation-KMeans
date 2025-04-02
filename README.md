# Customer Segmentation using K-Means Clustering

## Overview
This project demonstrates customer segmentation using the K-Means clustering algorithm. The analysis identifies customer groups based on spending behavior and annual income, enabling targeted marketing strategies.

## Dataset
The dataset used is sourced from [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) with the following features:
- CustomerID: Unique ID for each customer
- Gender: Gender of the customer
- Age: Age of the customer
- Annual Income (k$): Annual income in thousand dollars
- Spending Score (1-100): Customer spending behavior score

## Project Structure
- **Data Collection and Analysis**: Load and inspect the dataset
- **Choosing Features**: Select features for clustering
- **Optimal Cluster Calculation**: Use the Elbow Method
- **Model Training**: Apply K-Means
- **Visualization**: Visualize customer segments

## Prerequisites
Ensure you have the following libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Run
1. Clone the repository
```bash
git clone https://github.com/abinayagoudjandhyala/Customer-Segmentation-KMeans
cd CustomerSegmentation
```
2. Run the notebook
```bash
jupyter notebook CustomerSegmentation.ipynb
```

## Results
- Optimal number of clusters determined using the Elbow Method.
- Visualized customer segments using 2D plots.

## Conclusion
This project effectively segments customers using K-Means, enabling targeted marketing strategies.
