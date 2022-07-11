# EMNIST-Tensorflow-Lite

<p align="center">
<img src="https://github.com/samuelesm/EMNIST-Tensorflow-Lite/blob/main/20220711_175214_1_1_1.gif">
</p>

## What is EMNIST?
EMNIST is the next step to MNIST, which is a dataset for training detection of handwritten digits 0-9. 

EMNIST stands for Extended MNIST, and as implied, it goes beyong the numerical digits and includes the English alphabet. 

The EMNIST Bymerge data is used to train this Tensorflow lite model. 

The Bymerge has varying numbers of training data per letter/number. Also, it combines the labelling for capital and lowercase letters for a handful of characters, because training to accurately make distinctions for all 52 capital uppercase and lowercase letters was difficult. 

From 62 total possible letters and digits, we are predicting 47 possible outcomes. 

## Technology and Methodology

This dataset and CNN method should create about a 90% accuracty rating. 

This is based on the Tensorflow Lite MNIST tutorial for Android devices. 

Tensorflow Lite is a lighter version of Tensorflow made friendly for mobile devices. 

By using clever techniques including compression with fewer bits, Tensorflow lite can easily be deployed on mobile devices and even Raspberry Pi's. 
