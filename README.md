Introduction
--------------

This code mainly implement the paper [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](https://arxiv.org/abs/1703.06868) which address the problem of arbitrary style transfer in real-time. The main contribution of this paper is 'Adaptive Instance Normalization(AdaIN)' proposed by Xun Huang etc. 

![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/AdaIN.jpg)

Procedure of this method is as shown in follow figure.

![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/style_transfer_network.jpg)

How to train the network
------------------------

Python packages you need:

1. python 3.x
2. tensorflow 1.4.0
3. numpy
4. scipy
5. pillow

Data sets you need:

1. Content images data sets ([MSCOCO](http://images.cocodataset.org/zips/train2017.zip))
    Firstly, Unzip the MSCOCO dataset, and then put all images into the folder 'content'
2. Style images data sets ([wikiart](https://www.kaggle.com/c/painter-by-numbers/data))
    Firstly, Unzip the wikiart dataset, and then put all images into the folder 'style'
    
Pretrained model vgg19:

1. Please click [BaiduYun](https://pan.baidu.com/s/1CO-A2GOoym7eCw0hQsvEyw) to download
    when you have downloaded the file 'vgg.mat', put it into the folder 'vgg_para'.

Results of our code
--------------------

Style | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/ori.jpg) | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/ori1.jpg)
:-- | :--: | --:
![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/s1.jpg) | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/result1.jpg)  | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/result3.jpg)
![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/s2_3.jpg) | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/result6.jpg)  | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/result5.jpg)
![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/fire.jpg) | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/result7.jpg)  | ![](https://github.com/MingtaoGuo/Real-time-Arbitrary-Style-Transfer/blob/master/Figures/result4.jpg)
