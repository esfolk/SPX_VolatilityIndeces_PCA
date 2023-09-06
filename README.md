# SPX_VolatilityIndeces_PCA_TSNE


## PCA Analysis on Financial Indices

### Project Overview

This repository contains an exploratory analysis of various financial indices, including the S&P 500 Index, VIX, VVIX, MOVE, Skew, and Short Vol Index, using Principal Component Analysis (PCA). 

### Objectives:

- **Dimensionality Reduction**: Identify the key principal components that capture most of the variance in the data.
- **Relationship Understanding**: Determine which indices are most closely correlated based on their loadings on the principal components.
- **Visualization**: Visualize the data in the reduced PCA space to identify patterns, clusters, or outliers.
- **Noise Removal**: Utilize PCA to emphasize important signals and patterns while discarding noise.

### Quick Start:

1. **Clone the Repository**:
    ```
    git clone [https://github.com/esfolk/SPX_VolatilityIndeces_PCA.git]
    ```

2. **Navigate to the Directory**:
    ```
    cd [SPX_VolatilityIndeces_PCA]
    ```

3. **Install Required Libraries** (assuming you have `pip` installed):
    ```
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook**:
    ```
    jupyter notebook PCA_Financial_Indices_Analysis.ipynb
    ```

### Results:

- The first three principal components capture approximately 84.77% of the total variance in the data.
- Visualization in the PCA space revealed the structure and patterns of the data.
- Loadings provide insights into which original indices are most correlated.

Let's summarize the t-SNE results and provide a comprehensive analysis of the clusters based on the visualization and previous discussions.

---

## Summary of t-SNE Results on Financial Indices (2017-2023)

### **Introduction:**
t-SNE (t-distributed Stochastic Neighbor Embedding) was applied to the dataset containing daily values of various financial indices from 2017 to 2023. The purpose of this analysis was to visualize the inherent structures in the data in a two-dimensional space, identifying patterns, clusters, and potential anomalies.

### **Main Findings:**

1. **Distinct Clusters**: The t-SNE visualization revealed distinct clusters, indicating inherent groupings in the data. These clusters represent observations (days) that share similar characteristics based on the provided financial indices.

2. **Central Dense Region**: A predominant cluster in the center of the plot might represent 'typical' or 'common' market behavior. This suggests that for a significant portion of the time frame, the market exhibited consistent behavior based on the input indices.

3. **Peripheral Clusters**: Surrounding the central dense region, there were smaller clusters or groups of points. These could represent unique patterns of market behavior that occurred less frequently but were still distinct from the norm.

4. **Overlapping Clusters**: The overlapping of different colors (representing different principal components) in certain areas of the plot suggests periods where multiple market indices had closely aligned influences. This could indicate days of heightened market interconnectedness or significant economic events affecting multiple indices simultaneously.

5. **Potential Anomalies**: Scattered points distant from the main clusters may indicate days with unusual market behaviors. These could be outliers or anomalies worth investigating further, as they might correspond to unexpected market events or data errors.

6. **Mixed Regions**: Areas where all three principal component colors (red, blue, green) cluster closely together indicate convergence in the behavior of the financial indices associated with each principal component. These regions suggest days where the differentiating characteristics of each index were less pronounced.

### **Implications and Recommendations**:

- **Market Strategy**: Investors and market analysts can utilize these clusters to identify and study recurring market behaviors. Understanding these patterns can inform trading strategies, risk assessment, and forecasting.

- **Further Investigation**: The outliers or anomalies identified could be subject to further investigation to understand the underlying causes. Were they due to significant market events, data errors, or other factors?

- **Refinement and Additional Analysis**: The t-SNE visualization provides a high-level view of the data's structure. For detailed insights, one might consider segmenting the data further, conducting time series analyses on specific clusters, or exploring correlations with external economic factors.

### **Conclusion**:
The t-SNE analysis on the financial indices from 2017 to 2023 has provided valuable insights into the market's behavior patterns during this period. The identified clusters and patterns can serve as a foundation for more in-depth analyses, helping stakeholders make informed decisions.

---
