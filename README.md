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

## DATASET
* Approximately 550 images of each type of gesture were taken.
* Then each of them were reduced to size 224x224x3 to train the model.
* For better results, background masking of each image was performed using OpenCV libraries.

## CNN MODEL
* `my_model.py` is responsible for labelling the images of dataset and training the model, whose summary is shown below.
