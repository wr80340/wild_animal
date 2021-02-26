# Oregon Wildlife
## introduction
Wildlife image collection with 14013 image and 20 kinds of animal.  
task : image classification  
epoch : 100  
LR : 1e-4  
data link : https://www.kaggle.com/virtualdvid/oregon-wildlife   
## results 
pretrained weights | train accuracy | train loss | val accuracy | val loss | test accuracy | test loss 
--- | --- | --- | --- |--- |--- |--- 
vgg16 | **0.93** | 2.38 | 0.81 | 6.60 | 0.80 | 8.25
inception v3 | 0.82 | 4.63 | 0.83 | **4.67** | 0.82 | 4.99
resnet 101 | **0.93** | **1.93** | **0.84** | 4.71 | **0.86** | **4.77**
## training details
data augmentation : 
- flip up down left right
- adjust hue
- adjust saturation
- adjust contrast
## wandb details
https://wandb.ai/wr80340/animal
