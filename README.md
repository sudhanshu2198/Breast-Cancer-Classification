

# Multi-Class Credit Score Classification

A mammogram is an X-ray of the breast. For many women, mammograms are the best way to find breast cancer early, when it is easier to treat and before it is big enough to feel or cause symptoms. Having regular mammograms can lower the risk of dying from breast cancer.This dataset was constructed by scanning the images, segmenting them into candidate objects, and using computer vision techniques to describe each candidate object.

![](https://github.com/sudhanshu2198/Breast-Cancer-Classification/blob/main/images/1.jpg)

## Dataset
- **Area**: Area of object (in pixels).
- **Grey Level**: Average gray level of the object.
- **Gradient Strength**: Gradient strength of the object's perimeter pixels.
- **Noise Fluctuation**: Root mean square noise fluctuation in the object.
- **Contrast**: average gray level of the object minus the average of a two-pixel wide border surrounding the object.
- **Shape Descriptor**: A low order moment based on shape descriptor.
- **Microcalcification**: Presence of Microcalcification clusters
There are two classes and the goal is to distinguish between Cancerous and non-Cancerous using the features for a given segmented object.

![](https://github.com/sudhanshu2198/Breast-Cancer-Classification/blob/main/images/2.PNG)
![](https://github.com/sudhanshu2198/Breast-Cancer-Classification/blob/main/images/3.PNG)

**The main goal of this project is to develop a machine learning model to predict whether a patient has breast cancer or not given extracted feature vector of Chest X-Ray images.**

## 🔗 Links

- [Dataset](https://www.kaggle.com/datasets/sudhanshu2198/microcalcification-classification)
- [Kaggle Notebook](https://www.kaggle.com/code/sudhanshu2198/techniques-for-imbalanced-classification-problems)

## 🛠 Frameworks
Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn, Imblearn, Xgboost, Lightgbm, Optuna

## Results
- The model achieved a F1-score of 0.96 on the Breast Cancer Detection Dataset with utilizing Support Vector Machine and threshold moving
- SVC with cost sensitive learning has result in best performance among all the predictors therefore we will be using Support Vector Classifier with cost sensitive learning.
### Precision Recall Curve
![](https://github.com/sudhanshu2198/Breast-Cancer-Classification/blob/main/images/4.PNG)
### Threhold Moving
![](https://github.com/sudhanshu2198/Breast-Cancer-Classification/blob/main/images/5.PNG)
### Confusion Matrix
![](https://github.com/sudhanshu2198/Breast-Cancer-Classification/blob/main/images/6.PNG)






