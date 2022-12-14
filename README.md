# Melanoma Detection with CNN
Build a CNN based model which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
>Provide general information about your project here.
>To build a CNN based model which can accurately detect melanoma.
>Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
>A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in    diagnosis.
> The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)


## Technologies Used
- Python - version 1.0
- Tensorflow - version 2.0
- Augmentor - version 3.0


## Conclusions
Model 1
- Model 1 was trained for 20 epochs with available data
- Observations:
    - Model is overfitting
        - Training accuracy increases exponentially
        - Validation accuracy increases initially and then remains constant
        - More data and more epochs may help
        - Handling class imbalance might help


Model 2
- Model 2 was trained for 20 epochs with keras built-in data augmentation.
- Following augmentations were used
   - Rotation
   - Flip - vertical and horizontal
- Observations:
   - Overfitting reduced compared to Model 1
   - But accuracy also decreased - which means, fewer epochs results in underfitting
   - Therefore Data augmentation helped in reducing overfitting
   - More epochs to be considered to better the accuracy


Model 3
- Model 3 was trained for 50 epochs
- Applied augmentation to handle imbalance
- 500 images are generated for each class in addition to existing images
- Observations:
  - Final model is still overfitting slightly
  - Validation accuracy increases initially and then remains constant
  - Validation loss reduces initially and increases exponentially after few epochs
  - Rebalancing the data may help achieve a good accuracy 

Model 4
- Model 4 was trained for 20 epochs
- 1000 additional images are generated for each class in addition to existing images
- Observations:
  - 
  - 
  - 


## Acknowledgements
- Tensorflow image classification tutorial


## Contact
Created by [@NatrajNaikar] - feel free to contact me!
