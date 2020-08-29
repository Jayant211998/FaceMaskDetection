# FaceMaskDetection
This is a deep learning based project which helps us to identify weather a person is wearing a face mask or not

Data Gathering
It consists of a script written in python language which is used to download the images required to create the dataset from google.
For this we just need to write a query. It uses tools like selenium webdriver.

Dataset Creation
After gathering the images for the data we try to create a dataset. It is done by first analysing the images and marking humen faces
in it and then I just converted the data to npy fileto save the dataset.

Training 
In the training file if have used CNN to train the model.

Application 
This file consist of the application part.It detects the humenface using opencv and haarcascade_frontalface_default.xml and then using
the trained model it detects if someone is wearing facemask or not. It can detect more than one face at a time and denote the output by 
showing the face in green or red color rectangle. It also clicks image of the face without facemask. 
