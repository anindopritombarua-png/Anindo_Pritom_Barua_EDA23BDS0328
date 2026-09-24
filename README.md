# Exploratory Data Analysis (EDA) Project

## Student Information

**Name:** ANINDO PRITOM BARUA  
**Registration Number:** 23BDS0328  
**Program:** B.Tech Computer Science and Engineering – Data Science  
**Institution:** VIT Vellore

---

# Project Overview

This project presents an Exploratory Data Analysis (EDA) of an Indian Food Dataset.

The project is divided into two major phases:

- **Phase 1:** Data Preparation and Exploratory Data Analysis
- **Phase 2:** Statistical Analysis and Clustering

The analysis is implemented using **Python and Jupyter Notebook**.

---

# Dataset

### Indian Food Dataset

The dataset contains information about different Indian dishes, including attributes such as:

- Dish name
- Ingredients
- Preparation time
- Cooking time
- Total time
- Flavor profile
- Diet
- Course
- State
- Region

The dataset was cleaned and transformed before performing statistical and exploratory analysis.

---

# Phase 1 – Exploratory Data Analysis

Phase 1 contains the following notebooks:

### 01. Loading Dataset
- Loading the dataset
- Displaying initial records
- Checking dimensions
- Inspecting columns and data types
- Checking missing values and duplicates

### 02. Basic Statistical Analysis
- Mean
- Median
- Mode
- Standard deviation
- Variance
- Minimum and maximum
- Range
- Quartiles
- IQR
- Categorical frequency analysis

### 03. Handling Missing Data
- Identification of missing values
- Numerical missing-value treatment using median imputation
- Categorical missing-value treatment
- Creation of a processed dataset

### 04. Data Cleaning
- Duplicate removal
- Column-name standardization
- Text cleaning
- Data type conversion
- Consistency checks

### 05. Data Transformation
- Total preparation and cooking time
- Recipe classification
- Min-Max normalization
- Z-score standardization
- Log transformation

### 06. Univariate Analysis
Univariate analysis was performed using multiple visualizations, including:

- Histograms
- Boxplots
- Count plots
- Distribution plots

### 07. Bivariate Analysis
Bivariate relationships were investigated using:

- Scatter plots
- Regression plots
- Boxplots
- Correlation analysis

### 08. Multivariate Analysis
Multivariate relationships were explored using:

- Correlation heatmaps
- Pair plots
- 3D visualizations
- Bubble plots
- Parallel coordinates
- Multivariable scatter plots

---

# Phase 2 – Statistical Analysis and Clustering

### 01. 1D Statistical Analysis

Includes:

- Mean
- Median
- Mode
- Variance
- Standard deviation
- Percentiles
- IQR
- Skewness
- Kurtosis
- Outlier detection
- Statistical visualizations

### 02. 2D Statistical Analysis

Includes:

- Covariance
- Pearson correlation
- Spearman correlation
- Regression analysis
- Significance testing
- Scatter plots
- Heatmaps
- Boxplots

### 03. 3D Statistical Analysis

Includes:

- Three-dimensional statistical visualization
- 3D scatter plots
- Correlation analysis
- Covariance analysis
- Grouped statistical summaries

### 04. K-Means Clustering

K-Means clustering was performed using standardized numerical features.

The analysis includes:

- Feature standardization
- Elbow method
- Silhouette score
- Selection of cluster count
- Cluster assignment
- Cluster profiles
- 2D and 3D cluster visualization

The resulting clustered dataset is also saved as a CSV file.

### 05. Hierarchical Clustering

Hierarchical clustering was performed using different linkage methods:

- Single linkage
- Complete linkage
- Average linkage
- Ward linkage

The notebook includes:

- Dendrograms
- Linkage comparison
- Cluster evaluation
- Agglomerative clustering
- Cluster profiles
- 2D and 3D visualizations

The resulting clustered dataset is saved as a CSV file.

---

# Project Structure

```text
EDA_PROJECT_23BDS0328
│
├── Phase 1
│   ├── 01_Loading_Dataset.ipynb
│   ├── 02_Basic_Statistical_Analysis.ipynb
│   ├── 03_Handling_Missing_Data.ipynb
│   ├── 04_Data_Cleaning.ipynb
│   ├── 05_Data_Transformation.ipynb
│   ├── 06_Univariate_Analysis.ipynb
│   ├── 07_Bivariate_Analysis.ipynb
│   ├── 08_Multivariate_Analysis.ipynb
│   └── Processed CSV datasets
│
└── Phase 2
    ├── 01_1D_Statistical_Analysis.ipynb
    ├── 02_2D_Statistical_Analysis.ipynb
    ├── 03_3D_Statistical_Analysis.ipynb
    ├── 04_KMeans_Clustering.ipynb
    ├── 05_Hierarchical_Clustering.ipynb
    └── Processed and clustered CSV datasets
