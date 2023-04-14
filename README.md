#UTOR_Project4_Team5
#Comparing Different Machine Learning Models for Breast Cancer Diagnosis


# Comparing Supervised and Unsupervised Learning Algorithms for Breast Cancer Diagnosis

#### Google Slides
#### Jupyter Notebook – Data Extraction - https://github.com/Ahmadhha/UTOR_Project4_Team5/blob/main/Data%20Extraction.ipynb
#### Jupyter Notebook – Machine Learning - https://github.com/Ahmadhha/UTOR_Project4_Team5/blob/main/Machine%20Learning.ipynb
#### Tableau Dashboard – Breast Cancer - https://public.tableau.com/app/profile/andreza.dos.santos6466/viz/BreastCancer-MeanProject/Story1?publish=yes
#### Tableau Dashboard – Performance Comparison - https://public.tableau.com/authoring/Performance_Comparison/Models_Evaluation_Performance#1
#### Data Source - https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?select=data.csv

## Background
This project aims to evaluate and compare the effectiveness of various supervised and unsupervised learning algorithms in accurately classifying breast cancer as malignant or benign, using the Breast Cancer Wisconsin (Diagnostic) dataset. The study assessed the performance of Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), Neural Network and K-Nearest-Neighbour (KNN) algorithms based on metrics such as accuracy, precision, recall, and F1 score. However, it should be noted that the study is limited to the dataset's features, and other risk factors or clinical information may impact breast cancer diagnosis. Additionally, the chosen algorithms may not be the most optimal for this task.

## Research Question
Among the various supervised and unsupervised learning algorithms evaluated in this study using the Breast Cancer Wisconsin (Diagnostic) dataset, which one performed the most effective in accurately classifying breast cancer as malignant or benign?

## Methods

### Machine Learning Analysis Performed
Diagnosis of breast masses as benign or malignant: Machine learning analysis will be performed on this dataset to build a predictive model that can distinguish between benign and malignant breast masses.

5 Supervised learning and 1 unsupervised learning models will be compared to identified that most optimum algorithm for this data set.

### Supervised learning algorithms to explore are:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - Neural Network

### Unupervised learning algorithms to explore is:
  - K-Nearest-Neighbour (KNN)

### Diagnosis of breast masses ( benign or malignant)
The problem of diagnosing breast cancer as malignant or benign is a binary classification problem, as there are only two possible outcomes. Therefore, we can build a binary classification model using supervised learning algorithms.


## Results

### Accuracy

<img width="181" alt="image" src="https://user-images.githubusercontent.com/115505106/231871921-1ce96e2d-adf0-4146-bae0-3f6cb2472b62.png">


![image](https://user-images.githubusercontent.com/115505106/231871653-2d148649-b063-45b1-8193-b68bc0d1d18e.png)


### Precision

<img width="187" alt="image" src="https://user-images.githubusercontent.com/115505106/231871601-81f92ca8-1ebb-42bc-9cc6-4c9e4c2bd670.png">

![image](https://user-images.githubusercontent.com/115505106/231871681-75231e3f-91fc-40f3-a9e0-4a2bd635a810.png)

### Conclusion

### Limitation
This research project solely focused on analyzing the Breast Cancer Wisconsin (Diagnostic) dataset, which contains information on ten specific features of cell nuclei extracted from fine needle aspirate images of breast masses. It is important to note that the dataset's limited scope excludes other possible risk factors and clinical data that could impact breast cancer diagnosis. Furthermore, this study solely evaluate the performance of the selected supervised and unupervised learning algorithms and may not consider alternative algorithms or techniques that may prove more effective for diagnosing breast cancer.

### Disclaimer
The Breast Cancer Wisconsin (Diagnostic) dataset is made available for academic purposes only. The dataset contains information on characteristics of cell nuclei present in fine needle aspirate (FNA) images of breast masses. The dataset is intended to be used for research and educational purposes only and not for gaining commercial benefits. The dataset does not contain any sensitive personal information of individuals. The dataset is provided as is, without any warranty, express or implied, including without limitation, warranties of merchantability or fitness for a particular purpose. Users are responsible for ensuring that their use of the dataset complies with all applicable laws and regulations. The creators and distributors of the dataset are not liable for any damages arising from the use of the dataset.
