# NSL-KDD-Instrusion-Detection-Analysis
NSL-KDD (for network-based intrusion detection systems (IDS)) is a dataset suggested to solve some of the inherent problems of the parent KDD'99 dataset. This IDS basically helps to determine security of systems and alarming when intrusion is noticed or detected. Choosing NSL-KDD provides insightful analysis using various machine learning algorithms for intrusion detection. Myself expecting to explore intuitive insights of intrusion detection and work on various machine learning algorithms that is reasonable to understand future instance of attacks and its types.

<img align = "center" width= "1000" src = "https://cdn.sketchbubble.com/pub/media/catalog/product/optimized1/8/f/8fc687d53e8cadebc099f6a79f456550c5109b9c344dd65d48f58f891f8b4788/intrusion-detection-system-mc-slide1_1.png">

Data Analysis performed in 4 stages.

1. Data Preprocessing
2. EDA (Exploratory Data Analysis)
3. Machine Learning Modeling
4. Conclusion


Conclusion: 
It was a great exploration and learning in path and dive of this data analysis. Critically examining things of each variable and understanding through insightful visualizations is the key factor of any data analysis. Initial process of this data analysis went through EDA (Exploratory Data Analysis) which includes pre-processing the data and creating meaningful visualizations to understand data better. Later, the data was prepared using hot-encoding for class variables to categorize data into 5 groups as Normal, Dos, Probe, R2L and U2R. Which was later helpful to understand any future instance in machine learning modeling process. Modeling has done using following ways.

1. Initially train_df was split into train and test data using train_test_split method from sklearn. This is helpful to train and test the data before we encounter with unseen data.
2. Trained 3 algorithms. 1. Decision Tree 2. KNN 3. Logistic Regression
3. All three algorithms have been evaluated on testing data which was initially split from train_df
4. Later apart, All algorithms have been evaluated with new and unseen data which is test_df
5. Finalized data results using confusion matrix plot.

Decision Tree algorithm has performed reliably on new and unseen data for classifying labels (0, 1, 2, 3 and 4). Which his more preferred to be used for future instances.

Also, in terms of execution performance, KNN took execution time longer than Decision Tree and Logistic Regression. Although it has not performed well.
