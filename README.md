# Digit_Recognition

###### Final Project for class:
Basics of Machine Learning
###### Instructor
Dr. Paweł Morkisz

## Description:
The program is trained using MNIST dataset to predict handwritten digits. There is a GUI for users to draw their own digits using a mouse. The program can predict digits that users draw using their mouse. It can also be used to predict digits in images if they are provided as an input. 

  
## Structure:
Digit Recognition:<br/>
 -evaluateModel.py  ->To evaluate model.h5.<br/>
 -model.h5          ->Model created in saveModel.py<br/>
 -saveModel.py      ->Preprocess the data and creates te model<br/>
 -predictGUI.py     ->GUI to predict handwritten digits<br/>

Report.pdf:          ->Pdf of the report<br/>


## Usage:
  To use the application, simply run predictGUI.py.
  
## Language, Version, IDE
  Python 3.8, Pycharm Community Edition 2020.2.3

## Requirements:
python -m pip install keras tensorflow Pillow opencv-python

You don't have to run saveModel.py to create a model because model.h5 is already included in the repository. If you wish to create a new model on you computer, you can run saveModel.py and a new model will be created.

## Example Image
![digit](https://user-images.githubusercontent.com/65031185/176141710-a2151d22-81ec-4e68-b180-e030bb0b2016.png)



