# SPX_VolatilityIndeces_PCA


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

### Contributing:

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### License:

[MIT](https://choosealicense.com/licenses/mit/)

---

Note: The placeholders like `https://github.com/esfolk/SPX_VolatilityIndeces_PCA.git` and `SPX_VolatilityIndeces_PCA` should be replaced with the actual links or names relevant to your GitHub repository. Adjust the Quick Start steps based on your repository structure and any additional steps you might have.
