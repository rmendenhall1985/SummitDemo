# SummitDemo

## Prerequisites before starting the workshop

### Redeem Your Github Education Pack
https://docs.microsoft.com/en-us/learn/roles/student

[![Github Student Pack](https://github.com/rmendenhall1985/SummitDemo/blob/main/Images/GithubStudentPack.PNG)](https://signup.azure.com/studentverification?offerType=1&correlationId=04A696E101FA66F83EE999D0002667D9)



### Sign up for Azure for Students

[![Signup for Azure](https://github.com/rmendenhall1985/SummitDemo/blob/main/Images/SignUpForAzure.PNG?raw=true)](https://signup.azure.com/studentverification?offerType=1&correlationId=04A696E101FA66F83EE999D0002667D9)





## Azure Image Classification using MML Spark

[![Launch Microsoft Learn](https://github.com/rmendenhall1985/SummitDemo/blob/main/Images/LaunchMSLearn.PNG)](https://docs.microsoft.com/en-us/learn/modules/create-windows-virtual-machine-in-azure/1-introduction)

[![Deploy to Azure](https://github.com/rmendenhall1985/SummitDemo/blob/main/Images/DeploytoAzure.PNG)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-storage-account-create%2Fazuredeploy.json)





[Image classification](https://en.wikipedia.org/wiki/Contextual_image_classification) is a common application for [machine learning](https://en.wikipedia.org/wiki/Machine_learning). The classic use case involves training a computer to recognize cat images — or, if you're fan of the TV show [Silicon Valley](https://www.hbo.com/silicon-valley), hot-dog images. In real life, image classification serves a variety of purposes ranging from analyzing images for adult content to identifying defective parts produced by manufacturing processes. It was recently used to [help search-and-rescue drones](https://blogs.technet.microsoft.com/canitpro/2017/05/10/teaching-drones-to-aid-search-and-rescue-efforts-via-cognitive-services/) identify objects such as boats and life vests in large bodies of water and recognize potential emergency situations in order to notify a rescue squad without waiting for human intervention.

Image-classification models are typically built around [convolutional neural networks](https://en.wikipedia.org/wiki/Convolutional_neural_network) that "learn" from the thousands (or tens or hundreds of thousands) of labeled images they are trained with. Such networks are frequently built using [Apache Spark](https://spark.apache.org/) and [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html). The [Microsoft Machine Learning Library for Apache Spark](https://github.com/Azure/mmlspark), also known as MMLSpark, is an open-source library that simplifies machine learning in Spark by abstracting many of Spark ML's lower-level APIs and providing near-seamless integration between Spark ML pipelines and popular Deep Neural Network (DNN) libraries such as the [Microsoft Cognitive Toolkit](https://www.microsoft.com/en-us/research/product/cognitive-toolkit/), also known as the Computational Network Toolkit, or simply CNTK.

In this lab, the first of four in a series, you will use the Azure CLI to create an Azure SQL database in the cloud. Then you will use [Azure Machine Learning Workbench](https://docs.microsoft.com/en-us/azure/machine-learning/preview/quickstart-installation) to run a Python script that uses the [Bing Image Search API](https://azure.microsoft.com/services/cognitive-services/bing-image-search-api/) to search the Web for images of paintings by famous artists and write the results to the Azure SQL database. In [Lab 2](../2%20-%20Process), you will clean the data, and in [Lab 3](../3%20-%20Predict), you will use MMLSpark to build an image-classification model that can identify the artists of famous paintings. Finally, in [Lab 4](../4%20-%20Visualize), you will operationalize the model and build an app that uses it.
