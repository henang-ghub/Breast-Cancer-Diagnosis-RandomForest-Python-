# Breast-Cancer-Diagnosis-RandomForest-Python
Machine learning classification model to predict whether a breast tumour is malignant (1) or benign (0) using diagnostic cell features. The project applies Random Forest, an ensemble learning technique, to improve prediction accuracy and robustness in a healthcare context.

**Overview**
This project applies a Random Forest classifier to predict whether a breast tumour is malignant (cancerous) or benign (non-cancerous) based on diagnostic cell features.
Accurate classification can support early detection and assist healthcare professionals in making informed decisions.

## Objective
Build a machine learning model that:
- Classifies tumours as malignant (1) or benign (0) 
- Achieves high accuracy and recall (especially for malignant cases) 
-	Identifies the most important diagnostic features 

## Dataset
The dataset consists of 9 input features derived from cell analysis:
1. Clump Thickness	Cell layering structure
2. Uniformity of Cell Size	-  Consistency in cell size
3. Uniformity of Cell Shape	- Consistency in cell shape
4. Marginal Adhesion	- Cell cohesion strength
5. Single Epithelial Cell - Size	Size of epithelial cells
6. Bare Nuclei	- Presence of exposed nuclei
7. Bland Chromatin	- Uniformity of genetic material
8. Normal Nucleoli	- Structure of nucleoli
9. Mitoses	- Cell division rate
    
**Target Variable:**
-	Class → 0 (Benign), 1 (Malignant) 

## Tech 
-	Python 
-	Pandas – Data manipulation 
-	NumPy – Numerical operations 
-	Scikit-learn – Machine learning 
-	Matplotlib / Seaborn – Data visualization 
-	Jupyter Notebook 

## Project Workflow
**1.	Data Loading and Cleaning**
-	Checking for missing values, data types, inconsistences and duplicates  
-	The  dataset was reported clean and ready for analysis .

**2. Exploratory Data Analysis (EDA)**
-	Checked class Distribution 
-	Generated summary statistics 

**3. Model Building**

Used Random Forest Classifier, an ensemble learning method that combines multiple decision trees to improve accuracy.
-	Train-test split: 70/30 
-	Hyperparameter optimization: 
-	n_estimators = 100
-	max_depth = 10
-	Random state =  42

**4. Model Evaluation**

Evaluated performance using:
- Accuracy (95%)
-	Precision 
-	Recall 
-	F1-score 
-	Confusion Matrix 

 ## Key Insights
-	The model achieved an accuracy of 95%, meaning 95% of the samples were classified correctly.
-	Random Forest reduces overfitting compared to a single decision tree 
-	Model performs well in identifying high-risk cases 

## Future Improvements
-	Use larger, real-world datasets
