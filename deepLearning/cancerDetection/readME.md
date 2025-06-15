Machine learning has many potential applications; however, none are (to me) more rewarding than its applications in medicine. This particular project aims to identify metastatic cancer in small image patches (the center 32x32 pixels) taken from larger digital pathology scans (96x96 pixels).

The dataset used in this project is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset. A positive label (1) indicates that the center of the image contains at least one pixel of tumor tissue, while a zero label indicates there is no tumor tissue present in the image. The outer pixels are present for padding and do not influence the label of the image. There are three parts of this dataset:

train folder -- containing training images
test folder -- containing testing images
train_labels.csv -- a file mapping training image names to labels
For this project, I am going to compare two CNN architectures: one very basic model, and another utilizing normalization layers (like BatchNormalization, etc).

The data is not included in this repo because it was very large. To access the data, please look here: https://www.kaggle.com/competitions/histopathologic-cancer-detection/data 
