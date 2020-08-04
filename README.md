# CAM

Implementation of Learning Deep Features for Discriminative Localization([paper](https://arxiv.org/pdf/1512.04150.pdf))

![test1](https://drive.google.com/uc?export=view&id=1lHqpu8QE8PMa8BuIzwbiJQNOV_5HZ9xe) ![cam1](https://drive.google.com/uc?export=view&id=1uAmApd8PnsCBixmM6whvkBPmrVF5LGV7)  
![test2](https://drive.google.com/uc?export=view&id=1coE6aIaoZ-lgrqsOnHE9HIuRHj1dImwh) ![cam2](https://drive.google.com/uc?export=view&id=108Y6Ds_sZ7FkruX7qThMdt5RrrPo2VQf)  
![test3](https://drive.google.com/uc?export=view&id=1hOUnEG8qpj8-GafGajwie7PAUI6nyGbh) ![cam3](https://drive.google.com/uc?export=view&id=1V84PrTRS3EALuSb2_3stXYas-Den0alc)  
![test4](https://drive.google.com/uc?export=view&id=) ![cam4](https://drive.google.com/uc?export=view&id=1RzaGt4mPik8XDlg5JNsX7hkHlVYQ3YoJ)
![test5](https://drive.google.com/uc?export=view&id=) ![cam5](https://drive.google.com/uc?export=view&id=16EGjSSm3yOuTQFkG_F0zhI0pVhMkUbd_)
![test6](https://drive.google.com/uc?export=view&id=) ![cam6](https://drive.google.com/uc?export=view&id=)

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
