# Computer_Vision

Code created to recognize images using Keras dataset and using a neural network recommended on textbook: Depp Learning with Python

Jupyter Notebook was used

The followinf libraries would need to be installed in order to run this code:

from keras import layers
from keras import models
import pandas as pd
from keras.datasets import mnist
from keras.utils import to_categorical
import os, shutil
from keras.datasets import cifar10
from keras.preprocessing.image import ImageDataGenerator
from tensorflow.keras.applications.resnet50 import ResNet50
from tensorflow.keras.preprocessing import image
from tensorflow.keras.applications.resnet50 import preprocess_input, decode_predictions
