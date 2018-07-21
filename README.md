# Car_Image_Classifier_Final

For in-depth explanation of the code, please see the file "Readme.docx" in the folder “image_classifier_main.zip”

Objective: 
This code uses machine learning tools such as convolutional neural network, random forest and an ensemble model in order to classifiy images that contain cars from the ones that don’t contain cars.
Requirements prior to running the code:
1. You will need to have python version 3.6.3 or higher on your computer. This code may run on previous version of python but I have not checked that.
2. You will need to install these python packages before running the code: flask, Flask-Uploads, Redis, opencv-python, numpy, pandas, scipy, matplotlib, pathlib, pillow, tensorflow, sklearn, tflearn
3. You can use pip install in order to install these packages in your computer.
How to run the code:
1. Download the folder “image_classifier_main.zip” and unzip in your computer’s local drive. 
2. Look out for the code named “app.py” and run it using either via command line or by some other python IDE software.

How to run the code as a docker image?
1. Install respective docker tool on your computer depending on your operating system
2. docker run -t -p 4550:5000  ranasac/car_image_classifier_code:rev1



