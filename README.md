# diabetes-prediction-using-machine-learning

This Python code performs a comprehensive analysis and prediction of diabetes using a dataset. It begins by importing necessary libraries including NumPy, Pandas, Matplotlib, Seaborn, and various scikit-learn modules for data manipulation, visualization, model training, and evaluation.

The code first loads the diabetes prediction dataset, then explores the data using head, tail, and info methods. It checks for missing values and visualizes the data's cleanliness using a heatmap. Exploratory Data Analysis (EDA) is then conducted using histograms, bar plots, scatter plots, boxplots, violin plots, and pairplots to understand the distribution of various features like age, gender, BMI, blood glucose levels, HbA1c levels, and their relationships with diabetes. The distributions of hypertension, heart disease, and smoking history are also visualized.

Feature engineering is applied to handle categorical variables: 'gender' is mapped to numerical values and 'smoking_history' is one-hot encoded. The data is then split into training and testing sets.

Four machine learning models are trained: Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and an Ensemble Model (a Voting Classifier combining the three previous models). Each model is trained on the training data, predictions are made on the test data, and their accuracy and classification reports are printed.

Model evaluation is crucial, and ROC-AUC curves are generated for each model to visually compare their performance. The area under the curve (AUC) score, a measure of a classifier's ability to distinguish between classes, is calculated for each model. A bar chart visualizes the accuracy of all models.

Finally, the code demonstrates prediction using the Random Forest model, comparing 10 random actual and predicted diabetes values from the test set, to provide a practical example of how the model can be used for prediction. The entire process, from data exploration to model training and evaluation, demonstrates a standard machine learning workflow for classification tasks.
