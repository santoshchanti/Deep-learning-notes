# Deep Learning Specialization | [Coursera](https://www.coursera.org/specializations/deep-learning)
Path to learning DL | Day-1: 18 October 2020

## About this Specialization
You will learn about Convolutional networks, RNNs, LSTM, Adam, Dropout, BatchNorm, Xavier/He initialization, and more. You will work on case studies from healthcare, autonomous driving, sign language reading, music generation, and natural language processing. You will master not only the theory, but also see how it is applied in industry. You will practice all these ideas in Python and in TensorFlow. 

## Agenda
- Course 1 *Neural Networks and Deep Learning* - just a start, architecture of NN
- Course 2 *Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization* - TensorFlow, optomization algos
- Course 3 *Structuring Machine Learning Projects* - how to build a successful machine learning projects, and how to prioritize the problem
- Course 4 *Convolutional Neural Networks* - all about CNN
- Course 5 *Natural Language Processing: Building sequence models* - Recurrent Neural Networks (RNNs), natural language processing (NLP)

Source: [coursera.org](https://www.coursera.org/specializations/deep-learning)

# Course 1 - Neural Networks and Deep Learning
- Understand the major technology trends driving Deep Learning
- Be able to build, train and apply fully connected deep neural networks 
- Know how to implement efficient (vectorized) neural networks 
- Understand the key parameters in a neural network's architecture 

## C1 Week 1
### Introduction to Deep Learning
- Machine Learning vs Deep Learning
<br><img src="media/MLvsDL.png" width=300>

- **What is neural network?** [(Lecture notes)](https://github.com/Rustam-Z/deep-learning/blob/main/Course%201%20Neural%20Networks%20and%20Deep%20Learning/01_What_is_Neural_Network.pdf) NN is a powerful learning algorithm inspired by how the brain works. 
<br><img src="media/what-is-nn.png" width=300>

- **Supervised Learning for Neural Networks** [(Lecture notes)](https://github.com/Rustam-Z/deep-learning/blob/mainCourse%201%20Neural%20Networks%20and%20Deep%20Learning/02_Supervised_Learning_for_Neural_Network.pdf)

  - Supervised - regression and classification problems. Regression problem - predict results within a continuous output, trying to map input variables to some continuous function. Classification problem, we are instead trying to predict results in a discrete output, we are trying to map input variables into discrete categories.  

  - Application of supervised learning
    <br><img src="media/supervised-learning.png" width=300>

  - Types of neural networks: **Convolution Neural Network (CNN)** used often for image application and **Recurrent Neural Network (RNN)** used for one-dimensional sequence data such as translating English to Chinses. As for the autonomous driving, it is a hybrid neural network architecture.

  - Structured vs unstructured data
    <br><img src="media/structured-and-unstructured-data.png" width=300>

- **Why is Deep Learning taking off?** [(Lecture notes)](https://github.com/Rustam-Z/deep-learning/blob/main/Course%201%20Neural%20Networks%20and%20Deep%20Learning/03_Why_is_Deep_Learning_Taking_Off.pdf) 
Large amount of data! We see that traditional algorithms reach to a threshold on performance. However, NN always works better with more data. So you can get better performance as long as you collecting more and more data, without changing the algorithm itself.
<br><img src="media/dl-taking-off.jpeg" width=300>


## C1 Week 2
- LogReg for NN, making prediction, derivative computation, and gradient descent
- Compute LogReg using back prop
- Python, NumPy, implement vectorization

### Logistic Regression as a Neural Network
- **Binary Classification** [(Lecture notes)](https://github.com/Rustam-Z/deep-learning/blob/main/Course%201%20Neural%20Networks%20and%20Deep%20Learning/04_Binary_Classification.pdf) 
- **Logistic Regression** Predict whether 0 or 1, [(Lecture notes)](https://github.com/Rustam-Z/deep-learning/blob/main/Course%201%20Neural%20Networks%20and%20Deep%20Learning/05_Logistic_Regression.pdf), [YouTube Video Part 1](https://www.youtube.com/watch?v=L_xBe7MbPwk), [Part 2](https://www.youtube.com/watch?v=uFfsSgQgerw)

  