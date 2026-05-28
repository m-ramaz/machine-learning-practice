#Outlier Removal using Z-Score on Binomial
DataThis project demonstrates how to detect and remove outliers from a dataset using the Z-score method. The statistical approach is specifically tailored for data following a Binomial Distribution.
Project OverviewOutliers can heavily skew machine learning models. This project addresses that issue by applying a mathematically sound filtering technique to clean the dataset before training.
MethodologyDistribution Analysis: Identified that the target feature/data follows a Binomial Distribution.Z-Score Calculation: Computed the standard scores using the mean (\(\mu = np\)) and standard deviation (\(\sigma = \sqrt{np(1-p)}\)) of the distribution.
Threshold Filtering: Removed data points that fall outside the standard threshold (typically \(Z > 3\) or \(Z < -3\)).🛠️ Technologies Used:
PythonPandas (Data manipulation)
NumPy (Mathematical operations)
Matplotlib / Seaborn (Data visualization)
