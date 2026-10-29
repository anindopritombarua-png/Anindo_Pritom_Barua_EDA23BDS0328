# Exploratory Data Analysis (EDA) Project

## Student Information

**Name:** ANINDO PRITOM BARUA  
**Registration Number:** 23BDS0328  
**Program:** B.Tech Computer Science and Engineering – Data Science  
**Institution:** VIT Vellore

---

## Project Overview

This project performs Exploratory Data Analysis (EDA), statistical analysis, clustering, dimensionality reduction, and regression modeling using the **Indian Food Dataset**.

The project is organized into three phases:

- **Phase 1:** Data Preparation and Exploratory Data Analysis
- **Phase 2:** Statistical Analysis and Clustering
- **Phase 3:** Dimensionality Reduction and Simple Linear Regression

The project uses Python and Jupyter Notebook to explore data characteristics, identify patterns, visualize relationships, and apply statistical and machine learning techniques.

---

## Dataset: Indian Food Dataset

The dataset contains information about Indian dishes, including attributes such as:

- Dish name
- Ingredients
- Preparation time
- Cooking time
- Diet
- Flavor profile
- Course
- State
- Region

The dataset is cleaned, transformed, analyzed, and used for statistical modeling throughout the project.

---

# Phase 1 – Data Preparation and Exploratory Data Analysis

Phase 1 focuses on understanding the dataset, preparing the data, and identifying patterns through statistical summaries and visualization.

### 01. Loading Dataset

- Load the Indian Food dataset.
- Inspect the first and last records.
- Examine dataset dimensions, columns, and data types.
- Identify missing values and duplicate records.

### 02. Basic Statistical Analysis

- Calculate mean, median, and mode.
- Calculate variance and standard deviation.
- Examine minimum, maximum, range, quartiles, and interquartile range (IQR).
- Analyze categorical frequencies and unique values.

### 03. Handling Missing Data

- Identify missing values.
- Apply median imputation to numerical variables.
- Handle missing categorical values.
- Save the processed dataset.

### 04. Data Cleaning

- Remove duplicate records.
- Standardize column names.
- Clean inconsistent text values.
- Convert columns to appropriate data types.
- Check data consistency.

### 05. Data Transformation

- Calculate total preparation and cooking time.
- Create recipe-related derived features.
- Apply Min-Max normalization.
- Apply Z-score standardization.
- Perform log transformations where appropriate.

### 06. Univariate Analysis

- Examine individual variable distributions.
- Use histograms, boxplots, count plots, and distribution plots.
- Identify potential outliers and skewed distributions.

### 07. Bivariate Analysis

- Investigate relationships between pairs of variables.
- Use scatter plots, regression plots, and boxplots.
- Examine correlations and grouped comparisons.

### 08. Multivariate Analysis

- Explore relationships among multiple variables.
- Generate correlation heatmaps and pair plots.
- Create 3D visualizations, bubble plots, and parallel-coordinate plots.
- Examine multivariable patterns.

---

# Phase 2 – Statistical Analysis and Clustering

Phase 2 extends the exploratory analysis through one-dimensional, two-dimensional, and three-dimensional statistical techniques and unsupervised learning.

### 01. One-Dimensional (1D) Statistical Analysis

- Mean, median, and mode.
- Variance and standard deviation.
- Percentiles and IQR.
- Skewness and kurtosis.
- Outlier detection.
- Statistical visualizations.

### 02. Two-Dimensional (2D) Statistical Analysis

- Covariance analysis.
- Pearson and Spearman correlation.
- Regression analysis.
- Statistical significance testing.
- Scatter plots, heatmaps, and boxplots.

### 03. Three-Dimensional (3D) Statistical Analysis

- Three-dimensional scatter plots.
- Multivariable relationships.
- Correlation and covariance analysis.
- Grouped statistical summaries.

### 04. K-Means Clustering

K-Means clustering groups observations based on similarities in their selected numerical features.

The analysis includes:

- Feature standardization.
- Elbow method.
- Silhouette score.
- Cluster-count selection.
- Cluster assignments and profiles.
- 2D and 3D cluster visualizations.
- Export of the clustered dataset.

### 05. Hierarchical Clustering

