# Potato-Crop-Disease-Classifier

## Summary
This repository contain files for a Potato Disease Classifier, the model is trained on Kaggle's Plant Village Dataset.<br>
This deep neural network is able to detect diseases encountered in the potato plant through images.This repository also contains files for creating a React JS app.

## Aim
The aim of the project is to create a classifier that could be employed in then agricultural sector, to classify crop diseases.

There are three states a potato crop plant has:
- Healthy
- Early Blight
- Late Blight

Globally The potato crop diseases are classified into two types: Early Blight and Late Blight, the treatments for these diseases differ slightly, so it is essential to determine what disease the crop is suffering from. 
- Healthy Crop: A healthy potato plant leaf has no discoloration, it is bright green in color and is free from any sort of specs. 
- Early Blight Crop: Early Blight is a disease in the Potato plant crop, its leaf has small dark specs that are distinct and small. 
- Late Blight Crop: Late Blight is a Potato crop disease that also has black specs, but they are considerably large and connected as compared to the Early Blight     disease. 


---------------

## Crop analysis

![image](https://user-images.githubusercontent.com/101527504/200467839-30eb14aa-b900-4c1a-9c04-2eac8ab12c28.png)


---------------------

## Dataset

- The dataset has been taken from Kaggle
- The dataset includes three classes and the dataset comprises of 2152 images and the distribution is given as: 
- Healthy Plant (152 images) 
- Late Blight (1000 images) 
- Early Blight (1000 images) 
- Link: https://www.kaggle.com/datasets/emmarex/plantdisease

-------------

## Model Features

- Tensorflow’s Keras library was used to make this sequential model 
- Data Augmentation techniques such as Rescaling, Resizing, Random-Flip and Rotation have been used to make a robust model.
- Optimizer: Adam 
- Loss Function: Sparse Categorical Cross Entropy 
- Epochs: 50 

--------------

## Metrics

On evaluation the following loss and accuracy were obtained: 
- Loss: 0.0141 
- Accuracy: 0.9961 <br>

![image](https://user-images.githubusercontent.com/101527504/200467811-0bd1d159-1fb6-4940-adae-b620dc9adf6d.png)




-------------

## Web Framework

- Web Framework: FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+.
- ASGI (UVICORN): Is The gateway inteface used for the web application is UVICORN. It’s a standard interface between async-capable Python web servers, frameworks, and applications.

![image](https://user-images.githubusercontent.com/101527504/200467670-ec57e4dd-fa60-4d4e-8711-7b62f3351be2.png)<br><br>
------------------

## Final Outlook<br>
![image](https://user-images.githubusercontent.com/101527504/200467754-d6faa242-f71c-4f24-ae51-0ef9f6ec0c20.png)






