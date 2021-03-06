# Image Classification
Image classification is the task of assigning a label to an image (classifying an image as one thing or another). Here we start you off with a basic example:

 - **Dogs and Cats**:
  Trains a model to classify an image as a cat or a dog using 25,000 images
 (12,500 Cats and 12,500 Dogs).
 - **More Pets**:
 Trains a model to classify an image as a rabbit, mouse, hamster, fish, lizard, or snake.
 - **Poison Ivy**:
 Trains a model to classify a plant image as a type of poison ivy (or not).

## Tips and "Gotchas"
-  **Training Data**: In order for an image classifier to identify a particular category, it must have trained on
images labeled as such. For example, if a model was trained on dogs and cats, and it is shown a plant, it will
 identify that plant as either a dog or cat. To build an image classification model that identifies plants or other
 types of objects, you would need to retrain the model, using labeled images of the type you want.
-  **Model Runtime**: The out-of-the box model takes a long time to train on CPU. Definitely take advantage of Sagemaker Notebook Instances that serve up GPUs.
-  **Model Size**: In addition to the tips above, try using the `squeezenet_v1.1` model in the
`turicreate.image_classifier.create` function if you are worried about the size of the resulting model. This may also impact the classification accuracy of the model.

## Need Help?
Didn't find something you need? Confused by something? Need more guidance?

- [**Check out our platform documentation**](https://docs.skafos.ai)

Please contact us with questions or feedback! Here are two ways:

-  [**Signup for our Slack Channel**](https://join.slack.com/t/metismachine-skafos/shared_invite/enQtNTAxMzEwOTk2NzA5LThjMmMyY2JkNTkwNDQ1YjgyYjFiY2MyMjRkMzYyM2E4MjUxNTJmYmQyODVhZWM2MjQwMjE5ZGM1Y2YwN2M5ODI)
-  [**Find us on Reddit**](https://reddit.com/r/skafos)

Also checkout Turi Create's [**documentation**](https://apple.github.io/turicreate/docs/userguide/image_classifier/) on image classification basics.
