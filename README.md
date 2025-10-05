# Deep-Learning-with-PyTorch
This repository has lab demonstrations for paper MS 32 Deep Learning.
It has following lab demonstrations:
1. EfficientNet v2 demo in PyTorch			<br>																																																																																							
-Using pre-trained model for Test image classification, source: [How to Use EfficientNet-v2 for Image Classification with PyTorch](https://fxis.ai/edu/how-to-use-efficientnet-v2-for-image-classification-with-pytorch/) fxis.ai
EfficientNet – PyTorch <br>
-Fine-tuning EfficientNet v2 for underlying task of Olympic Game images, OGED-Olympic Games Event Dateset source: https://www.kaggle.com/datasets/yousefidris/ogedolympic-games-event-dateset<br>

3. ResNet demo <br>
-Using pre-trained ResNet for a Test image Classification(in 1000 categories) <br>
-ResNet Transfer Learning Demo <br>
Source of dataset: Tyre Quality Classification <br>
https://www.kaggle.com/datasets/warcoder/tyre-quality-classification
Digital images of defective and good condition tyres
4. Demo of CNN in PyTorch for MNIST classification <br>
Install timm package with: <br>
!pip install timm <br>
“PyTorch Image Models,” abbreviated as “timm”, a computer-vision model zoo and training toolkit created by Ross Wightman. <br>
import timm <br>
pretrained_resnet_34 = timm.create_model('resnet34', pretrained=True) <br>

Alternatively: <br>
import torchvision <br>
model =torchvision.models.resnet50(weights=torchvision.models.ResNet50_Weights.DEFAULT) <br>
