Kaggle Workbook: https://www.kaggle.com/code/altasshrugs/braintumorclass/notebook 

Imagine if you could take a picture of a spot that has recently appeared on your skin and have an app tell you whether or not you should actually be worried about it. While they shouldn't aim to replace doctors or dispense medical advice, large scale deep learning models have the potential to bring efficient and affordable medical care to billions of people around the world.

The purpose of this project is to create a deep learning model capable of classifying and potentially segmenting (that is, drawing an area around) brain tumors from MRI scan images. This sort of classification project could assist doctors in diagnoses & automate tumor measurements with potentially life-saving impacts.

## The Dataset
The repository contains a curated/enhanced version of brain MRI scan images derived from two publicly available datasets. It is suitable for both classification and segmentation, including tumor type detection. The original datasets (and their enhancements) are noted as follows:

### Kaggle Brain Tumor MRI Dataset [5]
This dataset contains 3D MRI scans categorized into four classes:
* No tumor
* Glioma tumor
* Meningioma tumor
* Pituitary tumor
* 
### SciDB Brain Tumor Dataset [6]
This dataset contains pixel-level annotated MRI slices with tumor segmentation masks for various types of tumors.

These datasets were "enhanced" with image preprocessing including normalization of the pixel intensity and noise reduction. Each entry in the dataset consists of an MRI image, a segmentation mask, and a classification label. There are approximately 5,000 images total.

## Plan of Action
I will tackle the classification problem for this project, first using a 'basic' CNN with hyperparameter tuning and then using ResNet50, a 50-layer Residual Neural Network (RNN) that is often used for image classification. ResNet50 was trained on the ImageNet dataset, so it will be interesting to see how it compares to the CNN.
