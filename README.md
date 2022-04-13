# Image Recognition movie character and comics to Figure collection classification

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)[![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Goal

With help of image processing algoritms and deep learning techniques I try compute images of Figure collections, looking at movies characters and comics images (inputs).

In this notebook you can find the model: [Image recognition](https://github.com/carlosjimenez88M/batman_peacemaker_recognition/blob/master/Object_recognition.ipynb)

## Steps Considered

* Batman Case : 
  * Differents actors, 
  * Differents Batman version,
  * Mix between classic and moderm comics

* Peacemaker Case : 
  *  Only actor, 
  *  Only Classic Comics

* Small Data

* Tensorflow version = 2.7

![](https://github.com/carlosjimenez88M/batman_peacemaker_recognition/blob/master/train/batman/batman02.jpeg?raw=true)
![](https://github.com/carlosjimenez88M/batman_peacemaker_recognition/blob/master/train/peacemaker/peacemaker08.jpeg?raw=true)

## Model Performance 

I use three differents convolutional layers to understand pixels connections at differents images and using pooling layers to create subsamples in inputs images in order to reduce the computational memory and limiting risk of overfitting


![](https://github.com/carlosjimenez88M/batman_peacemaker_recognition/blob/master/train/performance.png?raw=true)


