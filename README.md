# Handwriting-recognition-using-Convolutional-neural-network-using-Keras
Handwriting recognition using Convolutional neural network ad experiment against proving that 
CNN is better than deep neural networks in better classifying images with its improvised convolution and pooling functions using Keras on MNIST data set.

In my previous attempt to classify digits using **Deep neural networks** I obtained an **accuracy of ~ 93%** not so good **on MNIST data set**,
But using **Convolution neural network (CNN)** I obtained a whooping **accuracy of ~ 99%** which proves that **CNN  is the best 
alternative to DNN for classifying images.**

I have attached the images showing the **plots of training error , and accuracy of both Deep neural network classification and Convolutional 
neural network classification**

## Plot of training error in DNN
![Training error DNN](https://github.com/Sahana-M/Images/blob/master/dtr.png)

## Plot of training error in CNN
![Training error CNN](https://github.com/Sahana-M/Images/blob/master/ctr.png)

### *We can see here from the above image that the training error is comparitively less in CNN , though our model in DNN is trying to over fit the data as our validation set is performing better than our training set there. Epochs = 10*




| Model         | training set loss         | validation set loss  |
| ------------- |:-------------:| -----:|
| DNN      | ~0.22 | ~0.20 |
| CNN      | ~0.05      |   ~0.03 |



## Plot of accuracy in DNN
![Training error DNN](https://github.com/Sahana-M/Images/blob/master/dts.png)

## Plot of accuracy in CNN
![Training error CNN](https://github.com/Sahana-M/Images/blob/master/cts.png)

### *We can see here from the above image that the accuarcy of CNN is outstanding compared to DNN*




| Model         | training accuracy         | validation accuracy  |
| ------------- |:-------------:| -----:|
| DNN      | ~93% | ~94% |
| CNN      | ~98.7%      |   ~99% |
