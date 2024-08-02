# building-scratch-neural-nets
Implementation of Simple Regression models, Deep Neural Networks and Convolutional neural nets. <br>


## Notebook-1: Scratch Linear Models and Basic Neural Networks: <br>
> Dataset used: Titanic Survival dataset <br>
> 1. Preprocessed data, by imputing missing values, added `log_Fare` feature for a normal distribution of data etc. <br>
> 2. Created a simple regression model from scratch, slowly worked the way up by implementing a loss function and then adding gradient descent, converting it into a basic neural net component. Then, ran a training loop for 45 epochs with 0.4 as base learning rate to reduce loss from `0.54` to `0.42`.<br>
> 3. Implemented matrix multiplication as the base of operation to boost up efficiency, then implemented a DNN.

---
## Notebook-2: Random Forest:<br>
> Dataset used: Titanic Survival Dataset. <br>
> 1. Used the same preprocessing steps as in Notebook-1. <br>
> 2. Created basic dumb models to demonstrate how decision trees work at the atomic level. <br>
> 3. Implemented DecisionTrees and RandomForests on the dataset to achieve <br>
>> MAE for `DecisionTree` = 0.1929<br>
>> MAE for `RandomForest` = 0.1641.
---

## Notebook-3: Convolutional Neural Network from scratch: <br>
> Dataset used: MNIST handwritten numbers dataset. <br>
> 1. Implemented the basic convolution operation from scratch, creating kernels and strides from atomic level. <br>
> 2. Visualized the activations and learning of convolutional layers, then added a BatchNorm layer to demonstrate why Batch Normalization is an essential step.
> 3. Leveraged 1-cycle training method to achieve an overall accuracy of `96.5%`
> 4. Final accuracy achieved: 99.3%
