## About
Skin cancer is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopic analysis, a biopsy and histopathological examination. 
Automated classification of skin lesions using images is a challenging task owing to the fine-grained variability in the appearance of skin lesions.

### Model

**We have created a model to detect and classify a mole into benign or malignant.**
The dataset is taken from the ISIC (International Skin Image Collaboration) Archive.
It consists of 1800 pictures of benign moles and 1497 pictures of malignant classified moles. The pictures have all been resized to low resolution (224x224x3) RGB. 

As the dataset is pretty balanced, the model will be tested on the accuracy score, thus (TP + TN)/(ALL).

It has 2 different classes of skin cancer which are listed below :
1. Benign
2. Malignant

In this kernel we will try to detect 2 different classes of moles using Convolution Neural Network with keras tensorflow in backend and then analyse the result to see how the model can be useful in practical scenario.
