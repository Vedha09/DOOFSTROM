# DOOFSTROM

* Reads your hand signs and translates them to English words and voice output using Tensorflow object detection.<br/>
* The dataset is made manually by running the **Image Collection python file** that collects images from the webcam for all the signs in the Indian Sign Language. 

The model was made only with help of Nicholas Renotte tutorial.

## Database_project
<br/>
https://drive.google.com/drive/folders/1ZVu74TR2fl97ijLBrg4V-AJG5Q3JoFW6?usp=share_link
<br/>

## Database_tested_image
<br/>
https://drive.google.com/drive/folders/1ZVu74TR2fl97ijLBrg4V-AJG5Q3JoFW6?usp=sharing
<br/>

## LOGIN_PAGE

![image](https://user-images.githubusercontent.com/115984518/198564084-e8e66894-c800-4ab3-be65-cc8e0ec5634b.png)


## Steps to Execute:
* I have uploaded dataset. Execute Collect data file first and Create your own Dataset for each character.
* Execute Image processing and Preprocessing files. So the Black & White Images of your dataset will be created.
* Execute train.py file so json & h5 files for your dataset will be created
* Execute the App.py file so the frontend will be loaded & conversion of each sign language will be displayed

## How Frontend Works:
* Once the Frontend is loaded.
* Show the Sign language of character you wanted to translate
* For the 5frames predicted text conversion will be stored in backend and most predicted character will be displayed in front of character.
* When all the characters will be predicted don't show any sign language in screen. When Model finds blank screen it predicts word is completed.
* After Predicting all characters it will be shifted in front of word and if blank screen continues it will be shifted in front of sentence.

## Source_code_image_detection
<br/>
https://docs.google.com/document/d/1D2dEWvaevWLBJg5aGfkpiWMZKcV0pNcD/edit?usp=share_link&ouid=107885165483411500951&rtpof=true&sd=true
<br/>

