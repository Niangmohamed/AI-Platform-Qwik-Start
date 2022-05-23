# AI Platform Qwik Start

In this project, you will learn how to train the TensorFlow 2.x model, both locally and on AI Platform. You will then discover how to deploy it on AI Platform to make predictions. You will train the model to predict an individual's income category using the U.S. Census income dataset.

This project gives you the opportunity to experience the entire training and prediction process on AI Platform. You will use a census dataset to perform the following tasks:

* Create a TensorFlow 2.x training application and validate it locally
* Run your training task on a single compute node instance in the cloud
* Deploy a model to support the prediction
* Request a prediction online and view the answer

What you will create...

The example presented here creates a classification model capable of predicting the income category from a census dataset (conducted in the United States). The two income categories, also called "labels", are as follows:

* \>50K: incomes above $50,000
* <=50K: income less than or equal to $50,000

The example defines the model using the Keras Sequential API. It also defines the data transformations that are specifically relevant to the census dataset, before assigning these (potentially) transformed features to the DNN or linear part of the model.
