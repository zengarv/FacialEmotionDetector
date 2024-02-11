### About
This project is made for the induction task at the Google Developer Student Club (GDSC) at IIT Indore, under the AI/ML domain.

Task Description:
Create a ML model using computer visioon techniques which would predict the facial emotion of a human. The model should be able to satisfy the following aspects:
- Detection of emotion in a video recording or live video (preferred)
- Deteection fo a minimum of 5 emotions

About the dataset:
The dataset used to train the model is FER 2013
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.
The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

# The Models:

## Attempt 1: Using a hand-trained CNN Model
This is a standard CNN model which is used to classify the emotions
The trained model has an accuracy of 62.27%

It can be used for realtime face detection by running the realtimedetection.py script

Note: Several markdown cells have been added as notes, which were found by the author when reading through the documentation and researching about the components

## Attempt 2: Using Transfer Learning (Unfinished)
The MobileNetv2 was used as a base model and batch-learning was attempted to load data into the model. However, the training remains incomplete as it was hit with insufficient resources error. 


### Scope for further improvement:
- Implementing Batch Learning
- Using other/better pre-trained models like ResNetv3_large
- Increasing the epochs for which the model is trained on
- Implementing checkpoints and graphing model performance during training