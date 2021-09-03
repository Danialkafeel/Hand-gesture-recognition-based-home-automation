# Hand-gesture-recognition-based-home-automation

## Prerequisits and Installation
* Numpy 
```
pip3 install numpy
```
* Tensorflow
```
pip3 install tensorflow
```
* Matplotlib
```
pip3 install matplotlib
```
* OpenCV
```
pip3 install opencv-python
```

## Dataset
* Approximately 550 images of each type of gesture were taken.
* Then each of them were reduced to size 224x224x3 to train the model.
* For better results, background masking of each image was performed using OpenCV libraries.
* An example of masked images of the 5 types of gestures.
![Gestures](https://github.com/Danialkafeel/masked_gestures)


## CNN Model
* `my_model.py` is responsible for labelling the images of dataset and training the model, whose summary is shown below.
![Model summary](https://github.com/Danialkafeel/Hand-gesture-recognition-based-home-automation)

## Working
* Firstly, the background has to be captured, that will be needed for masking.
* Then the image of user is taken from webcam and background is removed.
* The masked image is feeded to the pre-trained model for prediction.
![Result](https://github.com/Danialkafeel/Result)