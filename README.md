# IVF-Success-Prediction-Phase-1-
This is the phase-1 of our project.

# Description of the project

This project consists of a comparitive analysis between four machine learning models namely Gradient Boosting, Random Forest, Support Vector Machine, and Logistic Regression. 
Our project consisted of the following steps: 
1.	Data Collection : In this stage we collected real time IVF data from Dr P. Thamilselvan. 
2.	Data Preprocessing: Since the data we obtained was raw data, processing the data involved a very long and tedious method. We handled the missing values in columns by imputation, dropping columns and treating missing values as a separate category. Further to develop a model with this data we were required to standardize the same. After data standardization we converted the categorical variables to numeric. Further we also studied the different features available to us using Exploratory Data Analysis. 
3.	Feature Engineering : This phase consisted to 2 sub parts: 

      3.1	Feature Selection : In this phase we evaluated the important features using five feature selection techniques. From which we generated the top 20 features of each technique and further classified the most occurring features as important. Those features were namely : Age(F), Duration of infertility(years), BMI(F), Psychological and Emotional, Strain of repeated treatment, Gross and Microscopic Appearance, Sperm Motility, Sperm Vitality, No. Of Oocytes Retrieved, No. Of Embryos Transferred. 

      3.2	Feature Extraction : In feature extraction we used PCA. To determine the number of PC’s required we plotted a scree plot(attached below). Further we plotted a heat map to show the important features. (attached below) 

4.	Model Building : We built 4 machine learning classification models namely RF, SVM, Gradient Boosting and Logistic Regression. We evaluated our models on the basis of three criteria’s Accuracy, Specificity, and Sensitivity. For building the models we split our dataset into train and test data with a 80:20 ratio. Further to increase the accuracy of the same we tuned the parameters of the same. 

5. Results : 
  
      RF :
      1.	Accuracy : 0.86 
      2.	Specificity : 0.93
      3.	Sensitivity : 0.75	

      SVM: 
      1.	Accuracy: 0.65 
      2.	Specificity: 1.00
      3.	Sensitivity: 0.00

      Gradient Boosting : 
      1.	Accuracy: 0.87 
      2.	Specificity: 0.93
      3.	Sensitivity: 0.75	

      Logistic Regression : 
      1.	Accuracy: 0.85
      2.	Specificity: 0.90
      3.	Sensitivity: 0.75


# Future Work 
Our future work would consist of giving the result in a percentage form rather than simple classification. We would also include hyperparameter tuning to add improve the accuracy of our models. We would include advanced machine learning and deep learning techinques to get better results.
