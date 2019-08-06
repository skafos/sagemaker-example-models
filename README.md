# Skafos Example Models on AWS Sagemaker
[<img src="https://docs.skafos.ai/assets/main-logo.png" width="40%">](https://skafos.ai)

A collection of AWS Sagemaker notebooks for training machine learning models with
[TuriCreate](https://github.com/apple/turicreate). At the end of each example notebook,
you will be able to upload a trained [CoreML](https://developer.apple.com/documentation/coreml)
model to [Skafos.ai](https://skafos.ai) where you can deliver over-the-air to your
iOS applications. In this repo, we provide two machine learning tasks to get you started.

## Syncing with Sagemaker
![Sagemaker Logo](/assets/sagemaker-logo.jpg)

1. Open the Amazon Sagemaker console: https://console.aws.amazon.com/sagemaker
2. Choose **Notebook Instances** on the left panel, and then click **Create Notebook Instance**
3. Fill in all required settings on the **Create Notebook Instance** page. Choose an instance type.
    - If you plan on using a GPU for compute, select one of the `ml.p2.xxxxxx` instances.
4. Open the **Git repositories** panel. In the Default repository section, click the dropdown and select
*"Clone a public Git repository to this notebook instance only"*.
5. Copy and paste this repo URL into the field that pops up.
6. Hit **Create Notebook Instance** at the bottom and wait for the instance to show *InService*.

*Amazon will launch an ML compute instance running the Jupyter Notebook App with a
set of pre-installed Anaconda libraries. This repository will be your working
directory when you open your new instance.*

7. Open up the Jupyter Notebook (or JupyterLab if you prefer that UI over the traditional one).
8. Navigate to one of the example models that interests you and select a kernel from the drop down.
    - If you plan on using a GPU for compute, select the `conda_amazonei_mxnet_p36` kernel

*Lastly, we recommend creating different instances for different models you plan on
working with. You don't want to mix up training environments/dependencies between
models.*

## Example Models
Each one of these example models links with an example app on the Skafos platform. You can easily deliver these models to iOS apps over-the-air by creating an account and heading over to https://dashboard.skafos.ai.

### Text Classification
Classify chunks of user text into different categories.
- [**Sentiment Classifier**](TextClassification/sentiment_classifier.ipynb)
- [**Spam or Ham**](TextClassification/spam_or_ham.ipynb)
- [**Topic Classifier**](TextClassification/topic_classifier.ipynb)

### Image Classification
Classify images into different categories.
- [**Dogs and Cats**](ImageClassification/dogs_and_cats.ipynb)
- [**More Pets**](ImageClassification/more_pets.ipynb)
- [**Poison Ivy**](ImageClassification/poison_ivy.ipynb)

### Object Detection
*Coming Soon*

## Need Help?
Didn't find something you need? Confused by something? Need more guidance?

- [**Check out our platform documentation**](https://docs.skafos.ai)

Please contact us with questions or feedback! Here are two ways:

-  [**Signup for our Slack Channel**](https://join.slack.com/t/metismachine-skafos/shared_invite/enQtNTAxMzEwOTk2NzA5LThjMmMyY2JkNTkwNDQ1YjgyYjFiY2MyMjRkMzYyM2E4MjUxNTJmYmQyODVhZWM2MjQwMjE5ZGM1Y2YwN2M5ODI)
-  [**Find us on Reddit**](https://reddit.com/r/skafos)

We will continue to update this repository with updated/new example models to get you started. Stay tuned.
