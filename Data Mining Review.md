# 1. Data
* Data Type/ Data Set
* Data Quality
* Density

# 2. Clustering
* Type of cluster
    * Center-based
    * Contiguous
    * Density-based
    * Conceptual: points and squares
* K-means
    * Initial Centroid Problem
        * Multi-run
        * Hierarchical help
        * Over-select and then merge
    * Limitation
        * Size unequal
        * Density
        * Various shape
        * Outlier
* Hierarchical
    * Single Link: 
        * Pro: non-circle
        * Con: chain problem(noise)
    * Complete Link: 
        * Pro: good with noise
        * Con: break large cluster
    * Average Link: balanced both
* DBSCAN
    * Limitation:
        * Various density in one cluster
        * High dimension
* Validation(Internal)
    * SSE
    * Silhouette Co
    * Cohesion and Separation

# 3. Classification
* Feature Selection
    * Chi-square statistic
    * Information gain
    * Feature subset selection
* Class Imbalanced Problem
    * Use Evaluation Method like:
        * ROC
        * Precision/Recall
        * Kappa
    * Solution
        * Oversampling or Undersampling
* Overfitting or Underfitting
    * Generalization Error(test sets)
* Algorithm 
    * Decision Tree
    * Nearest Neighbor
    * Naive Bayes
    * SVM
        * Maximum margin
        * Kernal trick for non-linear
    * Random Forest
        * Decision Trees and vote

# 4. Association Analysis
* Frequent item
    * Apriori Algorithm  
* Association rules

# 5. Visualization(ggplot, R gallery)
* Histogram
* Box plot
* Violin plot
* Scatter plot
* Contour plot(global temp)
* Matrix plot
* Parallel Coordinate plot(high dimens)








