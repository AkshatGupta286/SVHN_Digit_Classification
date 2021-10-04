# Digit Classification using SVHN Dataset

## Overview
In this work, I have created a Convolutional Neural Network (CNN) based Deep Learning model to perform digit classification. I have used SVHN Dataset for the same.

## SVHN Dataset
The dataset contains 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9, and '0' has label 10. It is a pretty large dataset with 73257 digits for training and 26032 digits for testing. Data is in the format of 32x32 images centered around a single character.  
You can get more information about the dataset here: http://ufldl.stanford.edu/housenumbers/

## Installation
To use this repo, create a conda environment using ```environment.yml```

```
# from environment.yml
conda env create -f environment.yml
```

Download the dataset using the links given below:  
Training Data: http://ufldl.stanford.edu/housenumbers/train_32x32.mat  
Test Data: http://ufldl.stanford.edu/housenumbers/test_32x32.mat  

Rename both the files as ```svhn_train.mat``` and ```svhn_test.mat``` respectively.
Store the files in the outermost folder with the following folder structure ```Datasets/svhn_train.mat``` and ```Datasets/svhn_test.mat```

## Results
I could achieve an accuracy of ```90%``` on the test data.
