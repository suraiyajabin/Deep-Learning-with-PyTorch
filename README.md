# Deep-Learning-with-PyTorch
This repository has lab demonstrations for paper MS 32 Deep Learning.
It has following lab demonstrations:
1. EfficientNet v2 demo in PyTorch
-Using pre-trained model for Test image classification, source: How to Use EfficientNet-v2 for Image Classification with PyTorch fxis.ai
EfficientNet – PyTorch
-Fine-tuning EfficientNet v2 for underlying task of Olympic Game images, OGED-Olympic Games Event Dateset

2. ResNet demo
-Using pre-trained ResNet for a Test image Classification(in 1000 categories) 
-ResNet Transfer Learning Demo
Source of dataset: Tyre Quality Classification
https://www.kaggle.com/datasets/warcoder/tyre-quality-classification
Digital images of defective and good condition tyres
4. Demo of CNN in PyTorch for MNIST classification
Install timm package with:
!pip install timm
“PyTorch Image Models,” abbreviated as “timm”, a computer-vision model zoo and training toolkit created by Ross Wightman.
import timm
pretrained_resnet_34 = timm.create_model('resnet34', pretrained=True)

Alternatively:
import torchvision
model =torchvision.models.resnet50(weights=torchvision.models.ResNet50_Weights.DEFAULT)
