# Image-Classification-with-Convulational-Neural-Network-CNN-

Training Dataset : 5000 images of size 300X300X3
Test Dataset : 1000 images of size 300X300X3

10 CIFAR classes : ['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']

MODEL Training: 
1. Convolutional 2D Layer
2. LeakyRelu Activation: to solve the problem of dying neurons
3. MaxPooling of size 2X2: downsampling the image
4. Dropout
5. Flatten
6. Dense
7. Dropout
8. Dense
Model Actionvation using SOFTMAX ACTIVATION

Test Accuracy : 81%
