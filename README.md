# Effect-of-PCA-on-model-performace
A simple project to illustrate the effect of PCA (pricipal component analysis) on the accuracy score. In this project, we are going to do the following:
1. Load our dataset `heart.csv` 
2. Perform outlier detection and removal on some data features using zcore greater than -3 or less than 3.
3. Standardized our data. 
4. Building our machine learning model by comparing three different models (SVM, RandomForest, and Logistic Regression) on the same dataset. 
5. Now, we apply Dimensionality reduction technique using pca to see how it affect model's performance.


#### In conclusion:
It is obvious that the PCA has effect on the model performance, by reducing the accuracy score of the model. intuitively, this is correct has the PCA tends to eliminate non important features, it will lead to data loss which will in return affect the performance of the model. This could be a major disadvantage using PCA.

#### Advantages of PCA:
1. Faster training of the machine learning model and insight from data.
2. Clearer visualization of the dataset.

# To Do:
1. clone repository.
2. On Anaconda prompt, pip install -r requirements.txt
3. create a folder data and paste `heart.csv` in the data folder
4. open notebook
5. Contributions are highly welcome!
