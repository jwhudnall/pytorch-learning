# PyTorch Training Material
These files represent my self-created PyTorch learning path.

**Includes:**
* FreeCodeCamp's ***PyTorch for Deep Learning***
* Daniel Godoy's ***Understanding PyTorch with an example: a step-by-step tutorial*** 
* DeepLizard's [Neural Network Programming - Deep Learning with PyTorch](https://deeplizard.com/learn/playlist/PLZbbT5o_s2xrfNyHZsM6ufI0iZENK9xgG)


### Misc ML Tidbits
* ImageNet classification with deep convolutional neural networks. Alexnet in 2012 was the “big bang” of modern AI.
* Output channels = no longer color channels, but modified color channels, also referred to as feature maps. These feature maps are the output of the convolutions that take place. 
* Dataset Validation and test set should have the same mix/frequency of observations that will be seen. Training set should have an equal number in each class; if not, replicate the less common one until it is more equal. Paper Link
* Max Pooling - reduces the resolution of the given output of a convolutional layer, the network looks at larger  areas of the image at a time going forward, reducing the amount of parameters and computational load. May also help reduce overfitting. Picks out the most activated pixels and preserves them for the following computation, discarding the lower value pixels. 
