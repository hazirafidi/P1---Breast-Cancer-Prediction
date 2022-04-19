# P1---Breast-Cancer-Prediction
 Breast cancer prediction using Feedforward Neural Network

## 1. Project Summary
This project is carried out to construct and build a model that can predict Breast Cancer disease based on the features given in the dataset. The labels are classification problem where the results are either "Maglinant" or "Benign". Deep learning approach is implemented by building a Feedforward Neural Network for this project. The data is retrived from this [Link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

## 2. IDE and Framework
The project is carried out in Jupyter Notebook as the main IDE and trained via Google Colab. The main frameworks used in this project are TensorFlow, Numpy, Matplotlib, and Scikit-learn.

## 3. Methodology
In this project, sequential model from tensorflow is used to create a feedforward neural network model.The model is trained based on 30 features in the dataset which are as in figure below.

![image](https://user-images.githubusercontent.com/100177902/163941375-da8a2c9d-18ae-48ba-b5fd-a8e86e000b61.png)

### 3.1 Data Pipeline
The dataset is in the format of csv file. The csv file is loaded via pandas read. The data is further splitted into train and test data using Scikit-learn with the ratio of 80:20.

### 3.2 Model Pipeline
The model architecture can be illustrated as in figure below.

![image](https://user-images.githubusercontent.com/100177902/163952090-7dee87cc-099d-452b-abcc-3c8540b97b7c.png)

The model is trained with epochs set to 100. No Early stopping applied in the model training. The model performance is evaluated afterwards with the result of 96% Training Accuracy and 18% Loss. The results are as shown in figure below.

![image](https://user-images.githubusercontent.com/100177902/163952637-a30d73b6-2648-430f-84f7-00f6434b1544.png)

The model performance curve which are Training vs Vakidation Loss and Training vs Validation Accuracy can be refer as in figure below.

![image](https://user-images.githubusercontent.com/100177902/163953126-de8b90ff-b7c9-40de-ad0e-2db0d5cf04bf.png)

![image](https://user-images.githubusercontent.com/100177902/163953206-c02ad325-61de-42d5-bca8-646785bf8672.png)

