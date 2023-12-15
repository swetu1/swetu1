 **Neural Network**
 A neural network is a machine learning (ML) model designed to mimic the function and structure of the human brain.
 that uses interconnected nodes or neurons in a layered structure that resembles the human brain.

 <img width="678" alt="image" src="https://github.com/swetu1/swetu1/assets/149421367/768badb2-eff4-4e8f-990e-8da78e597778">


 **Activation functions**

 An Activation Function decides whether a neuron should be activated or not. This means that it will decide whether the neuron's input to the network is important or not in the process of prediction using simpler mathematical operations.


 https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6

 **Random intialisation of weight is important**

 
 https://towardsdatascience.com/random-initialization-for-neural-networks-a-thing-of-the-past-bfcdd806bf9e


 **forward and backward propagation**

 Forward propagation sequentially calculates and stores intermediate variables within the computational graph defined by the neural network. It proceeds from the input to the output layer. Backpropagation sequentially calculates and stores the gradients of intermediate variables and parameters within the neural network in the reversed order. When training deep learning models, forward propagation and backpropagation are interdependent, and training requires significantly more memory than prediction.

 https://jonaslalin.com/2021/12/10/feedforward-neural-networks-part-1/

 https://community.deeplearning.ai/t/feedforward-neural-networks-in-depth/98811


 **HyperParameter vs parameter**

 **Bias and Varience** 

 How to deal with high bias issue and High bias problem.

 **Train,dev and test data**

 how divding the dataset is helpful.

 **overfitting** use **Regularization**
 Types of Regularization 
 https://towardsdatascience.com/regularization-in-machine-learning-76441ddcf99a

 Difference between Ridge and Lasso regularization.

 **Dropout regularization**

 other way to reduce overfitting  is **Data Augmentation**

 **How Normalizing input  improve the training  rate of the model**

 The goal of normalization is to transform features to be on a similar scale which helps to stabilize the gradient descent step, allowing us to use larger learning rates or help models converge faster for a given learning rate. This improves the performance and training stability of the model.

 **Vanishing and exploding of the gradients**


 https://neptune.ai/blog/vanishing-and-exploding-gradients-debugging-monitoring-fixing#:~:text=this%20term%20gets%20extremely%20large,either%20vanishing%20or%20exploding%20gradients.
 
 During backpropagation, the calculation of (partial) derivatives/gradients in the weight update formula follows the Chain 
 Rule, where gradients in earlier layers are the multiplication of gradients of later layers:
 As the gradients frequently become SMALLER until they are close to zero, the new model weights (of the initial layers) will be virtually identical to the old weights without any updates. As a result, the gradient descent algorithm never converges to the optimal solution. This is known as the problem of vanishing gradients.

On the contrary, if the gradients get LARGER or even NaN as our backpropagation progresses, we would end up with exploding gradients having big weight updates, leading to the divergence of the gradient descent algorithm.

**varience in weight_intialisation for different activation functioN**

**problem we face during batch gradient descent,stochastic gradient descent**

**Advantage of using mini_batch stochastic gradient descent**

**Exponentially Weighted Average**--EWA basically is an important concept in deep learning and have been used in several optimisers to smoothen the noise of the data.

https://medium.com/mlearning-ai/exponentially-weighted-average-5eed00181a09


**Bias** correction

when the EWMA is initialized, there might be a bias because the initial estimate is based on fewer observations. To correct this bias, a correction term is introduced.


**Gradient descent with momentum ,RMSPROP ,Adam optimization algorithms**


Implementing **learning rate decay** and why it is important.


**Batch normalisation** and its importance 


**Softmax**



 
  

 


 
