# image_classification_mask
The purpose of this notebook is to build an image classification model to detect if the subject in the image worn his mask correct.

# 3 models were built:
Base model using VGG architecture (without transfer learning)
Using VGG architecture with transfer learning
Using SVM as the classification (instead of softmax) using NASNet

# Result:
The models were evaluated based on their accuracy. The model with the best weights were saved for later prediction.
Accuracy of base model = 98.477%
Accuracy of model with transfer learning = 98.58%
Accuracy of model with SVM = 83.9%

# Data
The data used in this notebook can be found in this link (https://github.com/cabani/MaskedFace-Net).

# Citation/Credits
1. Adnane Cabani, Karim Hammoudi, Halim Benhabiles, and Mahmoud Melkemi, "MaskedFace-Net - A dataset of correctly/incorrectly masked face images in the context of COVID-19", Smart Health, ISSN 2352-6483, Elsevier, 2020, DOI:10.1016/j.smhl.2020.100144

2. Karim Hammoudi, Adnane Cabani, Halim Benhabiles, and Mahmoud Melkemi,"Validating the correct wearing of protection mask by taking a selfie: design of a mobile application "CheckYourMask" to limit the spread of COVID-19", CMES-Computer Modeling in Engineering & Sciences, Vol.124, No.3, pp. 1049-1059, 2020, DOI:10.32604/cmes.2020.011663

# Licences
The licenses of MaskedFace-Net dataset: The dataset is made available under Creative Commons BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/) license by NVIDIA Corporation.
