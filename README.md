# Data-Mining-in-Image-Data
## Problem we will solve?

The MNIST data set consist of the handwritten digits that is commonly used as a benchmark dataset for training and testing machine learning algorithms. MNIST stands for Modified National Institute of Standards and Technology database, and it contains a training set of 60,000 images and a test set of 10,000 images.

So looking at the dataset the only problem I can see is mkaing a system that recognizes the handwritten digits. 
The goal is to train the different machine learning models and get the classification of the image more accurately which can be used in the real world and important as it can be used to recognize the handwritten charaters in the application forms where human have different handwriting but this model can identify, also can be used in the banks to recognize checks and so on where human written charaters can be identified by machine.

## Exploring the data
![Screenshot 2024-06-19 at 10 04 30 PM](https://github.com/hbhavane/Data-Mining-in-Image-Data/assets/78750775/d3eca2ed-26be-4f19-a474-fa01ce225f9f)

![Screenshot 2024-06-19 at 10 02 41 PM](https://github.com/hbhavane/Data-Mining-in-Image-Data/assets/78750775/c677446d-472c-4712-b7a6-059cf024c7bf)


## Solution Aprroach
The problem I planned to solve using the MNIST dataset is to classify handwritten digits. My goal is to use deep learning models to achieve high accuracy on this task.
I will be comparing the performance of three different models: a simple feedforward neural network, a convolutional neural network (CNN), and a recurrent neural network (RNN).
The feedforward neural network will consist of two dense layers with ReLU activation, followed by a softmax output layer. The CNN will consist of two convolutional layers with ReLU activation, followed by two dense layers with ReLU activation and a softmax output layer. The RNN will consist of a single LSTM layer followed by a dense layer and a softmax output layer.
I will train each model on the MNIST dataset and evaluate their performance using the accuracy metric. I will also compare their training and testing times to evaluate their efficiency.
By comparing the results of these three models, I hope to gain insights into the strengths and weaknesses of each approach for solving the problem of classifying handwritten digits.

## Results: summarize

![image](https://github.com/hbhavane/Data-Mining-in-Image-Data/assets/78750775/d2a55522-4a24-430b-a64b-f7c025e31926)

We can see from the tables and the bar charts of the comparison between the three models accuracy and time taken to perform traning and testing, all three models achieved high accuracy on the MNIST dataset. 
The CNN performed the best with an accuracy of 0.9912 though it even took the highest time of around 5.8 minutes to train and test the model , followed by the FFNN with an accuracy of 0.9790 which took the least time to train test the data of around 20 seconds, and the RNN with an accuracy of 0.9733 taking middle averahe time of around 3.3 minutes than other two models . 
Overall, these results demonstrate the effectiveness of deep learning models for image classification tasks like MNIST
