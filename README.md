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

All the well-trained model dictionaries in our paper are available as follows:

 Network      | Dictionary Name     | Dictionary Link     
 :----------: | :-------------:  | :-------------: 
 U-Net     | UNet_dict.pth     | [U-Net Model](https://drive.google.com/file/d/1bv7Xk95gQmaqFDsrojisjN-aFpo0DajS/view?usp=sharing)  
 Pix2Pix GAN     | Pix2PixGAN_Patch_G_dict.pth     | [Pix2Pix GAN Model](https://drive.google.com/file/d/1tMqfo0WtQcfH6URfbNAmSYCKVG828kwa/view?usp=sharing)   
 CycleGAN     | CycleGAN_Patch_GA_dict.pth     | [CycleGAN Model](https://drive.google.com/file/d/1cwFMPQitdPT2EnTxUZROVxufx-INyVDO/view?usp=sharing)   

Download the dictionaries to the same path as the testing codes and load them.
