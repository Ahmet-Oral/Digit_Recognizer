# Digit_Recognition
Basics of Machine Learning Final Project
# Description:
This application contains a program that trained using MNIST dataset to predict handwritten digits. There is a GUI for users to draw their own digits using mouse. Program can predict user drawn digits.

  
# Structure:
Digit Recognition:<br/>
 -evaluateModel.py  ->To evaluate model.h5.<br/>
 -model.h5          ->Model created in saveModel.py<br/>
 -saveModel.py      ->Preprocess the data and creates te model<br/>
 -predictGUI.py     ->GUI to predict handwritten digits<br/>

Report.pdf:          ->Pdf of the report<br/>


# Usage:
  To use application, simply run predictGUI.py.
  
# Language, Version, IDE
  Python 3.8, Pycharm Community Edition 2020.2.3

# Requirements:
python -m pip install keras tensorflow Pillow opencv-python

You don't have to run saveModel.py to create a model because model.h5 is already included in repository. Of course if you wish to create the model in you computer, you can run saveModel.py and a new model will be created.

