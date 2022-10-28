# DOOFSTROM

* Reads your hand signs and translates them to English words and voice output using Tensorflow object detection.<br/>
* The dataset is made manually by running the **Image Collection python file** that collects images from the webcam for all the signs in the Indian Sign Language. 

The model was made only with help of Nicholas Renotte tutorial.

## LOGIN_PAGE

![image](https://user-images.githubusercontent.com/115984518/198564084-e8e66894-c800-4ab3-be65-cc8e0ec5634b.png)

## Importance of Each file

* Collect-data.py file: I was not able to find the correct dataset. Then I decided to create my own dataset. Using this file Own Dataset for each Character will be created
* Image_processing.py & preprocessing.py files: To improve the accuracy of the project I converted the RGB Images to Black & white Image. After Conversion I applied Gaussian Blur Filter which focuses on Boundry of the Sign Language.
* train.py file: File contains the code of model training.
* app.py File: Contains the code of Front End which is created using TKinter.

## Steps to Execute:
* I have uploaded dataset. Execute Collect data file first and Create your own Dataset for each character.
* Execute Image processing and Preprocessing files. So the Black & White Images of your dataset will be created.
* Execute train.py file so json & h5 files for your dataset will be created
* Execute the App.py file so the frontend will be loaded & conversion of each sign language will be displayed

