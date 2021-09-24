# Train-and-Deploy-a-CNN-Model-Using-TensorFlow-Serving

DESCRIPTION

You’re a Computer Vision Engineer at health.ai. Your company is developing a deep learning application to automate the detection of diabetic retinopathy. The company is sourcing high-resolution retina image data from various clinical partners but the dataset is expected to be huge and cannot be stored on a central system. You’re asked to build a proof of concept using the Kaggle retinopathy dataset to train a CNN model with the Mirrored Strategy and deploy it with TensorFlow Serving. 

 

Objective: To build a CNN model using distributed training that can detect diabetic retinopathy and deploy it using TensorFlow Serving.

     

Dataset Details: 

The dataset contains a large set of high-resolution retina images taken under a variety of imaging conditions. A left and right field is provided for every subject. Images are labeled with a subject id as well as either left or right. A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4. Like any real-world dataset, you will encounter noise in both the images and labels. Images may contain artifacts, be out of focus, underexposed, or overexposed. 

 

Link to the Dataset: https://www.dropbox.com/sh/7z7xq2lq3ogspcv/AACF_50dOtFaVYoII80abNPLa?dl=0

     

Prerequisites:

TensorFlow

Keras

TensorFlow Serving

 

Steps to be followed: 

Download and preprocess the dataset to correct for noise and under and over exposure

Augment the dataset and split it into training and test sets

Define the distributed training strategy

Define the number of shared instances

Define a CNN architecture to extract features from the model data

Define parameters like the loss, optimizer, epochs, learning rate, and evaluation metric

Define checkpoints

Train the model until an accuracy of at least 80% is obtained

Save the model

Deploy the saved model using TensorFlow Serving
