# My-Paypal

### Project Overview
This project delves into the realm of machine learning to develop and compare two powerful models for fraud detection: Logistic Regression and Neural Network. By leveraging a dataset containing credit card transactions, I aim to create models that can accurately distinguish between legitimate and fraudulent activities.

### Data source
The dataset used for this project is a credit card transaction dataset that contains information about transactions, including whether they are fraudulent or not, It contains information about the time, amount, and class (fraudulent or valid) of each transaction. The data set was produced by the Qwasar silicon Valley learning plartform where I was trained

### Steps

- Data Wrangling:
  This initial step involves accessing my data and checking to ensure interity and accurate model performance
- Exploratory Data Analysis:
  This step involves exploring the dataset to understand its structure and characteristics. I visualized the distribution of numeric variables, compute the correlation matrix, and analyze the class distribution.
- Data Pre-processing:
  Prior to model building, I performed data pre-processing steps, including standardizing the time and amount features and balancing the class labels by upsampling the minority class (fraud).

- Building ML Models:
   I was able to train two models for this project
1. Logistic Regression
I trained a Logistic Regression classifier on the pre-processed data. I evaluate its performance using accuracy, and classification report and visualize the results with a confusion matrix and ROC curve.

2. Neural Network
I built a Neural Network using TensorFlow/Keras. The architecture includes an input layer, two hidden layers, and an output layer. I compiled and train the model, and then evaluate its performance on the validation set.
- Model Evaluation:
  I assessed the models' performance using metrics such as accuracy, precision, recall, and F1-score. The evaluation provides insights into how well each model predicts fraudulent transactions.

- Visualizing Model Performance:
I visualized the performance of the models using confusion matrices, ROC curves, and learning curves. These visualizations help interpret the models' behavior and identify potential areas for improvement.
  

