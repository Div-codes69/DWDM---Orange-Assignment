# Diabetes Orange Experiment Guides

## 01 Data Cleaning
File -> Impute -> Data Table. Open the missing-value CSV; use Average/Most frequent.

## 02 Data Reduction
File -> Select Columns -> Data Table. Keep age, bmi, bp and ltg; set risk as target.

## 03 Data Transformation
File -> Normalize -> Data Table. Normalize numeric fields to [0, 1].

## 04 Association Rules
Select age, sex, bmi, bp, ltg, glu and risk. Discretize numeric features into three equal-frequency bins; use Apriori with 10% support and 80% confidence.

## 05 Statistical Analysis
Use Feature Statistics, Distributions and Box Plot to inspect descriptive values and compare bmi/ltg by risk.

## 06 Regression
Set progression as target. Compare Linear Regression, Random Forest and kNN using 10-fold cross-validation.

## 07 Outlier Analysis
Use age, bmi, bp, tc, ltg and glu. Configure covariance outliers with 10% contamination.

## 08 K-Means
Normalize six numeric predictors, then run k=3 with k-means++ and 10 restarts.

## 09 Simple K-Means
Use the same normalized predictors with k=2. Compare generated clusters against risk in Pivot Table.
