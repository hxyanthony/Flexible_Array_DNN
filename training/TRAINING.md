# Training Tutorial

- The training data should be the stacked raw RF channel data, the size of input training data cube should be: 

**N×R×S×D**

where **N** is the amount of training data, **R** is the number of active receiving elements, **S** is the number of scanlines, **D** is the number of samples in depth dimension.

For example, if you are traning the network with **N=1000** RF channel data, collected from transducer with **R=128** receiving elements and **S=64** scanlines, the size of input training data cube should be: **1000×128×64×256**, as the depth dimension is always resized to **D=256** samples.




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
