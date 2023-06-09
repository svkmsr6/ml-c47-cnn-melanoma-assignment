# Melanoma Detection Assignment
> The aim is to build a multiclass classification model using a custom convolutional neural network in TensorFlow which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- The data set being used can be found [here](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view). It consists of images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In real time, datasets will have an unbalanced set of different classes. Theses can be rebalanced using image augmentation
- Manual augmentation reduces overfitting, but alone cannot improve accuracy
- Using Augmentor the class imbalance can be handled effectively and accuracy can also be improved

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Augmentor 
- Numpy
- Pandas
- Tensorflow / Keras

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@svkmsr6] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
