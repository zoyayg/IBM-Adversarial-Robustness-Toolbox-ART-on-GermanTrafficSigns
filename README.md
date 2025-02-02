# IBM-Adversarial-Robustness-Toolbox-ART-on-GermanTrafficSigns

## 1- Abstract

Adversarial attacks pose real threats against Deep Neural Networks (DNN) specially the ones working with visual recognition tasks. An attacker can add carefully crafted noise to the input images that are unrecognizable by human eye but make the model totally misclassify it as something else. An example can be some added noise on a Stop Sign that can make the model misclassify it as an Ahead Only sign which can be very dangerous if the system using this model is a self-driving car! Therefore, it is very important to have tools to protect our models against such attacks. IBM has developed a library that is very powerful in detecting adversarial attacks as well as providing means to protect your model against them.


## 2- About the Project
In this project I trained a DNN (modified DenseNet structure) on GermanTrafficSign dataset then used it to show different capabilities of IBM's Adversarial Robustness Toolbox (ART). 

### This repository includes:
#### 2.1- Two main notebooks in "Notebooks" folder
1- one that contains the training code and then uses ART. 
2- one that loads a TensorFlow trained model then use it to work with ART.

#### 2.2- Miscellaneous and test images in "extra" folder

#### 2.3- For dataset info please refer to refrences section



## 3- About ART
Adversarial Robustness Toolbox is an open source library developed by IBM Research in Ireland. It is written in Python and supports most popular Deep Learning frameworks like TensorFlow, Keras, PyTorch, etc.
Link to IBM ART Library Github: https://github.com/IBM/adversarial-robustness-toolbox


## 4- Dataset
Download and use German Traffic Sign dataset http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset


## References

[1] J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel. The German Traffic Sign Recognition Benchmark: A multi-class classification competition. In Proceedings of the IEEE International Joint Conference on Neural Networks, pages 1453–1460. 2011. 

[2] The code to define and train the model was used from the code in https://github.com/hengck23-udacity/udacity-driverless-car-nd-p2

[3] "Densely Connected Convolutional Networks" - Gao Huang, Zhuang Liu, Kilian Q. Weinberger, Laurens van der Maaten, Arxiv 2016
