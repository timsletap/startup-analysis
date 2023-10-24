# Prediction of Startup Success Using Machine Learning

![startup image](https://static.vecteezy.com/system/resources/previews/002/142/408/non_2x/concept-of-a-startup-community-teamwork-discussion-of-issues-generation-of-ideas-creativity-young-men-and-women-work-together-flat-cartoon-illustration-vector.jpg)

## Introduction
Hello! I'm Smit Patel, I completed a study on the "Prediction of Startup Success Using Machine Learning." Through this research, I utilized advanced machine learning algorithms and achieved significant prediction accuracies, underscoring the power of technology in business decision-making. 

## Focus
 In the dynamic world of startups, predicting success remains a challenge. As an investor, this makes it difficult to deploy capital to a startup with a high probability of success. Leveraging machine learning has the potential to offer insights into factors that contribute to startup success and to provide a predictive model that can help investors. We used Neural Network and Gradient Boosting classification algorithms to predict startup success.  We were able to achieve accuracy of 96% for Neural Network and 100% for predicting startup success through Gradient Boosting classification. We concluded that investors should include machine learning based prediction models in their analysis along with other methods they already use today to make investment decisions.


## MLPClassifier
A multi-layer Perceptron classifier which optimizes the log-loss function using the backpropagation algorithm. It has hidden layers, and each layer has activation functions which introduce non-linearity.  The architecture can be deep, allowing for high model complexity. Depending on depth and data size, training can be slow for large networks. It requires preprocessing to handle missing data via imputation. It is considered a black-box model and doesn't offer great interpretability.  Our model encompassed an architectural design defined by an input layer of 25 nodes, a subsequent hidden layer of 50 nodes, and a final output layer. The ReLU activation function was employed for the input and hidden layers, while the Sigmoid function was reserved for the output layer. The model's training was orchestrated with the Adam optimizer, using the binary cross-entropy loss function. Spanning 50 epochs, with a batch size of 10 and a validation split of 20%, the training process fine-tuned the model's weights

## GradientBoostingClassifier

An ensemble method that builds an additive model in a forward stage-wise fashion. It constructs regression trees and fits them to the negative gradient of the loss function. It sequentially builds shallow trees and each tree tries to correct the errors of its predecessor. Depending on data size, training can be time-consuming since trees are built sequentially. It requires preprocessing to handle missing data via imputation. This specific model requires imputation but there are other boosting variants that can handle missing data natively. It offers a level of interpretability by visualizing individual trees, feature importance, and plots. Our model was tailored with hyperparameters including a learning rate of 0.1 and total estimators of 100.

## Feedback
Let me know if you have any further questions or feedback. Here is a link to my paper [paper](https://github.com/timsletap/startup-analysis/blob/main/PredictionOfStartupSuccessUsingML.pdf)
