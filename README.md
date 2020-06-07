
# Melanoma Skin Binary Imagine Classification

Melanoma is one of three types of skin cancers that starts in skin cells called melanocytes. Melanoma is a type of cancer that could be visible on top of the skin like a mold or spot in the surface of the skin.  Cancer is always something that completely affects the person but also family and friends of the affected.  Treatments are also long, painful, and tedious. However, as a human being we have to see the positive side even in the dark moments. The good thing about this type of cancer is that if it is detected in an early stage it could be treatable and it will give a high probability of rate of survival. However, if it’s not detected at an early stage it could spread very easily to other parts of the body and be fatal.  


# Overview

The objective of our product is based in a Machine Learning application which will try to reduce mortality by having an early detection. The tool we have created is an application for medical professionals to detect Melanoma in an early stage which will be extremely helpful for dermatologists to detect the cancer on time and treat it as soon as possible


# Models Used

* XGBoost
* Classification Models such as Random Forest,Decision Tree
* CNN Models

## Training Dataset
The dataset was collected from ISIC 2016 competiton dataset (https://challenge.kitware.com/#phase/5667455bcad3a56fac786791) and consisted of  900 dermoscopic lesion images in JPEG format. All images are named using the scheme ISIC_<image_id>.jpg, where <image_id> is a 7-digit unique identifier. EXIF tags in the images have been removed; any remaining EXIF tags should not be relied upon to provide accurate metadata.

The Training Ground Truth file is a single CSV (comma-separated value) file, containing 2 columns and 900 rows. The first column of each row contains a string of the form ISIC_<image_id>, where <image_id> matches the corresponding Training Data image. The second column of each row contains either the string:

* Benign: representing non-malignant
* Malignant: representing malignant

The training dataset was split in the ratio 80:20

## Test Data
Given the Test Data file, a ZIP file of 379 images of the exact same format as the Training Data, participants are expected to generate and submit a file of Test Results.

# Evaluation Methodology:

* Accuracy
* ROC AUC Curve
* Confusion Matrix
* F1 Score

# Results

The XGBoost model showed the best accuracy ratings among the models

Please check the Melanoma Skin Binary Image Classification document for more information

# Credits

This project completed in collaboration with Achal Suresh(asuresh6@jhu.edu), Mark Rao, Maitreiyi Maheshwari,Maria Vargas,Lu Cao,Ruchika Raikar







