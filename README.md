# In this project, we aim to apply data machine learning techniques to analyze a cardiovascular dataset and predict the presence of heart disease.

The give dataset contains 14 attributes related to heart disease. It has  5 different outputs indicating the severity of heart disease.
Reduction algorithms are commonly used in machine learning and data analysis to reduce the dimensionality of datasets while preserving important information. Two commonly used reduction algorithms are Independent Component Analysis (ICA) and Linear Discriminant Analysis (LDA).
Classification algorithms are a type of machine learning algorithms that are used to classify data into different categories or classes based on certain features. Two commonly used classification algorithms are Support Vector Machines (SVM) and Random Forest.
K-means and fuzzy clustering are two popular techniques used in data clustering, which is the process of grouping similar objects or data points together based on certain characteristics.
Analysis:
We can see that the K-means algorithm without dimension reduction and the fuzzy clustering algorithm without dimension reduction both identified a cluster with a very small number of data points (cluster 2 in K-means and cluster 4 in fuzzy clustering). This suggests that these algorithms might not be the best choice for this particular dataset.
 
In contrast, the K-means algorithm with ICA dimension reduction and the fuzzy clustering algorithm with LDA dimension reduction did not have such a problem and identified clusters that are more evenly distributed. However, there are differences in the specific clusters that each algorithm identified as the largest (cluster 3 in K-means with ICA and cluster 2 in fuzzy clustering with LDA).
 
Overall, the choice of algorithm and dimension reduction technique depends on the specific dataset and the goals of the analysis. It's important to carefully consider the results and choose the approach that best suits the particular task at hand!








