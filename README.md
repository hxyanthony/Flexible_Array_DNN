# Deep Learning for Ultrasound Beamforming in Flexible Array Transducer

### By Xinyue Huang, Muyinatu Bell, and Kai Ding

This is a PyTorch implementation of the paper 'Deep Learning for Ultrasound Beamforming in Flexible Array Transducer' for the IEEE Transactions on Medical Imaging 'Second Special Issue On Machine Learning for Image Reconstructions'.

![alt text](https://github.com/PickleJerry/Flexible_Array_DNN/blob/main/figure/pipeline.png)

# Installation

Assuming Anaconda with python 3.7, an example for installing this project is as follows:
``` Bash
  conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
```
Then clone or download this repo to local.

# Training

# Dataset

Unfortunately we cannot share the entire training dataset. You can download an example training dataset here, and you are welcomed to train the models with your own dataset.

The testing data of CIRS phantom and ABDFAN phantom are included in the [testing](https://github.com/PickleJerry/Flexible_Array_DNN/tree/main/testing) folder.

# Model Dictionary

All the well-trained models in our apaper are available as follows:

 Network      | 第一列     | Model link     
 -------- | :-----------:  | :-----------: 
 U-Net     | 第一列     | 第二列  
 -------- | :-----------:  | :-----------: 
 Pix2Pix GAN     | 第一列     | 第二列  
 -------- | :-----------:  | :-----------: 
 CycleGAN     | 第一列     | 第二列  
