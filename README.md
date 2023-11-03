# dog-image-classification
## Comparison of Pre-Trained Deep Neural Networks for Dog Breed Classification

### Code Overview

### Background
The image classification problem is one of the most popular yet challenging applications of supervised learning in the machine learning field today. New advances in computing and Deep Convolutional Neural Networks (DCNN)3,4 have allowed state of the art accuracy when evaluating high resolution images. These networks consist of many layers so training these DCNN from scratch has been a challenge since it requires an incredibly large amount of computing power. Transfer learning has recently gained its popularity as it allowed users to utilized pre-trained weights of the trained network in their own prediction tasks. In this paper, we evaluated four DCNN model using transfer learning methods to determine the best model in dog breed classification.

### Methods
We have adopted four DCNN models, namely, GoogleNet, ResNet-18, AlexNet, and SqueezeNet-1.0 on Stanford Dog Breed dataset using two different transfer learning methods, feature extraction (FE) and finetuning (FT). We have compared the performances and training time of each model using each method under the same circumstances for fair comparison.
