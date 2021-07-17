# Object_Detector

## Obejctive:
Main motive is train the neural network so it can detect thumbsup, thumbsdown, thankyou and live long with the help of libraries such as tensorflow, keras, opencv and etc. It     can detect live images with the help of webcam and also by uploading a picture from the system.
  
-------------------------------------------------------------------------------------------------------------------------------------
### Made on jupyter notebook.
### Python 3.9 was used.

Install any missing dependencies using  [pip](https://pip.pypa.io/en/stable/installing/)

-------------------------------------------------------------------------------------------------------------------------------------

## Setup:
###  [Image Collection](https://github.com/Garvit-01/Object_Detector/blob/main/1.%20Image%20Collection.ipynb) File:

  - After setting up the folders you will see like this in the directory where you started your project:
  - Now capture the images a small pop-up will appear in the taskbar of of the windows.
  - For image labelling install the required library and clone the repository given in the program.

### [Training and Detection](https://github.com/Garvit-01/Object_Detector/blob/main/2.%20Training%20and%20Detection.ipynb) File:

- Run the first few steps
- When installing the model you can choose any model from the following link: 
  [Models TensorFlow](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md)
- However, in this project I have used **SSD MobileNet V2 FPNLite 320x320**
- Then install the tensorflow object detection model it will take sometime.
- Run the verification step and after running should state "OK".

- Before going to the next step install the CUDA and cuDNN you can check compatible version here [Tensorflow](https://www.tensorflow.org/install/source_windows) only if your system has GPU otherwise, you can move to next steps.
- For the next 2 commands you can do on the juptyer notebook as well as but command prompt or anaconda prompt is better as it will give some visual representation. The output will be the same if you run anywhere. 
- Run all the commands after that; on step 6 during the training of the model run the `print(command)` and copy its output in the command prompt(location should be the directory   where the project is save) after that paste the paste it in the command prompt and wait while it runs (it might take some time depending upon the gpu and cpu of your system)
- After it is done during the Evaluate of the model step do the same thing again as done in the above  step.

- Traing of the model is done.
- Now you can detect an image by giving the location from your system or by webcam using live images



