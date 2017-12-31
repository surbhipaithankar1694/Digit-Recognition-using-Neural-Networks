# Digit-Recognition-using-Neural-Networks
Self Implemented multi-layered neural network for correctly recognizing handwritten images of MNSIT dataset

In this kaggle project, we have implemented neural networks to correctly identify digits from a dataset of tens of thousands of handwritten images.

**Data Set:**  

We downloaded the MNIST ("Modified National Institute of Standards and Technology) data from kaggle.com. Please refer the link below: https://www.kaggle.com/c/digit-recognizer
  
**Design Decisions:**  
  
We performed feature scaling using sklearn.  
Cross validation was performed.  
2 hidden layers with 50 hidden nodes have been implemented.  
Learning rate of 0.1 was set for initial iterations and later was reduced to 0.1.  
Sigmoid function is used as activation function.  

**Conclusion**  
We observe an accuracy of 91-94% over the test set, which looks to be pretty good. We can try using other activation functions like RELU and softmax in order to observe change in performance. As a step for further exploration, we can implement the project using Convolutional neural networks and deep learning.
