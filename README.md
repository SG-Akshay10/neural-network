# neural-network
Implementing Black and White Box Neural Networks for the same dataset and interpreting its results.

# White vs Black Box Neural Networks

* Black-box models have observable input-output relationships but lack clarity about their inner workings. This is typical of deep-learning and boosted/random forest models, which model extremely complex situations with high nonlinearity and input interactions.

* White-box models, on the other hand, like linear regressions and decision trees, have behaviour, features, and relationships between influencing variables and output predictions, but are often not as performant as black-box models, i.e., lower accuracy but higher explainability.

# About the Dataset

The dataset consists of age,bmi,glucose level,pregnancies,blood presssure,skin thickness,insulin and their diabetic result.

It consists of 8 attribute , where 1 is the target feature which needs to be predicted.

# Activation Function Used:

What is a Activation function?

* Activation function basically decides if the neuron needs to be activated or not. It derives output from a given set of input layers or nodes.

* Further Reading:Activation Functions

* I got to use Sigmoid as the activation function cause it is easier to calculate partial differential with respect to sigmoid function because of the presence of an exponential.

# Comparion of Black-Box and White Box results:
I choose accuracy as the metric on which both the models will be evaluated.While there are various others metrics on the basis of which the efficiency fo the model can be found it , Accuracy is the most simple and easy to understand metric. Hence it was chosen

Black Box : 73.16

White Box : 66.92

The black box models moderately performs better than white box model due to its more efficient and modular code.
