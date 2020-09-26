# Brain-Tumor-Segmentation
An application which detects the tumor spots from  MRI Scan and helps to diagnose whether it is a tumor/non-tumor

### Description:
As years go by, people with their lifestyle changing there is an mutual increase in the health risks they may have to face.Cancer/Tumor is one of the major health issue that is prevailing in this world.Cancer can occur in many parts of the body and could lead to loss of life but immediate diagnosis at starting stage can help in recovery.

In this project we will be dealing with Brain Tumor/Cancer,we will be looking how to diagnose at first stage using segmentations do detect whether a tumor is present in the brain.

### Dataset:

For this project I used Brain MRI segmentation (Brain MRI images together with manual FLAIR abnormality segmentation masks) dataset from Kaggle [link](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation). This dataset contains brain MRI images together with manual FLAIR abnormality segmentation masks. We will be using segmentation algorithms for detecting whether a tumor is present in the brain.

### Models Used:

For this project I used UNet model and Res-UNet(Resblocks with UNet) where we will be using the training data to train the model and we will be testing with our test data.

#### UNet

![alt text](https://github.com/ShapeAI/Brain-Tumor-Segmentation/blob/master/Unet.png "UNet Architecture")


#### Res-UNet
![alt text](https://github.com/ShapeAI/Brain-Tumor-Segmentation/blob/master/Resunet.png "Res-UNet Architecture")



### Steps to run the project:


1.Install the dataset from kaggle or use Kaggle notebooks or used Colab using api key from Kaggle for getting the dataset from kaggle.


2.Then copy the cells from the code in this project and implement the project.


3.Use GPU preferably, if not have one use Kaggle notebooks or Colab by enabling GPU runtime option and then getting the dataset.


## Contibutors:

### KARTHIKEYAN JM 
![alt text](https://github.com/ShapeAI/realtime-semantic-segmentation/blob/master/50882125.png "Contributor")

### SHAPE AI
![alt text](https://github.com/ShapeAI/realtime-semantic-segmentation/blob/master/69104283.jfif "Contributor")






