# Heart-disease-prediction-ML-project
An approach to predict if a patient is affected by CAD(coronary artery disease), a major heart disease using supervised machine learning algorithms.
# Problem statement:
Among all fatal diseases heart diseases are considered to be the most fatal diseases.Traditional screening tools lack efficiency in the early detection of asymptomatic heart diseases. Machine learning techniques help in prediction and thus early detection and cure of fatal diseases.
This project aims at analysing the heart disease dataset and using machine learning algorithms inorder to predict the presence of CAD(coronary artery disease) in patients.
# Dataset details:
The heart disease dataset is curated by combining 5 popular heart disease datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

1. Cleveland
2. Hungarian
3. Switzerland
4. Long Beach VA
5. Statlog (Heart) Data Set
# Toolkit
Data pre-processing
pandas
numpy
# EDA and data visualization
seaborn
matplotlib
pandas
numpy
# SVM and Random Forest model generation and accuracy measures
scikit-learn
numpy
pandas
yellowbrick
# Artificial Neural network
Keras
scikit-learn
pandas
# Methods
Initially data cleaning and preprocessing was performed. Exploratory data analysis was done. Visualization tools were used create plots for better undersatnding. 
To predict the presence of heart disease in a patient machine learning techniques were used.
Supervised machine learning algorithms used:
1. Support vector machine(SVM)
2. RandomForest classifier

To compare between the models the accuracy, classification report, confusion matrix and AUC-ROC curve for the respective models were found.

An attempt to build a simple artificial neural network was also done.
The model has 11 input parameters with 11 neurons and activation='relu' in the first hidden layer followed by the next layer with activation='sigmoid'.
During the compilation of the model optimizer='adam', loss='binary_crossentropy' (since the target variables are binary in nature) and metrics=['accuracy'] was used.The neural network was trained with 300 epochs and the accuracy was found.
# Conclusion 
SVM classifier was found to have an accuracy of about 84%
RandomForest classifier was found to have an accuracy of 82%
ANN model was found to have an accuracy of 79%
# Installation
To run this code in your local system you have to download this repository using-

git clone https://github.com/PrakruthiBalagopal/Heart-disease-prediction-ML-project

Now open the downloaded directory and install the required python packages using-
pip install -r requirements.txt
# Scope and future enhancements
The scope of the project is that integration of clinical decisions with computer-based patient records could reduce medical errors, enhance patient safety, decrease any human biases and improve patient outcome. 
In future work, the creation of more complex ML algorithms is much needed to increase the efﬁciency of disease prediction.Datasets should be expanded on different demo-graphics to avoid overﬁtting and increase the accuracy ofthe deployed models. Finally, more relevant feature selection methods can be used to enhance the performance of the learning models.
# Author
Name: Prakruthi B Gopal




