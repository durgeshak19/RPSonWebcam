# Rock Paper Scissor on webcam

This project uses a webcam to capture image on webcam to classify Rock paper scissor. The dataset is used is at link http://www.laurencemoroney.com/rock-paper-scissors-dataset/. The project is made using Tensorflow.js a library for machine learning using javascript. It uses javascript to develop models directly into web browser . 

#About the Project

This project uses user generated dataset and labels to further train on a previously trained model . This allows for better classification in accordance with the each specific user.
This project is made by transfer learning on the famous "keras-mobilenet" architecture which performs quite well for small applications. Mobilenet classifies 1000 labels which is then reduced by further adding neural layers to classify 3 labels (rock,paper,scissors). 

#How to Use
step 1 : Run retrain.html using a web browser .
step 2 : Create small dataset of each labels by capturing rock and clicking on rock label .repeat for all 3.
step 3 : Then tain the model model using the button and thats it after a few moments it will start classifying images.

