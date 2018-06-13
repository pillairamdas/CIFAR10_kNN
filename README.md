# Classifying CIFAR10 data set using k Nearest Neighbor classifier

Classify the test images in the CIFAR10 data set using the clustering algorithm k Nearest Neighbor. We also perform k-fold cross validation to identify the best k hyper-parameter to produce the best accuracy on the data set.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


## Prerequisites

The following python packages are required for running the software.

[numpy](http://www.numpy.org/)

[matplotlib](https://matplotlib.org/)

[time](https://docs.python.org/2/library/time.html)


## Built With

[Jupyter-notebook](http://jupyter.org/) - A web-based notebook environment for interactive computing.

[Anaconda Python Cloud](https://anaconda.org/anaconda/python) - A free and open source distribution of the Python and R programming languages for data science and machine learning related applications.

## References

The primary source of programming concepts is derived from the course [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/).

The files in utils folder are obtained from:

[CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/)

[Tensorflow-Tutorials](https://github.com/Hvass-Labs/TensorFlow-Tutorials/)

## Conclusion

We can observe from the results that using k Nearest Neighbor classifier, we are able to acheive around 35% accuracy which is more than a simple probabilistic classifier having an accuracy of 10% (since number of classes are 10).
However, we must consider the time taken for the classification. 
Since training in kNN is only memorizing the data, the time to train would be very less.
During testing, the kNN algorithm performs poorly. In this case it takes ~65 seconds for classifying the CIFAR10 data set.