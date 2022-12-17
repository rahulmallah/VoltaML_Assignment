# VoltaML_Assignment

![1_p4LFBwyHtCw_Qq9paDampA](https://cdn.britannica.com/89/140889-050-EC3F00BF/Ripening-heads-rice-Oryza-sativa.jpg)

### Problem Statement
Rice (Oryza sativa) is one of the staple foods worldwide. Paddy, the raw grain before removal of husk, is cultivated in tropical climates, mainly in Asian countries. Paddy cultivation requires consistent supervision because several diseases and pests might affect the paddy crops, leading to up to 70% yield loss. Expert supervision is usually necessary to mitigate these diseases and prevent crop loss. With the limited availability of crop protection experts, manual disease diagnosis is tedious and expensive. Thus, it is increasingly important to automate the disease identification process by leveraging computer vision-based techniques that achieved promising results in various domains.

### Objective of the project
The main objective of this project is to develop a machine or deep learning-based model to classify the given paddy leaf images accurately. The dataset provide a training dataset of 10,407 (75%) labeled images across ten classes (nine disease categories and normal leaf). Moreover, we also provide additional metadata for each image, such as the paddy variety and age. Your task is to classify each paddy image in the given test dataset of 3,469 (25%) images into one of the nine disease categories or a normal leaf

### About the dataset
We provide a training dataset of 10,407 (75%) labeled paddy leaf images across ten classes (nine diseases and normal leaf). We also provide additional metadata for each image, such as the paddy variety and age. Our task is to develop an accurate disease classification model using the training dataset and then classify each sample in the test dataset of 3,469 (25%) paddy leaf images into one of the nine diseases or normal leaf.

##### Files

1. train.csv - The training set

image_id - Unique image identifier corresponds to image file names (.jpg) found in the train_images directory.
label - Type of paddy disease, also the target class. There are ten categories, including the normal leaf.
variety - The name of the paddy variety.
age - Age of the paddy in days.

2. sample_submission.csv - Sample submission file.

3. train_images - This directory contains 10,407 training images stored under different sub-directories corresponding to ten target classes. Filename corresponds to the image_id column of train.csv.

4. test_images - This directory contains 3,469 test set images.
