# Emotion detection using Deep Learning
## Introduction
We have built a deep learning model which detects the real time emotions of students through a webcam so that teachers can understand if students are able to grasp the topic according to students' expressions or emotions and then deploy the model. The model is trained on the FER-2013 dataset(cleaned version) .This dataset consists of 48x48 sized face images with Five emotions - angry, disgusted, fearful, happy, and neutral.
## Dependencies
●	Python 3, OpenCV, Tensorflow

## Basic Usage
The repository is currently compatible with tensorflow-2.0 and makes use of the Keras API using the tensorflow.keras library.

●	First, clone the repository and enter the folder

https://github.com/jatin090/Jatin-Deep-Learning-Capstone-Face-Emotion-Recognition.git

I built a Transfer-Learning model to predict real-time emotion.

## Model Explanation - Jatin
The dataset which I used was the “Cleaned FER2013”  dataset from kaggle. You can download the dataset from the link below and copy paste the dataset in the folder.

https://www.kaggle.com/gauravsharma99/fer13-cleaned-dataset

![](modelimage.png)

 
This model gave an training accuracy of 77 and testing accuracy of 75. To access the dataset, unzip the zip file in this folder. This will create the folder dataset.

Since mobilenet model gave better accuracy this model was selected  further in the project.

