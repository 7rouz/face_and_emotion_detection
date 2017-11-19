# face_and_emotion_detection
A python project that uses openCV and python to detect faces and humain emotions.

## Setup
#### Global Settings
to install openCV 3 please follow this tutorial
https://www.learnopencv.com/install-opencv3-on-ubuntu/
[TODO]: re-write opencv3 installation instructions  

### Emotion Detection Setup
#### System Setup
For emotion detection part we will need dlib. Before pip installing it we need to install Boost. run thiq command to do so:

 sudo apt-get install libboost-all-dev

than go ahead and install dlib : pip install dlib

#### Landmarks Detector Data
you can find shapepredictor 68 face landmarks here:
[https://github.com/tzutalin/dlib-android/blob/master/data/shape_predictor_68_face_landmarks.dat](https://github.com/tzutalin/dlib-android/blob/master/data/shape_predictor_68_face_landmarks.dat)
