## Welcome to GitHub Pages

## Algorithms 101

## Neural Network
Read some fuxxxxx papers, then we talks.

### Open Datasets   
 + Cifar-10
 + Cifar-100
 
### CNN

- Lenet-5<br>
    Classic CNN structure to classification. Introduced by Lecun. <br>
    An tensorflow implementation of Lenet-5 was writen to train on Cifar-10 dataset.
- Facenet<br>
    [Paper](https://arxiv.org/abs/1503.03832) arxiv 1503.03832<br>

##### Weight Initiation
Papers related to new techniques for dealing with weights
[Understanding the difficulty of training deep feedforward neural networks](http://jmlr.org/proceedings/papers/v9/glorot10a/glorot10a.pdf)
[Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification](https://arxiv.org/pdf/1502.01852v1.pdf)
[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167v2.pdf)

##### How to go deeper?
Try and use deeper architectures, which have general tendency to blow up or vanish the gradients. So new techniques were used to  circumnavigate the issues with deeper architectures.
 - Residual Nets
 - Batch normalisation techniques. 
    * They basically normalise the output of every conv layer, very much for the same reason that you normalised the input image before feeding it to the net.

##### Further Readings
Advanced layers Computer Vision Scientists use regularly in their nets
 - Batch Normalisation layers \[[Paper](https://arxiv.org/pdf/1502.03167v3.pdf)\] \[[TFLearn](http://tflearn.org/layers/normalization/#batch-normalization)\]
 - Deconvolutional layers \[[Paper](http://www.matthewzeiler.com/pubs/cvpr2010/cvpr2010.pdf)\] \[[TFLearn](http://tflearn.org/layers/conv/#convolution-2d-transpose)\]
 - Dilated Convolutional layers \[[TFLearn](http://tflearn.org/layers/conv/#atrous-convolution-2d)\]
 
The details of all these layers are there in the TFLearn modules.

### RNN

##### Basic Concepts
 - [Andrej Karpathy's lecture](https://www.youtube.com/watch?v=iX5V1WpxxkY) on RNNs and LSTMs from CS231n(Youtube).
 - [A great blog post](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) by Christopher Olah on how LSTMs work.
 - [Building an RNN](http://r2rt.com/recurrent-neural-networks-in-tensorflow-i.html) from the ground up in tensorflow.
 - [Building an RNN II](http://r2rt.com/recurrent-neural-networks-in-tensorflow-ii.html)

LSTMs is the technique makes RNN valuable.
 - [Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) step by step

##### Funny to Read
 - [RNN generate samples](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)


Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
