# This repo is for the final project for BIOF399 course 

# Aim of project

To make a model to predict the stage of Alzheimers using CNNs

## Data
Data is available at https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images

About the data directory.
The MRI Images have already been converted to .jpg in the dataset
Dataset consists of two files - Training and Testing both containing a total of around ~5000 images each segregated into the severity of Alzheimer's

Classes:

1. MildDemented
2. VeryMildDemented
3. NonDemented 
4. ModerateDemeneted

![Screen Shot 2021-03-16 at 11 19 15 AM](https://user-images.githubusercontent.com/32390297/111333825-662ea680-8649-11eb-9319-59a1781cdcef.png)


## This repository contains 

### The data set is also present in this repository "Alzheimer_s Dataset"

### The final file with all the code is final_project_SK.ipynb in this repository

### The pretrained model is alzheimer_model.h5

### You can look at the "final_project_SK.pdf" file for the results and the way the code runs

### The model summary is present in "modelsummary.txt" and "model.png"

![Screen Shot 2021-03-16 at 11 19 54 AM](https://user-images.githubusercontent.com/32390297/111333904-7c3c6700-8649-11eb-8b02-e211d2d8ddbf.png)


![model](https://user-images.githubusercontent.com/32390297/111333978-8c544680-8649-11eb-8f42-e2eb02fa673d.png)

## Results from training the model on training dataset and validation dataset

![Model_Results](https://user-images.githubusercontent.com/32390297/111334092-a726bb00-8649-11eb-9610-dcf39cb86e7f.png)


### The results from fitting the test dataset to the model are present in "modelscores_on_test_dataset.txt"

- Accuracy =  0.7961297631263733
- Precision =  0.5973597168922424
- Recall =  0.5660672187805176
- AUC =  0.832899272441864

