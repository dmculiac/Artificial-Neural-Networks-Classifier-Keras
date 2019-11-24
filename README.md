# Artificial-Neural-Networks-Classifier

In this project we're dealing with a binary classification problem. We already have baseline scores having run classifiers from the sklearn suite on the dataset. What we're trying to do here is to see if we can do better than the scores resulting from the out of the box Python ML algorithms (Decision Tree, Random Forest, NeuralNet, AdaBoost, XGBoost).
The metric of interest for us is the number of false negatives. We're trying to keep that as low as possible. So this will become an exercise in answering the question what is an appropriate metric from a business case pov? We want to optimize our model to the business problem at hand and not to some out of the box, academic metrics.
The second issue of interest here is how flexible the artificial neural network construct is in adapting to the problem at hand compared to the competing out of the box Python ML algorithms (Decision Tree, Random Forest, NeuralNet, AdaBoost, XGBoost), being both business case accurate (not in the accuracy metrics sense, we're not solving for accuracy) and in the generalizing power (that of not being overfit on the training set and poor on unseen data).


## Business Problem
The Customer Engagement group uses leads provided by Sales to engage with prospective clients. The issue is the conversion rate is low. The business problem is one of cost control: how to keep adequate staffing levels in the customer engagement group? Low conversion rate translates to low productivity. To increase the productivity we need to increase the ratio of customers to staff. Being able to filter out the false prospective customers will be the first step on that road. This is the classification problem we're tackling in this project
