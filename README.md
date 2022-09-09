
# Hand Sign Detection(ASL)
<p align="center">
<kbd>
   <img align="center" src="https://user-images.githubusercontent.com/54831801/189453434-fbef14f5-9d70-4089-9035-274b6bf66462.png" width="700" height="500">
</kbd>
</p>

## Description 
In this project, we will learn how to create a hand sign detector. We will use American Sign Language as an example. This project will include both detection and classification. 
And yes we will use our own data to train the model.
For collecting data we use data_collection.py and for training the model we use Teachable Machine which is an online platform for training our modle and then we use test.py for prediction phase.  

## Data Collector
In order to collect data for each specific sign we have to create a directory in data folder with the name of that sign and then in the data_collection.py, line 13 we refer to that folder and then run the file and after that, by pressing 's' button we are going to collect data by using webcam.

## Train The Model
In this project instead of write a python file to create our model and train the data with it, we used an online platform called "Teachable Machine". The link of this website is as follows:

[link](https://teachablemachine.withgoogle.com/)
## Real Time Prediction
After training our data with the model and save the weights, we are ready to go for prediction phase. By using the the prediction.py file we could test our model by using webcam.

## Demo
