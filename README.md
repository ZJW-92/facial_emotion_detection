# ***Facial Emotion Detection***

_Facial emotion detection is the task of recognizing a person's emotional state among angry, disgust, fear, happy, neutral, sad and surprise using CNN deep learning technology._

## ***Data source***

_All the data is downloaded from [Kaggle FER-13](https://www.kaggle.com/datasets/msambare/fer2013?resource=download)._

## ***Technologies***
- _Keras: A high-level, deep learning API for implementing neural networks._
- _Tensorflow: An open-sourced end-to-end platform, a library for multiple machine learning tasks._ 
- _[OpenCV](https://docs.opencv.org/3.4/index.html): A library of Python bindings designed to solve computer vision problems._
- _[Haar Cascade](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html): An effective object detection method._
- _CNN: Convolutional neural network, a kind of network architecture for deep learning algorithms and is specifically used for image recognition and tasks that involve the processing of pixel data._ 

## ***Setup*** 
- 1. _Download dataset and put it in the directory_

- 2. _Open Pycharm terminal and run  `pip install -r requirements.txt`_

## ***Train the model***
_Run `python TrainEmotionDetection.py` and `emotion_model.json emotion_model.h5` will be gernerated after training._

## ***Test the model***
_Run `python TestEmotionDetection.py`_

## ***Visualization***

<a href="sample2.gif"><img src="gif/sample2.gif" width="33%" align="center"></a>
<a href="sample4.gif"><img src="gif/sample4.gif" width="32%" align="center"></a>
<a href="sample7.gif"><img src="gif/sample7.gif" width="32%" align="center"></a>

<a href="sample1.gif"><img src="gif/sample1.gif" width="26%" align="center"></a>
<a href="sample5.gif"><img src="gif/sample5.gif" width="35%" align="center"></a>
<a href="sample6.gif"><img src="gif/sample6.gif" width="35%" align="center"></a>
