The aim of this project is to identify metastatic cancer in digital pathology scans (96x96 pixels).

The dataset used in this project is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset. A positive label (1) indicates that the image contains at least one pixel of tumor tissue, while a zero label indicates there is no tumor tissue present in the image.

I am going to compare two CNNs: a very basic one focused on the center of the images (32x32 pixel selected area), and another using the entire image (after Gaussian Blur is applied) with batch normalization.
