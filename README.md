# CAM

Implementation of Learning Deep Features for Discriminative Localization([paper](https://arxiv.org/pdf/1512.04150.pdf))

![test1](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/bird1.jpg?raw=true) ![cam1](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/bird5.png?raw=true)  
![test2](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/horse1.jpg?raw=true) ![cam2](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/horse5-1.png?raw=true)  
![test3](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/ship1.jpeg?raw=true) ![cam3](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/ship40.png?raw=true)  
![test4](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/dog1.jpg?raw=true) ![cam4](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/dog5-1.png?raw=true)  
![test5](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/dog2.jpg?raw=true) ![cam5](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/dog5-2.png?raw=true)  
![test6](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/horse2.jpg?raw=true) ![cam6](https://github.com/froggydisk/froggydisk.github.io/blob/master/assets/img/horse5-2.png?raw=true)

This implementation is a simplified version of original project. The network was made easy to understand.


## Usage
This code implements only the main functions of the original project and visually checks their results.     
For more detail, please refer to the [original project.](https://github.com/metalbubble/CAM)


## Environments
- [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb?hl=ja)


## Dataset
- MNIST
- CIFAR10

## Settings
```python
dataset = 'CIFAR10'
img_size = 32
batch_size = 128
epoch = 5
learning_rate = 0.001
```

## Reference

This repository is influenced by [zhoubolei](https://github.com/metalbubble/CAM) and [KangBK0120](https://github.com/KangBK0120/CAM)
