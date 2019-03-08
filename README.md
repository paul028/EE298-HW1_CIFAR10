# EE298-HW1_CIFAR10
HW #1 in EE 298 Z - Deep Learning

Build a classifier on CIFAR10 dataset using
<br>1. 3-layer MLP
<br>2. 3-layer CNN
<br>3. The last layer is Dense
<br>4. Up to you to determine the hyperparameters (ie kernel size, # hidden units, # of filters, learning rate, optimizer, etc)
<br>5. Show your solution using Jupyter notebook
<br>6. Implement using Keras or Pytorch
<br>7. Compare performance of both networks (best MLP vs best CNN)

<br> **Final Result: **
<br>
<br> Cifar10 classifier on 3-Layer MLP:
<br> Link to MLP [Here](https://github.com/paul028/EE298-HW1_CIFAR10/blob/master/CIFAR10_MLP_v3.ipynb)
<br>
![alt text](https://github.com/paul028/EE298-HW1_CIFAR10/blob/master/MLP.png)
<br>The 3 Layer MLP attains a Maximum Training Accuracy of 61.57%  and Testing Accuracy of 57.32%
<br>
<br> Cifar10 classifier on 3-Layer CNN:
<br> Link to CNN Model [Here](https://github.com/paul028/EE298-HW1_CIFAR10/blob/master/CIFAR10_3L_CNN_TPUv9.ipynb).
<br>
![alt text](https://github.com/paul028/EE298-HW1_CIFAR10/blob/master/CNN.png)
<br>The 3 Layer CNN attains a Maximum Training Accuracy of 89.44%  and Testing Accuracy of 87.45%
<br>

<br> In terms of Performance, CNN performs way better in doing image related task as this model takes into account the pixel and dimensional information of the image. MLP on the other hand is still capable of performing image classification. However, the model is prone to underfitting. On the constraint of having a maximum of 3 hidden layers, CNN performs an acceptable accuracy of 89% on the training set and 87% on the testing set. MLP manage to reach 61% training accuracy and 57.32% testing accuracy, it's accuracy can still pushed up to 70%, but the model starts to underfit when attempted in this activity. Overall, CNN is the better model in doing image classification when compared head to head with MLP, the only downside of CNN is that it needs a lot of computational power unlike MLP. 

<br> Other trial models created can be found on this [repository](https://github.com/paul028/myJupyterNotebook).
