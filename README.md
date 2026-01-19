# Car Sales Clustering Analysis

This project performs a clusterization analysis on a car sales dataset (sourced from Kaggle) to identify distinct customer segments. By understanding these segments, businesses can tailor their marketing, inventory, and sales strategies to better meet customer needs.

## Project Overview

The main objective is to group customers based on their demographic information and purchasing behavior. The project involves:
- **Data Preprocessing:** Cleaning, handling categorical data, and feature scaling.
- **Exploratory Data Analysis (EDA):** Visualizing distributions, correlations, and preferences using `Plotly`, `Seaborn`, and `Matplotlib`.
- **Dimensionality Reduction:** Using PCA to reduce the feature space while retaining key information.
- **Clustering Algorithms:** Implementing and comparing K-Means, Agglomerative Clustering, and DBSCAN.
- **Model Evaluation:** Using Calinski-Harabasz and Davies-Bouldin scores to determine the best clustering approach.

## Key Features

- **Data Cleaning:** Removal of irrelevant identifiers (ID, Phone, Name, etc.).
- **Categorical Encoding:** Label encoding for categorical features like Company, Model, and Body Style.
- **Interactive Visualizations:** High-quality plots including:
  - Car Price vs. Annual Income.
  - Distribution of Gender and Model Preferences.
  - Income Distribution by Dealer Region.
  - Correlation Heatmaps.
- **Clustering Comparison:**
  - **K-Means:** Best for tight, well-defined clusters (Highest CH Score).
  - **DBSCAN:** Best for identifying outliers and well-separated segments (Lowest DB Score).
  - **Agglomerative Clustering:** Provides a hierarchical perspective.

## Business Insights

The identified clusters provide actionable strategies for:
1. **Targeted Marketing:** Personalizing messages based on income and model preference.
2. **Inventory Management:** Stocking popular models based on regional demand.
3. **Pricing Strategy:** Adjusting price points for different demographic segments.
4. **Sales Optimization:** Training teams on features most valued by specific clusters.

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd clustering_car_sales
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis:**
   Open the Jupyter Notebook and run all cells:
   ```bash
   jupyter notebook "Final Project.ipynb"
   ```

## Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `plotly`
- `yellowbrick`
- `tabulate`

---
*Dataset source: Kaggle*
