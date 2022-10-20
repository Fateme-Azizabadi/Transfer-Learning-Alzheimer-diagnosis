# Alzheimer's diagnosis with the help of Transfer Learning 

This project aims to diagnose Alzheimer's based on Non-Demented and Mild Demented scans using transfer training algorithms.
VGG19, NasNetLarge, Inception_V3, and Xception are investigated. (The network is implemented with the help of Transfer Learning.) 

* These models are trained for 500 IPACs on about 200 demented and 200 non-demented images.

* The dataset for this project was collected from the Kaggle website posted by Sarvesh Dubey. We used
this dataset to perform binary classification between Non-Demented and Mild Demented images. Although the source contained about 2000 images, we used only 200 images per category in this section. Sequentially, the images were preprocessed to resize to (229* 229), 80% of the images were used as training_data, and 20% were used as test_data.

Alzheimer's Dataset link: (https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images)

The image below and the table compare the model's results. 

 
 ![](https://github.com/Fateme-Azizabadi/Transfer-Learning-Alzheimer's-diagnosis/blob/main/Images/Comparing.Models.Results.png)

 ![](https://github.com/Fateme-Azizabadi/Transfer-Learning-Alzheimer's-diagnosis/blob/main/Images/Performance.png)
 
 ![](https://github.com/Fateme-Azizabadi/Transfer-Learning-Alzheimer's-diagnosis/blob/main/Images/Output.png)
 