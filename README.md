# Pancreatic Cancer Detection
Pancreatic Cancer Detection Model Building:

Identify patients with Pancreatic Cancer using urine biomarkers

Background:
Pancreatic cancer is an extremely deadly type of cancer. Once diagnosed, the five-year survival rate is less than 10%. However, if pancreatic cancer is caught early, the odds of surviving are much better. Unfortunately, many cases of pancreatic cancer show no symptoms until the cancer has spread throughout the body. A diagnostic test to identify people with pancreatic cancer could be enormously helpful.

The paper:
In a paper by Silvana Debernardi and colleagues, published this year in the journal PLOS Medicine, a multi-national team of researchers sought to develop an accurate diagnostic test for the most common type of pancreatic cancer, called pancreatic ductal adenocarcinoma or PDAC. They gathered a series of biomarkers from the urine of three groups of patients:

Healthy controls:
Patients with non-cancerous pancreatic conditions, like chronic pancreatitis
Patients with pancreatic ductal adenocarcinoma
When possible, these patients were age- and sex-matched. The goal was to develop an accurate way to identify patients with pancreatic cancer.

Prediction task:
The goal in this dataset is predicting diagnosis, and more specifically, differentiating between 3 (pancreatic cancer) versus 2 (non-cancerous pancreas condition) and 1 (healthy). 

Predictor variables used are: age, sex, creatinine, LYVE1, REG1B, and TFF1.

Model Conclusions:
1. Normalized the data
2. Compared the accuracy of models between: Simple Logistic Regression, SVM and Decision Tree classifier and found that simple logistic regression works best here. Comparison made using K-fold cross validation method.
3. Final accuracy of the model: 80.9%
