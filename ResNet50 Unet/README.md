### ResNet50 Based Unet

Unet is a popular image segmentation method used for semantic segmentaion. The architecture of Unet is shown below. This architecture was purposed in 2015 for biomedical image segmenation tasks. The Architecture and the original paper for U-Net is mentioned below

![Original Unet Architecture](https://miro.medium.com/v2/resize:fit:4800/format:webp/0*38vydfXeaN0Nc1p7.png)

Original Unet Paper: [U-Net for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf)

As compared to the orignal implementation of U-Net, this variation of U-Net uses a ResNet50 network pretrained on ImageNet for the Encoder. The Decoder and the bridge connection is as same as the original U-Net implementation.

In place of ResNet50 other pretrained models such as VGG19, MobileNet or any other model can be used for the Encoding process

Necessary Libraries are mentioned on the requirements.txt file
> pip install -r requirements.txt

The dataset used on the notebook could be found on Kaggle on provided link 
[Data Science Bowl 2018](https://www.kaggle.com/competitions/data-science-bowl-2018/overview)
