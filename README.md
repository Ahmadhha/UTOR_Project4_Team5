#UTOR_Project4_Team5
#Comparing Different Machine Learning Models for Breast Cancer Diagnosis


# Comparing Supervised & Unsupervised Learning Models for Breast Cancer Diagnosis

[Data Extraction](https://github.com/Ahmadhha/UTOR_Project4_Team5/blob/main/Data%20Extraction.ipynb)

[Machine Learning Analysis](https://github.com/Ahmadhha/UTOR_Project4_Team5/blob/main/Machine%20Learning.ipynb)

[Data Visualization](https://public.tableau.com/app/profile/andreza.dos.santos6466/viz/BreastCancer-MeanProject/Story1?publish=yes)

[Evaluation Performance Comparison](https://public.tableau.com/authoring/Performance_Comparison/Models_Evaluation_Performance#1)

[Data Source](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data?select=data.csv)

## Background
Breast cancer is the most commonly diagnosed cancer among women globally, with an estimated 2.3 million new cases and 685,000 deaths in 2020. Early detection and diagnosis of breast cancer are critical for improving diagnostic outcomes and reducing mortality rates. According to the journal, The Breast, by 2040 the breast cancer burden will increase to more than 3 million new cases per year (an increase of 40%) and more than 1 million deaths per year (an increase of 50%).
Medical imaging techniques such as mammography and ultrasound, as well as histopathological examination of tissue samples obtained through biopsy, are commonly used to diagnose breast cancer.

Machine learning algorithms have shown promise in improving the accuracy and efficiency of breast cancer diagnosis. Several models, including logistic regression, decision trees, random forests, support vector machines, neural networks, and K-Nearest Neighbors (KNN), have been applied to breast cancer diagnosis datasets to predict the presence or absence of malignancy. These models used the ten real-valued features thaT are computed for each cell nucleus: such as radius (mean of distances from center to points on the perimeter), 
texture (standard deviation of gray-scale values), perimeter,area, smoothness (local variation in radius lengths), compactness (perimeter^2 / area - 1.0), concavity (severity of concave portions of the contour), concave points (number of concave portions of the contour), symmetry and fractal dimension ("coastline approximation" - 1).

Despite the promising results, the development of accurate and reliable machine learning models for breast cancer diagnosis remains a challenging task. Issues such as imbalanced datasets, feature selection, overfitting, and interpretability must be carefully addressed to ensure that the models are effective and clinically relevant. Also, the performance of the models may vary depending on the type and quality of the data used for training and testing.

Therefore, the goal of this study is to develop and evaluate various machine learning models for breast cancer diagnosis using a large, publicly available dataset. Specifically, we aim to compare the performance of logistic regression, decision trees, random forests, support vector machines, neural networks, and KNN on the dataset and determine which model is most effective for predicting breast cancer diagnosis. Also, we will explore various feature selection and performance evaluation techniques to optimize the models and provide insights into the relevant features that contribute to accurate diagnosis. The results of this study could have significant implications for improving the accuracy and efficiency of breast cancer diagnosis and eventually improving diagnostic outcomes.

## Research Question
Among the various supervised and unsupervised learning algorithms evaluated in this study using the Breast Cancer Wisconsin (Diagnostic) dataset, which one performed the most effective in accurately classifying breast cancer as malignant or benign?

## Methods

### Machine Learning Analysis Performed
Diagnosis of breast masses as benign or malignant: Machine learning analysis will be performed on this dataset to build a predictive model that can distinguish between benign and malignant breast masses.

### Diagnosis of breast masses ( benign or malignant)
The problem of diagnosing breast cancer as malignant or benign is a binary classification problem, as there are only two possible outcomes. Therefore, we can build a binary classification model using supervised learning algorithms.

5 Supervised learning and 1 unsupervised learning models will be compared to identified that most optimum algorithm for this data set.

### Supervised learning algorithms to explore are:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - Neural Network

### Unupervised learning algorithms to explore is:
  - K-Nearest-Neighbour (KNN)


## Results

### Accuracy

<img width="181" alt="image" src="https://user-images.githubusercontent.com/115505106/231871921-1ce96e2d-adf0-4146-bae0-3f6cb2472b62.png">


![image](https://user-images.githubusercontent.com/115505106/231871653-2d148649-b063-45b1-8193-b68bc0d1d18e.png)


### Precision

<img width="187" alt="image" src="https://user-images.githubusercontent.com/115505106/231871601-81f92ca8-1ebb-42bc-9cc6-4c9e4c2bd670.png">

![image](https://user-images.githubusercontent.com/115505106/231871681-75231e3f-91fc-40f3-a9e0-4a2bd635a810.png)


## Limitation
This research project solely focused on analyzing the Breast Cancer Wisconsin (Diagnostic) dataset, which contains information on ten specific features of cell nuclei extracted from fine needle aspirate images of breast masses. It is important to note that the dataset's limited scope excludes other possible risk factors and clinical data that could impact breast cancer diagnosis. Furthermore, this study solely evaluate the performance of the selected supervised and unupervised learning algorithms and may not consider alternative algorithms or techniques that may prove more effective for diagnosing breast cancer.


## Conclusion



### Disclaimer
The Breast Cancer Wisconsin (Diagnostic) dataset is made available for academic purposes only. The dataset contains information on characteristics of cell nuclei present in fine needle aspirate (FNA) images of breast masses. The dataset is intended to be used for research and educational purposes only and not for gaining commercial benefits. The dataset does not contain any sensitive personal information of individuals. The dataset is provided as is, without any warranty, express or implied, including without limitation, warranties of merchantability or fitness for a particular purpose. Users are responsible for ensuring that their use of the dataset complies with all applicable laws and regulations. The creators and distributors of the dataset are not liable for any damages arising from the use of the dataset.



Sources: 

https://www.iarc.who.int/news-events/current-and-future-burden-of-breast-cancer-global-statistics-for-2020-and-2040/

https://www.cancer.gov/types/breast/patient/breast-screening-pdq

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
