# Machine Vision 
Development in the field of machine learning based computer vision.
Personal opinions but tried to be kept minimal.

# Methodology 
Starting with AlexNet paper, move to either side of the timeline with each paper having referral links to technologies or models. 
**Not all papers refer to the original introduction paper** , some papers might be a review because the main idea of this repository is to have a 




# 2010 - 2015

##  Dropout  `technique`
`2012 - 2014`
2014 : [Dropout: A Simple Way to Prevent Neural Networks from Overfitting](https://www.cs.toronto.edu/~rsalakhu/papers/srivastava14a.pdf)
2012  :  [Improving neural networks by preventing co-adaptation of feature detectors](https://arxiv.org/pdf/1207.0580.pdf)

##  AlexNet `model`
`2012`
[ImageNet Classification with Deep Convolutional Neural Networks](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) 

#### Key Aspects
**- Image Augmentation** 
**- Model Parameters** 
	- 
**- Regularization Tools**
	- Dropout (Not used as much anymore but is key in this era of papers )
- Showed the use of GPU for traning neural networks (CNN based GPU training)
- Make the argument that that operation of **convolution** is a very strong prior to learning information from images.
- Made Use of **RELU** 
- Split the model into 2 parts for easily fitting the weights in then GPU's
- Made use of **DROPOUT**

#### CURRENT RETROSPECTIVE 
- This paper is concerned with overfitting a lot but as of today, overfitting is not such a large issue as long as we build large enough models. 
- 

#### References
[Yannic Kilcher Video](https://youtu.be/Nq3auVtvd9Q)
[Analytics Vidya Article](https://www.analyticsvidhya.com/blog/2021/03/introduction-to-the-architecture-of-alexnet/)

##  VGGNet `model`
`2014`
[Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556)

## ResNet `model`
[Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)

-------------
-----------
----------


# 2015 - 2020


## Double Descent 
`2019`
[Deep Double Descent: Where Bigger Models and More Data Hurt](https://arxiv.org/abs/1912.02292)

## Transformers
`2017` 
[Attention Is All You Need](https://arxiv.org/abs/1706.03762)




# Trends 
1. **Dropout**  falling out of favor
	1.  Due to the large model sizes being used lately, fitting is a bigger problem for models than overfitting. 
	2. For smaller datasets, dropout may find some mileage but not so much as a general tool. 

2. **Channel Normalization** is replaced with **Batch Normalization**
	1. AlexNet uses channel normalization in its input pipeline whereas modern models use batch normalization 
	2. [This answer on StackExchange](https://stats.stackexchange.com/questions/211436/why-normalize-images-by-subtracting-datasets-image-mean-instead-of-the-current)
