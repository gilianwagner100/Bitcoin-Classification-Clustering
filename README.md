# Bitcoin Classification & Clustering

## Overview
In our Master's degree "Business Analytics" at Nova School of Business and Economics, we worked on a project which focused on analyzing Bitcoin transactions, performing Feature Engineering, Classification and Clustering. For this, the programming languages Python and PySpark were used.

Initially, we conducted a thorough analysis of these transactions before we created additional features such as *Number of Total Transactions*, *Average Number of Unique Partners per Day* or *Transaction Variability*. After that, we categorized the transactions based on their nature, such as mining, gambling, and exchanges, employing a **Support Vector Machines (SVM)** as well as **Random Forest model**.

After classification, we removed the label column and proceeded to cluster the dataset to group transactions without prior knowledge of their labels. To determine the optimal number of clusters, we used the Silhouette Method. In terms of modelling, we applied k-means as well as DBSCAN to accurately group bitcoin addressed.

## Usage
1. Clone the repository:
```sh
    git clone https://github.com/gilianwagner100/Bitcoin-Classification-Clustering.git
    cd Bitcoin-Classification-Clustering
```
2. Install the required libraries:
```sh
    pip install -r requirements.txt
```
3. Open Jupyter Notebook:
```sh
    jupyter notebook
```
4. Run the notebook `Master_Notebook.ipynb` to see the implementation and results of the project.

## About
Students that developed this project:
- Gilian Wagner
- David Boros