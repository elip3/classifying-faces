# Facial Classifier

**Model predicting age, race, and gender of all individuals present in an image**
-  Achieves an average 85% accuracy across all three dependent variables 
-  CNN model built and trained in PyTorch

## Model details
The underlying Convolutional Neural Network uses a pretrained Squeeze and Excitation Network (SENet), trained on VGGFace2

The model was fine tuned for classification of tightly cropped facial images using the UTKFace dataset
- https://susanqq.github.io/UTKFace/


