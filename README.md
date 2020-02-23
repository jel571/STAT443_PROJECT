# STAT443 - Project masterplan

### Presentation requirements

1. Description of the problem
  * Given an extreme amount of predictors and a discrete amount of classes as our response, we want to build a process that can detect which class a given observation belongs to given all X_i's.
1. NN architectures
1. Introduction to linear algebra of NNs
  * vectors
  * matrices
  * dot-product
  * introduce a structure for NNs showing the start (784 input), hidden layers, and output (10 classes) (diagram!)
1. Introduction to activation functions
  * ReLU (rectified linear units)
  * the Softmax function
1. Introduction to output distribution
  * probability distributions over categories
1. How it learns
  * categorical cross-entropy
1. Comparison against other methods
  * why this is better than logistic model prediction or other types of unsupervised learning
1. How we implemented this
  * we used Keras, a high-level library for building machine learning algorithms
1. Demo
  * with consultation with Resource (1)
  * fast live prediction, maybe plot 6-10 images in a single plot to showcase the examples and their prediction
1. Applicability to other areas
  * sorting recyclables
  * medical field (early detection of breast cancer, etc)
  * autonomous vehicles
  * facial recognition
### Work distribution
Uniform:

1. Team will work at the same time through atom.io
1. Team will attempt to understand and document the R code together so they all learn and understand the implementation
1. Presentation website will also be written in a collaborative manner and the R Markdown code implemented as a team

### Resources

1. [R classification tutorial](https://cran.r-project.org/web/packages/keras/vignettes/tutorial_basic_classification.html)
1. Some review paper of classification approaches
  * [Artificial Neural Networks in Image Processing for Early Detection of Breast Cancer] (http://downloads.hindawi.com/journals/cmmm/2017/2610628.pdf)
  * [Fixed point optimization of deep convolutional neural networks for object recognition](https://ieeexplore.ieee.org/abstract/document/7178146)
1. [3B1B video series on neural networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
1. fashion mnist rundown (https://github.com/zalandoresearch/fashion-mnist/blob/master/README.md) also exists on the arxiv; link leads to same md (https://arxiv.org/abs/1708.07747)
1. [Activation functions](https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6)
1. [ReLU] (https://www.kaggle.com/dansbecker/rectified-linear-units-relu-in-deep-learning)
