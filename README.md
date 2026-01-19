# AI_MI_Intern_T3
# Project Summary: Iris Dataset Exploratory Analysis
In this project, we performed a step-by-step Exploratory Data Analysis (EDA) and predictive assessment of the **Iris flower dataset** ("C:/Users/waghu/OneDrive/Desktop/ELEVATE Labs/iris.csv"). The goal was to identify patterns, evaluate data quality, and determine which physical characteristics are most useful for distinguishing between iris species.
#What Was Performed
#1. Statistical Distribution Analysis
We used **histograms** and density plots to visualize the spread of the four numerical features.
* **Result:** We identified that petal measurements are bimodal, clearly separating the *Setosa* species from others.
# 2. Class Balance Verification
We created **count plots** for the `species` categorical column.
* **Result:** Confirmed the dataset is perfectly balanced with 50 samples per species, ensuring no class bias during analysis.
# 3. Outlier Identification
Using **box plots**, we inspected the dataset for extreme values that might skew results.
* **Result:** We found that `sepal_width` is the only feature containing outliers.
# 4. Correlation Mapping
We generated a **correlation heatmap** to find relationships between variables.
* **Result:** Discovered a massive correlation (0.96) between `petal_length` and `petal_width`, indicating these features provide almost identical information.
# 5. Feature Importance Modeling
We trained a **Random Forest Classifier** to rank which features actually drive the prediction of the iris species.
* **Result:** Petal length was identified as the #1 predictor, while sepal width was found to be the least significant.

# Final Conclusions
The analysis reveals that **petal dimensions** are the most critical factors in identifying an Iris species. Because the data is balanced and mostly free of outliers, it serves as an excellent foundation for building highly accurate machine learning classification models.