Hierarchical clustering explores the nested grouping of observations.

The analysis includes:

- Single, complete, average, and Ward linkage.
- Dendrogram visualization.
- Linkage-method comparison.
- Agglomerative clustering.
- Cluster profiles and visualizations.
- Export of the clustered dataset.

---

# Phase 3 – Dimensionality Reduction and Regression

Phase 3 introduces dimensionality reduction and supervised regression modeling.

### Module 6: Dimensionality Reduction Using PCA

**Notebook:** `Module_6_Dimensionality_Reduction_PCA.ipynb`

This module explores techniques for representing data using fewer features while preserving useful information.

Topics include:

- Feature selection and preprocessing.
- Numerical feature standardization and categorical encoding where applicable.
- Principal Component Analysis (PCA).
- Explained variance and cumulative explained variance.
- Scree plot analysis.
- Two-dimensional and three-dimensional PCA projections.
- PCA feature loadings.
- Singular Value Decomposition (SVD).
- Factor Analysis.
- Intrinsic dimensionality estimation.
- Export of PCA results.

The objective is to understand how dimensionality reduction can simplify the representation of the Indian Food dataset.

### Module 7: Simple Linear Regression (SLR)

**Notebook:** `Module_7_Simple_Linear_Regression_SLR.ipynb`

Simple Linear Regression models the relationship between one independent variable and one continuous dependent variable.

The Indian Food analysis investigates the relationship between:

- **Independent variable:** Preparation time.
- **Dependent variable:** Cooking time.

Topics include:

- Dataset preparation and variable selection.
- Training and testing data split.
- Linear Regression model training.
- Regression coefficient and intercept.
- Prediction of cooking time.
- Mean Absolute Error (MAE).
- Mean Squared Error (MSE).
- Root Mean Squared Error (RMSE).
- Coefficient of Determination (R²).
- Actual-versus-predicted visualization.
- Residual analysis.
- Export of prediction results.

The objective is to evaluate how well preparation time alone explains variations in cooking time.

---

# Project Structure

```text
EDA_PROJECT_23BDS0328/
│
├── Phase 1/
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
├── Phase 2/
│   ├── 01_1D_Statistical_Analysis.ipynb
│   ├── 02_2D_Statistical_Analysis.ipynb
│   ├── 03_3D_Statistical_Analysis.ipynb
│   ├── 04_KMeans_Clustering.ipynb
│   ├── 05_Hierarchical_Clustering.ipynb
│   └── Processed and clustered CSV datasets
│
├── phase 3/
│   ├── Module_6_Dimensionality_Reduction_PCA.ipynb
│   ├── Module_7_Simple_Linear_Regression_SLR.ipynb
│   ├── indian_food_pca_results.csv
│   └── indian_food_slr_predictions.csv
│
└── .gitignore
```

---

# Technologies and Libraries

The project uses the following tools and Python libraries:

- **Python** – Main programming language.
- **Jupyter Notebook** – Interactive analysis environment.
- **Pandas** – Data loading, manipulation, and analysis.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **Scikit-learn** – Preprocessing, clustering, PCA, and regression.
- **SciPy** – Statistical analysis and hypothesis testing.

---

# Machine Learning Techniques

The project applies both unsupervised and supervised learning methods.

### Unsupervised Learning

- K-Means clustering.
- Hierarchical agglomerative clustering.
- Principal Component Analysis.
- Singular Value Decomposition.
- Factor Analysis.

### Supervised Learning

- Simple Linear Regression.
- Model prediction and evaluation using regression metrics.

---

# Conclusion

This project demonstrates a progressive data-analysis workflow, starting with dataset loading and cleaning and continuing through statistical analysis, visualization, clustering, dimensionality reduction, and regression modeling.

Phase 1 establishes the foundation through data preparation and exploratory analysis. Phase 2 investigates statistical relationships and discovers groups within the dataset. Phase 3 explores lower-dimensional representations and builds a regression model to study the relationship between preparation time and cooking time.

The project provides practical experience with Python-based data analysis, visualization, statistical methods, and introductory machine learning.

---

## Author

**ANINDO PRITOM BARUA**  
**Registration Number:** 23BDS0328  
**VIT Vellore
