Hi, this capstone project is about prediction of heart disease using different Machine Learning models which aim to detect the presence of heart disease based on medical attributes. All the computation, preprocessing and visualization was done on Jupyter notebook using Python. The data was collected from one of the open-source data platform i.e. #kaggle. The dataset consisted of 70,000 rows and 12 attributes, but after cleaning and preprocessing, it was reduced to approximately 51,948 rows and 10 attributes. 
Data processing, exploratory data analysis, and some data visualization bring out new insights from the medical dataset.
Since all attributes were categorical, outliers were removed to improve the model efficiency. 
To improve the convergence of the models, I applied k-modes clustering to preprocess the dataset and scale it.
To enhance the methodology, irrelevant information was eliminated, and incorporate additional features such as MAP and BMI.
To improve the performance and interpretability of classification algorithms, applied binning method for continuous inputs (Age, BMI, and MAP), which makes it easier to understand and interpret the relationship between the input variables and the output classes.
 Next, separated the dataset based on gender and implemented k-modes clustering. Finally, I proceeded with training the model with the processed data. The improved methodology produced more accurate results and superior model performance.
The algorithms used in this study were Random Forest, Decision tree Classifier, Logistic Regression, and SVM, together with K-mode classification.
The dataset was split into two parts: 80% of the data used to train model and 20% used to test the model.
This study used several measures of performance, namely, precision, recall, accuracy, and F1 score. 
The following insights that I have extracted from the data.
1.	How does age effect the likelihood of developing heart disease.
2.	Does inactive lifestyle and contribute to the disease.
3.	Body weight or BMI significance in developing disease compared to a normal weighing person.
4.	Abnormal pulse rate (High blood pressure) impact on onset of heart disease.
5.	Gender analysis: Understanding the unique characteristics and progression of disease in Men and Women.
6.	Cholesterol levels significance in developing disease.
The high number on Distribution of correlation features Age, BMI, MAP.
Amongst the 4 Machine Learning model, SVM is the most promising model for heart disease prediction with 86.4% accuracy.
