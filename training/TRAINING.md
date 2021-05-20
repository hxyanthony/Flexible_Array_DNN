# Training Tutorial

The size of training data cube should be: N*R*S*D

where N is the number of training data, R is the number of active receive elements, S is the number of scanlines, D is the number of samples in depth dimension.



# Installation

Assuming Anaconda with python 3.7, an example for installing this project is as follows:
``` Bash
  conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
```
Then clone or download this repo to local.

# Training

Read the [training tutorial]() for more details.

# Testing

Download the `testing dataset` and `well-trained model dictionaries`, then use the codes in the [testing](https://github.com/PickleJerry/Flexible_Array_DNN/tree/main/testing) folder to test different models.

# Dataset

You are welcomed to train the models with your own dataset.

The testing data of CIRS phantom and ABDFAN phantom are included in the [testing](https://github.com/PickleJerry/Flexible_Array_DNN/tree/main/testing) folder.
