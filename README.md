# MobileNetV2

### MobileNetV2 is very similar to the original MobileNet, except that it uses inverted residual blocks with bottlenecking features. It has a drastically lower parameter count than the original MobileNet. MobileNets support any input size greater than 32 x 32, with larger image sizes offering better performance. MobileNetV2 uses both depthwise and pointwise convolutions to produce  depthwise-separable convolutions which allows the model to notice more features of our data.

#### The MobileNetV2 research was carried out by Mark Sandler and  Andrew Howard which by the way led to a great improvement and efficiency of  the model compared to the MobileNetV1. The major improvements was the residual skip connection which allows our model not to lose vital information by passing information from  the input via the
residual connection directly to  the output just like Resnet. They also added  bottlenecking features which  was an improvement from just the depthwise convolutions of the MobileNetV1, the bottlenecking features consist of a depthwise convolutions and pointwise convolutions which reduces the size and increase the size of the data respectively.

[<img target="_blank" src="https://user-images.githubusercontent.com/59423092/196147731-69694733-10df-43e3-8324-ac9b1791a96e.png" width=400>](https://images.app.goo.gl/mVfH3iFY85cnDoHe7/)
![image](https://user-images.githubusercontent.com/59423092/196147731-69694733-10df-43e3-8324-ac9b1791a96e.png)

## As part of the Google ML BootCamp Deep Learning.ai Course  2022, i  was tasked with the assignment to build a model that mimics the architecture of MobileNetV2 
